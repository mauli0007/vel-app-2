pipeline {
		agent {

			label {

				label "built-in"
				customWorkspace "/mnt/project"

				}
		}

		stages {

				stage ("mkdir") {

				steps {
					sh"rm -rf *"
					
					sh "cd vel-app-2 && cp -r index.html /var/www/html"
					sh "chmod -R 777 /mnt"


 					}							
				}


	}

}
