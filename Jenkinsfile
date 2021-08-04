#!groovy
@Library('jenkins-pipeline') import com.github.jcustenborder.jenkins.pipeline.ConnectDockerPipeline

def pipe = new ConnectDockerPipeline()
pipe.imageName = 'cp-kafka-connect'
pipe.majorVersion = 6
pipe.minorVersion = 1
pipe.patchVersion = 1
pipe.repositories = [
    ['credential': 'hub.docker.com', 'registry': 'https://registry.hub.docker.com', 'repository': 'jcustenborder']
]
pipe.execute()

