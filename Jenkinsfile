def jenkins_path= "/var/lib/jenkins"

node {

    stage('scm'){

        checkout scm
    }


    stage('git'){

      sh "branchname=`git branch -a | grep remotes/origin/PR`"
      sh "git checkout \$branchname"
    }
  
    stage('error'){
      sh "cat aiueo"
    }
   
}
