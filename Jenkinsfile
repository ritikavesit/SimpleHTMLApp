node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/ritikavesit/SimpleHTMLApp.git'
    }

    stage('Build') {
        echo 'No build needed'
    }

    stage('Deploy') {
        bat '''
        mkdir C:\\deploy
        xcopy /E /I /Y * C:\\deploy
        '''
    }
}
