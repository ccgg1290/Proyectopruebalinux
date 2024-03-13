node() {
  
        
        stage('Start Testing'){
        	withMaven(maven: 'maventool') {
        	    echo 'hola mundo'
        	    sh  'mvn -version'
        	    sh  'java -version'

                sh "mvn clean verify"
                  
            }   
        }
}
