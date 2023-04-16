# 50_days_Docker_project

## Capstone project
Introduction to Docker: Build Your Own Portfolio Site
an online non-credit project authorized by Coursera Project Network and offered through
Coursera

Pull git repo
``` 
git pull git@github.com:amna-rahman/50_days_Docker_project.git
```
For this poject we deployed the insect game. Write this in terminal
```
cd  insect-catch-game/

```
Pull nginx docker image
```
docker pull nginx 
```
run the following command
```
nerdctl run -d -p 8081:80 -v $(pwd):/usr/share/nginx/html nginx

```
![image](https://user-images.githubusercontent.com/109412864/232349746-288d7320-794e-4640-acf5-9b5b8067597e.png)

Deployed and working!

