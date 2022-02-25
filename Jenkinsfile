node {            
    stage ('Scm checkout') {
        git url: 'https://github.com/Nazar802/manifests.git'
    }
    
    stage ('Kubectl apply') {
        sh "kubectl apply -f nginx.yaml"
    }
}
