node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'shahritesh1602') {

        def customImage = docker.build("shahritesh1307/docker-test")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
