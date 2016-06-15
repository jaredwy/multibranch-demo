
stage 'pre-setup'
node {
    checkout scm
    sh 'npm install'
}

stage 'validate'
node {
    sh 'grunt task1'
}