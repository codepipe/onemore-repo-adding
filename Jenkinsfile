pipeline {
    agent any
    stages {
        stage ("this is the first stage") {
            steps {
                bat "ipconfig"
            }
        }
        stage ("this is the second stage") {
            steps {
                echo "PSVersionTable"
            }
        }
        stage ("check the java version") {
            steps {
                bat "java -version"
            }
        }
        stage ("create the folders of below list") {
            steps {
               powershell 'New-Item -Type directory "c:\\sharat\\vikas\\vinaya\\thomson\\prakash"'
            }
           
        }
        stage ("successfully ran the sample pipline script") {
            steps {
                echo "yes ran"
            }
        }
    }
}
