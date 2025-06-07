pipeline{
	agent any
	tools{
	maven 'MAVEN_HOME'
	}
	stages{
		stages('Build')
			steps{
				bat 'mvn clean install'
}
}
}
}
