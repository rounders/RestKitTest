$:.unshift("/Library/RubyMotion/lib")
require 'motion/project'

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'RestKitTest'
  app.frameworks += %w(CoreData CFNetwork Security MobileCoreServices SystemConfiguration QuartzCore)
  app.vendor_project('vendor/RestKit', :xcode, target: 'RestKit')
end
