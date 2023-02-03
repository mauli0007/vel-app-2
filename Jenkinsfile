pipeline {
		agent {

			label {

				label "built-in"
				

				}
		}

		stages {

				stage ("mkdir") {

				steps {
					
					sh"rm -rf *"
					sh "cd vel-app-2 "
					sh "cp index.html /var/www/html"
					

 					}							
				}


	}

}
