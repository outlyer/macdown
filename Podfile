platform :osx, "12.3"

source 'https://cdn.cocoapods.org/'
source 'https://github.com/MacDownApp/cocoapods-specs.git'  # Patched libraries.


project 'MacDown.xcodeproj'

inhibit_all_warnings!

target "MacDown" do
  pod 'handlebars-objc', '~> 1.4.6'
  pod 'hoedown'
  pod 'JJPluralForm', '~> 2.1'
  pod 'LibYAML', '~> 0.1'
  pod 'M13OrderedDictionary', '~> 1.1'
  pod 'MASPreferences', '~> 1.3'
  pod 'Sparkle' #, '~> 1.18' , :inhibit_warnings => false

  # Locked on 0.4.x until we drop 10.8.
  pod 'PAPreferences', '~> 0.5'
end

