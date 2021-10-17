node {
    checkout scm
    /*
     * In order to communicate with the MySQL server, this Pipeline explicitly
     * maps the port (`3306`) to a known port on the host machine.
     */
    docker.image('ubi8/python-39') { c ->
        /* Wait until mysql service is up */
        sh "python --version"
    }
}
