properties  ([
    parameters  ([
            string(defaultValue: '', description: '''The number of the W manif
(Example: W-25)''', name: 'W', trim: false), 
            string(defaultValue: '', description: '''The number of the Wthat came before the current ticket
(Example: W-24)''', name: 'Previous Wr', trim: false), 
            password(defaultValue: '', description: 'Jira technical user\'s credentials encoded in Base64', name: 'SECRET')
                ])
            ])
pipeline {

    
   agent any
   
   
   stages {
      stage('Hello') {
         steps {
             sleep time: 5, unit: 'NANOSECONDS'
            echo 'Hello World'
            sh label: '', script: 'ls -la'
            sh("python3 python.py")
             sleep time: 5, unit: 'NANOSECONDS'
            git 'https://github.com/alexxxnaumenko/TestForJenkins.git'
         }
      }
   }
}
