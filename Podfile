# Uncomment this line to define a global platform for your project
# platform :ios, "6.0"

def import_pods
  pod 'libextobjc', '0.3'
  pod 'ReactiveCocoa', '2.1.8'
  pod 'ReactiveViewModel', '0.1.1'
end

target "C-41" do
  
  import_pods

  pod 'UIColor-Utilities', '1.0.1'

  inhibit_all_warnings!

end

target "C-41Tests" do

  import_pods

  pod 'Specta',      '~> 0.2.1'
  pod 'Expecta',     '~> 0.2.3'
  pod 'OCMock',      '~> 2.2.1'

  inhibit_all_warnings!

end

