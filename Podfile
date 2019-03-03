use_frameworks!

# NEW ======================

install! 'cocoapods',
         :generate_multiple_pod_projects => true,
         :incremental_installation => true

target 'PodNews_Example' do
	# NEW ======================
  pod 'PodNews', :path => '../', :appspecs => ['Example']

  target 'PodNews_Tests' do
    inherit! :search_paths

    pod 'Quick', '~> 1.2.0'
    pod 'Nimble', '~> 7.0.2'
  end
end
