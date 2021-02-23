pipeline {

    agent { label 'master'}

    stages{
          stage('SCM'){
              steps { 
                  git branch : 'develop',url:'https://github.com/r009504/Remote_Game_Node.git'
              }
                  }

          stage('BUILD'){
              steps{
                  sh 'pwd'
              }
          }
    }        
}