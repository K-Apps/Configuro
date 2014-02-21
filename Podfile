#Podfile

xcodeproj 'Configuro/Configuro.xcodeproj'

# Select the appropriate platform below
# Specify the minimum supported iOS version (or later) required by Kiwi
# platform :ios, '7.0'
platform :osx, '10.9'

# Add Kiwi as an exclusive dependency for the RPNTests target
# target :RPNTests, :exclusive => true do
#    pod 'Kiwi'
# end

# If you're using Xcode 5 with a brand new project
# (XCTest based instead of OCUnit based) use this instead:
target :ConfiguroTests, :exclusive => true do
   pod 'Kiwi/XCTest'
end

