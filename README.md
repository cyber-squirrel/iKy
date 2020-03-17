<div align="center">
    <a href="https://twitter.com/intent/follow?screen_name=kennbroorg">
	<img alt="follow on Twitter" src="https://img.shields.io/twitter/follow/kennbroorg.svg?label=follow%20%40kennbroorg&style=social">
    </a>
</div>

---

<div align="center">
    <img alt="Redis" src="https://img.shields.io/badge/storage-redis-red.svg">
    <img alt="Python" src="https://img.shields.io/badge/python-3.7-informational.svg">
    <img alt="Celery" src="https://img.shields.io/badge/multiprocessing-celery-green.svg">
    <img alt="Flask" src="https://img.shields.io/badge/interface-flask-yellowgreen.svg">
</div>
<div align="center">
    <img alt="Node" src="https://img.shields.io/badge/node-%3E%208.x-brightgreen.svg">
    <img alt="Angular" src="https://img.shields.io/badge/web%20framwork-angular%207-red.svg">
    <img alt="Boostrap" src="https://img.shields.io/badge/toolkit-boostrap-blueviolet.svg">
    <img alt="UI Kit" src="https://img.shields.io/badge/UI%20Kit-Nebular-9cf.svg">
</div>
<div align="center">
    <img alt="fullcontact" src="https://img.shields.io/badge/module-fullcontact-blue.svg">
    <img alt="twitter" src="https://img.shields.io/badge/module-twitter-blue.svg">
    <img alt="linkedin" src="https://img.shields.io/badge/module-linkedin-blue.svg">
    <img alt="github" src="https://img.shields.io/badge/module-github-blue.svg">
    <img alt="keybase" src="https://img.shields.io/badge/module-keybase-blue.svg">
    <img alt="ghostproject" src="https://img.shields.io/badge/module-ghostproject-red.svg">
    <img alt="haveibeenpwned" src="https://img.shields.io/badge/module-haveibeenpwned-blue.svg">
    <img alt="emailrep.io" src="https://img.shields.io/badge/module-emailrep.io-blue.svg">
    <img alt="socialscan" src="https://img.shields.io/badge/module-socialscan-blue.svg">
    <img alt="instagram" src="https://img.shields.io/badge/module-instagram-blue.svg">
    <img alt="tiktok" src="https://img.shields.io/badge/module-tiktok-blue.svg">
</div>

---

<div align="center">
    <a href="https://gitlab.com/kennbroorg/iKy/blob/iKy/README.es.md">
	<img alt="README Espanol" src="https://img.shields.io/badge/README-Espa%C3%B1ol-orange.svg">
    </a>
</div>

---

<div align="center">
    <img alt="Logo" src="https://kennbroorg.gitlab.io/ikyweb/assets/img/Logo-Circular.png">
</div>

---

# iKy

## Description
Project iKy is a tool that collects information from an email and shows results in a nice visual interface.

