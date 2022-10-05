node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("imransharkar1481/php")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
