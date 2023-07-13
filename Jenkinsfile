node{
    stage ('ckeckout scm'){
        git branch: 'main', url: 'https://github.com/Simplilearn-Edu/estore-admin-dashboard.git'
    }

    stage ('install node modules'){
        sh "npm install"
    }
}