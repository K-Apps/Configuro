# sPodfile

workspace 'Configuro.xcworkspace'
xcodeproj 'GUI/GUI.xcodeproj'

target 'GUI', :exclusive => true do
	platform :osx, '10.9'
	xcodeproj 'GUI/GUI.xcodeproj'
	# XCTest based
	target :GUITests, :exclusive => true do
   		pod 'Kiwi/XCTest'
	end
end

target 'Model', :exclusive => true do
	platform :osx, '10.9'
	xcodeproj 'Model/Model.xcodeproj'
	# XCTest based
	target :ModelTests, :exclusive => true do
   		pod 'Kiwi/XCTest'
	end
end
