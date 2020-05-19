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
            git 'https://github.com/alexxxnaumenko/TestForJenkins.git'
            sh("ls -l")
         }
      }
   }
}