Visit the Gitlab Page of the [Project](https://kennbroorg.gitlab.io/ikyweb/)

<div align="center">
    <a href="https://vimeo.com/347085110"><img src="frontend/src/assets/images/Giba.gif"></a>
</div>

[Video Demo](https://vimeo.com/347085110 "Video Demo - Click to Watch!")



## Installation

### Clone repository

```shell
git clone https://gitlab.com/kennbroorg/iKy.git
```

### Install Backend

#### Redis

You must install Redis

```shell
wget http://download.redis.io/redis-stable.tar.gz
tar xvzf redis-stable.tar.gz
cd redis-stable
make
sudo make install
```

#### Python stuff and Celery

You must install the libraries inside requirements.txt

```shell
python3 -m pip install -r requirements.txt
```

### Install Frontend

#### Node

First of all, install [nodejs](https://nodejs.org/en/).

#### Dependencias

Inside the directory **frontend** install the dependencies

```shell
cd frontend
npm install
```



## Wake up iKy Tool

### Turn on Backend

#### Redis

Turn on the server in a terminal

```shell
redis-server
```

#### Python stuff and Celery

Turn on Celery in another terminal, within the directory **backend**

```shell
./celery.sh
```

Again, in another terminal turn on backend app from directory **backend** 

```shell
python3 app.py
```

### Turn on Frontend

Finally, to run frontend server, execute the following command from directory **frontend**

```shell
npm start
```

### Screen after turn on iKy

<div align="center">
    <img src="frontend/src/assets/images/Screens1000.png">
</div>

### Browser

Open the browser in this [url](http://127.0.0.1:4200) 

### Config API Keys

Once the application is loaded in the browser, you should go to the Api Keys option and load the values of the APIs that are needed.

- Fullcontact: Generate the APIs from [here](https://support.fullcontact.com/hc/en-us/articles/115003415888-Getting-Started-FullContact-v2-APIs)
- Twitter: Generate the APIs from [here](https://developer.twitter.com/en/docs/basics/authentication/guides/access-tokens.html)
- Linkedin: Only the user and password of your account must be loaded
- HaveIBeenPwned : Generate the APIs from [here](https://haveibeenpwned.com/API/Key) (Paid)
- Emailrep.io : Generate the APIs from [here](https://emailrep.io/key)

# Wiki

- [iKy Wiki](https://gitlab.com/kennbroorg/iKy/-/wikis/home)
- [iKy Page](https://kennbroorg.gitlab.io/ikyweb/)
- Installation
  - [Easy Install](https://gitlab.com/kennbroorg/iKy/-/wikis/Installation/EasyInstall)
  - [Vagrant](https://gitlab.com/kennbroorg/iKy/-/wikis/Installation/Vagrant)
  - [Manual install (Compacted)](https://gitlab.com/kennbroorg/iKy/-/wikis/Installation/Manual-install-(Compacted))
  - [Manual install (Detailed)](https://gitlab.com/kennbroorg/iKy/-/wikis/Installation/Manual-install-(Detailed))
- Update
  - [Soft Update](https://gitlab.com/kennbroorg/iKy/-/wikis/Update/Soft)
- Wake Up 
  - [Turn on the project](https://gitlab.com/kennbroorg/iKy/-/wikis/Wakeup/WakeUp)
- APIs
  - [APIs through frontend](https://gitlab.com/kennbroorg/iKy/-/wikis/APIs/ApiKeys-through-the-browser)
  - [APIs through backend](https://gitlab.com/kennbroorg/iKy/-/wikis/APIs/APIs-through-the-backend)
- Backend
  - [Backend through URL](https://gitlab.com/kennbroorg/iKy/-/wikis/Backend/Backend-through-url)
- Videos
  - [Installation videos](https://gitlab.com/kennbroorg/iKy/-/wikis/Videos/Installations)
    - [Installation in Kali 2019](https://vimeo.com/350877994) 
    - [Installation in ubuntu 18.04](https://vimeo.com/347435255) 
    - [Installation in ubuntu 16.04](https://vimeo.com/332359273) 
  - [Demo videos](https://gitlab.com/kennbroorg/iKy/-/wikis/Videos/Demos)
    - [iKy eko15](href="https://vimeo.com/397862772)
    - [iKy version 2](https://vimeo.com/347085110)
    - [Testing iKy with Emiliano](https://vimeo.com/349011105)
    - [Testing iKy with Giba](https://vimeo.com/342843348)
    - [iKy version 1](https://vimeo.com/326114716)
    - [iKy version 0](https://vimeo.com/272495754)
- [Disclaimer](https://gitlab.com/kennbroorg/iKy/-/wikis/Disclaimer)

## Demo Videos

<div align="center">
    <a href="https://vimeo.com/397862772"><img alt="Kali 2019" src="uploads/8ef7b21b6c6e5450cc919b3ab74b4b40/iKyEko15.png"></a>
    <p>iKy eko15</p>
</div>

<div align="center">
    <a href="https://vimeo.com/347085110"><img alt="Kali 2019" src="uploads/75d9b968c865bd54f9bfb538b6a3d394/Ikyv2.png"></a>
    <p>iKy Version 2</p>
</div>

<div align="center">
    <a href="https://vimeo.com/349011105"><img src="uploads/49a5525dbe4bc7e42b97739aedf9380f/Emiliano.png"></a>
    <p>Testing iKy with Emiliano</p>
</div>

<div align="center">
    <a href="https://vimeo.com/342843348"><img src="uploads/1adfd331102577141c6905a247bb4216/Giba.png"></a>
    <p>Testing iKy with Giba</p>
</div>

<div align="center">
    <a href="https://vimeo.com/326114716"><img src="uploads/8dfaed2ea390fed9725926a384ede50d/ikyDemoV1.png"></a>
    <p>iKy version 1</p>
</div>

<div align="center">
    <a href="https://vimeo.com/272495754"><img src="uploads/8413daae9082f8668d2efe9a46ac8531/ikyDemov0.png"></a>
    <p>iKy version 0</p>
</div>

## Disclaimer

Anyone who contributes or contributed to the project, including me, is not responsible for the use of the tool (Neither the legal use nor the illegal use, nor the "other" use).

Keep in mind that this software was initially written for a joke, then for educational purposes (to educate ourselves), and now the goal is to collaborate with the community making quality free software, and while the quality is not excellent (sometimes not even good) we strive to pursue excellence.

Consider that all the information collected is free and available online, the tool only tries to discover, collect and display it.
Many times the tool cannot even achieve its goal of discovery and collection. Please load the necessary APIs before remembering my mother.
If even with the APIs it doesn't show "nice" things that you expect to see, try other e-mails before you remember my mother.
If you still do not see the "nice" things you expect to see, you can create an issue, contact us by e-mail or by any of the RRSS, but keep in mind that my mother is neither the creator nor Contribute to the project.

We do not refund your money if you are not satisfied.
I hope you enjoy using the tool as much as we enjoy doing it. The effort was and is enormous (Time, knowledge, coding, tests, reviews, etc.) but we would do it again.
Do not use the tool if you cannot read the instructions and / or this disclaimer clearly.

By the way, for those who insist on remembering my mother, she died many years ago but I love her as if she were right here.

[readmees]: README.es.md
[readmeen]: README.md
