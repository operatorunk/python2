pipeline {
    agent {label 'windows'}
    stages {
        stage('build') {
            steps {
                script {
                    //echo "**************Show env variables *******************"
                    //echo env.PATH
                    //bat 'echo %PATH%'
                    //bat 'wmic computersystem get name'
                    //echo bat(returnStdout: true, script: 'dir')
                    //echo "**************Show Chocolatey help *******************"
                    //echo bat(returnStdout: true, script: 'choco -?')
                    //echo "**************Install python *******************"
                    //echo bat(returnStdout: true, script: 'choco install python -y')
                    echo bat(returnStdout: true, script: 'cd C:\\Users\\Administrator\\Desktop && py -2 Hello_python2.py')
                    echo bat(returnStdout: true, script: 'py -3 C:\\Users\\Administrator\\Desktop\\Hello_python3.py')
                    
                    
                }
            }
        }
    }
}





