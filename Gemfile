default_platform(:ios)

platform :ios do
  desc "Build the iOS app without signing"
  lane :build do
    build_app(
      workspace: "FastlaneCacheTest.xcworkspace",
      scheme: "FastlaneCacheTest",
      clean: true,
      skip_codesigning: true
    )
  end
end

