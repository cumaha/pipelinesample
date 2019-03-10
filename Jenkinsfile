pipeline {
	agent any
	stages {
		stage("Clone_Repository") {
			steps {
				echo 'Cloning started'
				echo 'Clone is Completed'
			}
		}
		
		stage("Compile") {
			steps {
				echo 'Compile is in Progress'
				echo 'Compilation is Completed'
			}
		}
		
		stage("Unit_Testing") {
			steps {
				echo 'Unit Testing is in Progress'
				echo 'Unit Testing is Completed'
			}
		}

		stage("Test_Coverage") {
			steps {
				echo 'Test Coverag in Progress'
				echo 'Test Coverage is Completed'
			}
		}
		stage("Func_Testing") {
					steps {
						echo 'Functional Testing is started'
						echo 'Functional Testing is completed'
					}
				}
		stage("UAT_Testing") {
					steps {
						echo 'UAT Testing is completed'
					}
				}
		stage("Performance_Testing") {
					steps {
						echo 'Performance Testing is completed'
					}
				}
		
		stage("PROD Deploy") {
			steps {
				echo "Deploy!"
			}
		}
}
}
