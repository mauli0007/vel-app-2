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
					sh "cd /mnt/vel-app-2/ && index.html /var/www/html "
 					}							
				}


	}

}
