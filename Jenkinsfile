node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'docker-hub-credentials') {

        def customImage = docker.build("George-Nyamao/node-web-app")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
