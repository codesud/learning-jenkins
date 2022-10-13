// node {
//     stage('Demo') {
//         print 'Hello World'
//     }
// }

// sample if else scripted pipeline
node {
    stage('Demo') {
        print 'Hello World'
    }
}

if (env.BUILD_URL == "") {
    stage ('EMPTY') {
        print 'Empty World'
    } 
}
else {
    stage ('Not Empty') {
        print 'Else World'
    }
}
