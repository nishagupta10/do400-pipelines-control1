
node('nodejs') {
stage('Checkout') {
git branch: 'main',
url: 'https://github.com/nishagupta10/do400-pipelines-control1'
}
stage('Backend Tests') {
sh 'node ./backend/test.js'
}
stage('Frontend Tests') {sh 'node ./frontend/test.js'
}
}
