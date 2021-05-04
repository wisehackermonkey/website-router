# website-router
----
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<!-- <img src="assets/NNNNNNNNNNNNN" width="400"> -->
<h2 align="center">how I handle routing the example.com/routeNAME to the different containers on my website "oran.business"</h2>

<h4 align="center">uses nginx as the router</h4>


# Quick start
### __________________
```
Pixilate image server: pixel-artist 6451
Chirp.io 1199
Blank Page Website 11111
Remash 7788
```
<!-- 
##### __________________________
```bash
``` 
-->

# Summary
<!-- ### -  *[Quick start](#Quick-start)* -->
### -  *[Installation](#Installation)*
### -  *[For developers](#For-developers)*
### -  *[Contributors](#Contributors)*
### -  *[License](#License)*




# Installation
### Docker non compose (testing only)
```bash
cd ~
git clone https://github.com/wisehackermonkey/website-router.git
cd website-router
docker run --rm -it --name web-redirector --net=host -v $PWD/nginx.conf:/etc/nginx/nginx.conf:ro nginx
```


### Docker  compose (deployment )
```bash
cd ~
git clone https://github.com/wisehackermonkey/website-router.git
cd website-router
docker run --restart always -d --name web-redirector --net=host -v $PWD/nginx.conf:/etc/nginx/nginx.conf:ro nginx
```
### Docker composer
```
cd ~
git clone https://github.com/wisehackermonkey/website-router.git
cd website-router
docker-compose up -d
```
<!-- ----------------- -->
<!-- # Screenshots -->
<!-- - <img src="assets/_____________" width="400">  -->
<!-- -  -->



<!-- SETUP -->
-----------------
# For developers
### 
```bash
docker run -it --rm -d -p 8080:80 --name web nginx
```

-----------------
# Contributors

