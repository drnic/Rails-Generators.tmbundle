require 'bundler'

desc "Show the list of snippets/commands/drags"
task :list do
  require "plist"
  
  def load_actions(action_type)
    root = File.expand_path('..', __FILE__)

    if File.directory?(File.join(root, action_type))
      Dir[File.join(root, action_type, '*')].sort.map do |action_file|
        Plist.parse_xml(File.read(action_file))
      end  
    else
      []
    end
  end
  
  # DragCommands
  actions = load_actions('DragCommands')
  actions.each do |action|
    name = action['name']
    file_ext = action['draggedFileExtensions']
    puts "DragCommands -> #{name} #{file_ext.inspect}"
  end

  # Others
  action_types = %w[Snippets Commands]
  action_types.each do |action_type|
    actions = load_actions(action_type)
    actions.each do |action|
      name = action['name']
      tab_trigger = action['tabTrigger']
      puts "#{action_type} -> #{name} [#{tab_trigger}]"
    end
  end
end