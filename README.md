# Node.js-App
TASK 1: Automate Code Deployment Using CI/CD Pipeline (GitHub Actions)

First i have created the repository on my Github and clone it into my local environment.

For that i have used this git commands to clone he repo git clone https://github.com/Darshan-webapp/Node.js-App.git

Then i created one node.js demo app

after that i have created the dockerfile in to the same node.js app fproject folder 

Now i have build the docker image locally using the dockerhub desktop.

once I successfully build the iamge i run the container using this command docker run -p 3000:3000 node.js-app(it will run this app at local 3000 port which i can access using this http://localhost:3000)

Then i pushed my latest code into my repository using this git commands listed below.
1 git status (to check the latest chnages)
2 git add . (this will add all the files at once)
3 git commit -m "commit message" (this will shows the commit message)
4 git push origin main (this will pushed the code into the repository)

now i have to craete github action workflow, so i have created the folder inside my project name .github/workflows 

and inside that i have to create main.yml file ( this code inside the main.yml will make sure to what,when and how automation runs on our repository)

after this i have added Dockerhub secret credential in github action.

now i have to push the code again to trigger the CI/CD pipline.

I have also shared some screeshots of my work.