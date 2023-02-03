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
					sh "yum install httpd -y"
					sh "service httpd start"
					sh "mkdir mauli"
					sh "cd vel-app-2 && cp index.html /var/www/html"
					sh "chmod -R 777 /mnt"


 					}							
				}


	}

}
