pipeline{
		agent any
		stages{
				stage("clean up"){
									steps{
									bat 'del /q *'
									for /d %x in (*) do @rd /s /q "%x"
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