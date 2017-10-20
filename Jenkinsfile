node('unix') {
    if( env.BRANCH_NAME == "master" ) {
        properties([disableConcurrentBuilds()])
    }
    sleep time: 10, unit: 'MINUTES'
}