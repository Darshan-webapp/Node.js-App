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

<img width="1224" height="1061" alt="Image" src="https://github.com/user-attachments/assets/bce986f4-47b1-4329-923b-b3933fecc26d" />

<img width="954" height="733" alt="Image" src="https://github.com/user-attachments/assets/13104fef-2bbf-4735-931f-b5e743f8abc6" />

<img width="1898" height="965" alt="Image" src="https://github.com/user-attachments/assets/1e529c36-8776-41e6-8209-6941541cdd73" />

<img width="1370" height="473" alt="Image" src="https://github.com/user-attachments/assets/566f42f3-e15e-45f7-b37b-9c7e61309c49" />

<img width="1177" height="660" alt="Image" src="https://github.com/user-attachments/assets/bc887f0e-7575-43da-ab02-3f95baf6af1a" />

<img width="1289" height="966" alt="Image" src="https://github.com/user-attachments/assets/1ba19129-4eae-4f62-bd40-b69fb0c83001" />

<img width="1911" height="915" alt="Image" src="https://github.com/user-attachments/assets/ffc651a7-85d0-40bc-b636-21eab52f298f" />

<img width="1886" height="776" alt="Image" src="https://github.com/user-attachments/assets/7486d7e9-b78f-42a7-8573-8606ad90650f" />

<img width="1226" height="849" alt="Image" src="https://github.com/user-attachments/assets/7365bddc-1122-4ab2-8fd6-d5fdb9b3b0c1" />
