pipeline {
 agent {
label {
label "Slave1" 
customWorkspace "/mnt/pipeline"
}
}
stages {
stage ("stage-1") {
steps {
sh "sudo service httpd start"
sh "sudo cp -r index.html /var/www/html"
sh "sudo chmod -R 777 /var/www/html/index.html"
}
}
}
}
