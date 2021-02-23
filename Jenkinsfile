peipeline {

    agent { label 'SLAVE01'}

    stages{
          stage('SCM'){
              steps { 
                  git branch:'qa',url:'https://github.com/r009504/Remote_Game_Node.git'
              }
                  }
          stage('BUILD'){
              steps{
                  sh 'hostname'

              }

          }
    }        
}