pipeline {
    agent any 
            stages{
                 stage ('Build'){
                              steps { 
                                  echo "This is build stage"
                  bat "rm -rf springExample
                  bat "mvn clean -f springExample" 
                                 }
                 }
           
                 stage ('Test'){
                              steps { 
                                  echo "This is test stage"
                  bat "mvn test -f springExample"
                                 }
                 }
           
                 stage ('Deploy'){
                              steps { 
                                  echo "This is deploystage"
                  bat "mvn package -f springExample"
                                 }
                 }
           
}
