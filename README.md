# Introduction Jenkins

This repo contains a brief and simple introduction to Jenkins and its configuration on MacOS. The first thing to do is installing Jenkins:

```zsh
brew install jenkins
```

This is a non stable version of Jenkins that contains the newest features, if you want to install the stable version install the `jenkins.lts` package. Once installation is complete start the service and open http://localhost:8080 to get the Jenkins GUI, here you'll have to create and admin account the first time you do this.

```zsh
brew services start jenkins
```
