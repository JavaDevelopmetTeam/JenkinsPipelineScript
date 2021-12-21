	pipeline{
	
		agent {
			label 'master'
		}
		
		stages{
		
			stage('linux'){
			
				agent {
					label 'maven'
				}
					
				steps{
					println "From decalarative pipeline script - build stage"
				}
			
			}
			
			stage('windows'){
			
				agent {
					label 'dotnet'
				}
				
				steps{
					println "From decalarative pipeline script - deploy stage"
				}
			
			}
		
		}
	
	}
