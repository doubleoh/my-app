pipeline{
		agent any
		stages{
				stage("clean up"){
									steps{
									bat 'mvn clean'
									}
				}
				stage("build"){
								steps{
										bat 'mvn build'
									}
				}
				stage("test"){
								steps{
										bat 'mvn test'
								}
							}
		}
}