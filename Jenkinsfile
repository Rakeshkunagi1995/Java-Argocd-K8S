pipeline {
    agent { label 'jenkins-agent' }
    tools {
        jdk 'java17'
        maven 'maven3'
    }

stages{
        stage("Cleanup Workspace"){
                steps {
                cleanWs()
                }
        }

	stage("Checkout from SCM"){
                steps {
                    git branch: 'master', credentialsId: 'github', url: 'https://github.com/Rakeshkunagi1995/Java-Argocd-K8S.git'
                }
        }










	}


}
