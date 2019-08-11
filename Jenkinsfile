node ('Srikpkash') {
	WS = env.WORKSPACE
	checkout scm
    stage ('Build') {
        println("Building the multi branch pipeline app using the tool maven")
		sh "mvn -f $WS/pom.xml clean package"
    }
    stage ('Deploy') {
         println("Application deployed successfully")
    }
}
