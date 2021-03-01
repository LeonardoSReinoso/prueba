// Powered by Infostretch 

timestamps {

node () {

	stage ('helloworld - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '83084695-575b-486f-87ee-f7d88746577e', url: 'https://github.com/leodeoz/prueba.git']]]) 
	}
	stage ('helloworld - Build') {
 	
// Unable to convert a build step referring to "hudson.plugins.timestamper.TimestamperBuildWrapper". Please verify and convert manually if required.		// Shell build step
sh """ 
echo 'hola mundo' 
 """ 
	}
}
}