pipeline {
	agent any
	stages {
		stage("Clone_Repository") {
			steps {
				sleep 10
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
		stage("Security_Testing") {
			steps {
				 sleep 10	
				 echo 'Security Testing is completed'
				}
		}
		stage("Exploratory_Testing") {
			steps {
				 sleep 15	
				 echo 'Exploratory Testing is completed'
				}
		}
		stage("Performance_Testing") {
					steps {
						sleep 5
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
