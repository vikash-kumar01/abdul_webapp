@Library('my-shared-library') _

pipeline{

    agent any

    stages{

        stage('Git Checkout'){

            steps{
            gitCheckout(
                branch: "main",
                url: "https://github.com/Abdulsalam16/mrdevops_java_app.git"
            )
            }
       }
    }
}