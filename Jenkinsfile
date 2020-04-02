node {

    checkout scm

    docker.withRegistry('https://hub.docker.com', 'dockerHub') {

        def customImage = docker.build("milindlasurve1/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
