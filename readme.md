# Ionic 4 Auth CLI

Starting point for Ionic 4 Application with Authentication build in.

## Getting Started

If your Ionic 4 application needs authentication, you have came on right page. If you are starting a completely new project, then you can just clone this and start working on it. This will save your couple of hours for sure.

In this Project I’m using side menu template of Ionic 4. If you already have a project then you can go to [Ionic Auth](https://github.com/flicher-net/ionic-4-auth) and copy only files.


### Prerequisites

[Ionic Framework Docs](https://ionicframework.com/docs/)

[Node](https://nodejs.org/)

### Installing

If you want to install the project local, you can using following command.

```
git clone https://github.com/flicher-net/ionic-4-auth-cli.git
```

CD into project

```
cd ionic-4-auth-cli/
```

Install Node Modules

```
sudo npm install
```

If you are using mac, you might get ENFILE: file table overflow errors, you can use these commands to solve it.

```
echo kern.maxfiles=65536 | sudo tee -a /etc/sysctl.conf
echo kern.maxfilesperproc=65536 | sudo tee -a /etc/sysctl.conf
sudo sysctl -w kern.maxfiles=65536
sudo sysctl -w kern.maxfilesperproc=65536
ulimit -n 65536 65536    
```

## Deployment

[iOS Setup](https://ionicframework.com/docs/installation/ios)

[Andriod Setup](https://ionicframework.com/docs/installation/android)

## Built With

[Ionic Framework](https://ionicframework.com/)

## Follow me on Twitter

[Twitter](https://twitter.com/_varunverma)
