pipeline {
    agent any 
    options {
        timestamps()
        checkoutToSubdirectory(some)
        // hello 
    
    }
        stages {
            stage ("Build"){
                steps {
                    echo " making build unstable useing global variable"
                }
            }
            stage ("Deploy"){
            steps {
                echo "build is Deploying"
            }
        }
    }
}
