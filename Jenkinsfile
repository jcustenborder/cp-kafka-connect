#!groovy
@Library('jenkins-pipeline') import com.github.jcustenborder.jenkins.pipeline.ConnectDockerPipeline

def pipe = new DockerPipeline()
pipe.imageName = 'cp-kafka-connect'
pipe.majorVersion = 6
pipe.minorVersion = 0
pipe.patchVersion = 0
pipe.repositories = [
    ['credential': 'custenborder_docker', 'registry': 'https://docker.custenborder.com', 'repository': 'jcustenborder']
]
pipe.execute()