[![](https://contrib.rocks/image?repo=wisehackermonkey/website-router)](https://github.com/wisehackermonkey/website-router/graphs/contributors)

##### Made with [contributors-img](https://contrib.rocks).

-----------------
# License
#### MIT © wisehackermonkey
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
```bash
by oran collins
github.com/wisehackermonkey
oranbusiness@gmail.com
20210423
```

















<!-- ---------------------------------- -->
<!-- FULL -->
<!-- ---------------------------------- -->

<!-- # website-router -->
<!-- ---- -->
<!-- 
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<img src="assets/NNNNNNNNNNNNN" width="400">
<h2 align="center">____________________</h2>
<h4 align="center">________________________</h4>
 -->

<!-- 

# Quick start
### __________________
##### __________________________
```bash
```

 -->


<!-- 

# Summary
### -  *[Quick start](#Quick-start)*
### -  *[Live Demo](#Live-demo)*
### -  *[Installation](#Installation)*
### -  *[Screenshots](#Screenshots)*
### -  *[License](#License)*
### -  *[Features](#Features)*
### -  *[For developers](#For-developers)*
### -  *[Todo](#TODO)*
### -  *[Related](#Related)*
### -  *[Contributors](#Contributors)*
 -->



<!-- ----------------- -->
<!-- <img src="assets/KKKKKKKKKKK" width="400"> -->
<!-- # [Live Demo](https://www._____________.com) -->





<!-- 
# Installation
### 
```bash
``` 
-->




<!-- 

-----------------
# Screenshots
- <img src="assets/_____________" width="400"> 
- 
-->



<!-- 

# Features
- [x] ______
- [ ] ______

-->


<!-- 
-----------------
# For developers
### 
```bash
```
 -->





<!-- -----------------
# TODO
- [x] ___________
- [ ] ___________ 
-->

<!-- 
-----------------
# Built with
- #### ________________
-->





<!-- -----------------
# Related 
### [_________](https://www.____________.com)
 -->





<!-- 
-----------------
# Contributors

[![](https://contrib.rocks/image?repo=wisehackermonkey/website-router)](https://github.com/wisehackermonkey/website-router/graphs/contributors)

##### Made with [contributors-img](https://contrib.rocks).

-----------------
# License
#### MIT © wisehackermonkey
[![MIT](https://img.shields.io/github/license/wisehackermonkey/website-router.svg)](https://github.com/wisehackermonkey/website-router/blob/master/LICENSE)
-->

<!-- 
```bash
by oran collins
github.com/wisehackermonkey
oranbusiness@gmail.com
______________________
``` 
-->

<!-- ---------------------------------- -->
<!-- EXTRAS -->
<!-- ----------------------------------- -->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<!-- 
[![Javascript](https://img.shields.io/badge/Javascript-Enabled-lightgreen.svg)](https://shields.io/) 
[![forthebadge made-with-python](https://forthebadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
![Python](https://img.shields.io/badge/Python-Enabled-<COLOR>.svg)
![P5.js](https://img.shields.io/badge/P5.js-Enabled-pink.svg)
[![Generic badge](https://img.shields.io/badge/<SUBJECT>-<STATUS>-<COLOR>.svg)](https://shields.io/)
[![GitHub release](https://img.shields.io/github/release/wisehackermonkey/website-router.svg)](https://GitHub.com/wisehackermonkey/website-router/releases/)
[![GitHub tag](https://img.shields.io/github/tag/wisehackermonkey/website-router.svg)](https://GitHub.com/wisehackermonkey/website-router/tags/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/wisehackermonkey/website-router.svg)](https://GitHub.com/wisehackermonkey/website-router/pull/)
[![Website perso.crans.org](https://img.shields.io/website-up-down-green-red/http/www.orancollins.com.svg)](http://www.orancollins.com/) 
    -->

<!-- 
# https://yuml.me/diagram/plain/activity/draw
### (start)->[AAAAAAAA]<aaaaa->(BBBBBB)->(end) 

# Diagram
## 
```bash
```
 -->

<!-- 

# List
- 
- 
- 

# Table
| XXX | YYYY |
|----- |-----|
| ___s | ____| 

| XXX  | YYYY |
|:-----|:-----:|
| ___s | ____| 


# Toggle List (NO FORMATTING)
<details><summary>AAAAAAAA</summary>
<details><summary>Hidden A</summary>
</details>
</details>

<details><summary>BBBBBBBBB</summary>
<details><summary>Hidden B</summary>
</details>
</details>

<details><summary>CCCCCCCCC</summary>
</details>



# Toggle list with formatting
<details><summary>Level 1</summary></details>

<details><summary>&emsp;BBBBBBBBB</summary></details>
<details><summary>&emsp;&emsp;CCCCCCCCC</summary></details>
<details><summary>&emsp;&emsp;&emsp;DDDDDDDDD</summary></details>


# Toggle list Nested
<details><summary>Level 1</summary>

<details><summary>&emsp;BBBBBBBBB</summary>
<details><summary>&emsp;&emsp;CCCCCCCCC</summary>
<details><summary>&emsp;&emsp;&emsp;DDDDDDDDD</summary>

</details></details></details></details></details></details></details></details></details></details></details></details></details></details></details></details></details></details>

# Keyboard Commnand
### <kbd>Command/ctrl + R</kbd> 

# Installation
### 
```bash
cd ~
git clone https://github.com/wisehackermonkey/website-router.git
cd website-router
pip install -r requirements.txt
npm install
```

# Docker
### Build
```bash
cd ~
git clone https://github.com/wisehackermonkey/website-router.git
cd website-router
docker build -t wisehackermonkey/website-router:latest .  
```
### Run
```bash
docker run -it --rm --name wisehackermonkey/website-router:latest  
```
### Docker-compose
```bash
docker-compose build
docker-compose up 
```



# Publish Docker Image
```bash
docker build -t wisehackermonkey/website-router:latest .
docker login
docker push wisehackermonkey/website-router:latest
```

 -->