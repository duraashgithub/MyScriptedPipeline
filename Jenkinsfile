node {
    stage('Checkout') {
        echo "Building branch: ${params.BRANCH}"
        
    }
    
    stage('Build') {
        sh "echo Building on branch: ${params.BRANCH}"
        
    }
    
    stage('Test') {
        if (params.BRANCH == 'main') {
            echo 'Running tests for main branch'
        } else {
            echo "Skipping tests for branch: ${params.BRANCH}"
        }
    }
}
