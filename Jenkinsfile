pipeline {
	agent any
	stages {
		stage("Clone_Repository") {
			steps {
				echo 'Clone is in Progress'
				bat 'ping 127.0.0.1 -n 10 > nul'
				bat 'echo.'
				echo 'Clone is Completed'
			}
		}
		
		stage("Compile") {
			steps {
				echo 'Compile is in Progress'
				bat 'ping 127.0.0.1 -n 7 > nul'
				bat 'echo.'
				echo 'Compilation is Completed'
			}
		}
		
		stage("Unit_Testing") {
			steps {
				echo 'Unit Testing is in Progress'
				bat 'ping 127.0.0.1 -n 15 > nul'
				bat 'echo.'
				echo 'Unit Testing is Completed'
			}
		}

		stage("Test_Coverage") {
			steps {
				echo 'Test Coverag in Progress'
				bat 'ping 127.0.0.1 -n 9 > nul'
				bat 'echo.'
				echo 'Test Coverage is Completed'
			}
		}
		stage("Func_Testing") {
					steps {
						bat 'ping 127.0.0.1 -n 9 > nul'
						bat 'echo.'
						echo 'Functional Testing is completed'
					}
				}
		stage("UAT_Testing") {
					steps {
						bat 'ping 127.0.0.1 -n 9 > nul'dd
						bat 'echo.'
						echo 'UAT Testing is completed'
					}
				}
		stage("Performance_Testing") {
					steps {
						bat 'ping 127.0.0.1 -n 9 > nul'
						bat 'echo.'
						echo 'Performance Testing is completed'
					}
				}
		
		stage("Deploy") {
			steps {
				echo "Deploy!"
			}
		}
}
}
