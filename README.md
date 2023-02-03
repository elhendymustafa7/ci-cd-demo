# CI-CD Project
- compile a code from GitHub , Analyse the test cases present in the GitHub repository through building a Jenkins Pipeline.
- pull a Docker Image 
- build a Docker image and then set up Jenkins to build and publish the image automatically, whenever you commit changes to your code repository.
## compile and build
### free style job jenkins to compile
![Screenshot from 2023-02-03 18-18-12](https://user-images.githubusercontent.com/58703269/216654455-ece9dcf3-4e44-4246-a139-02b5b54f6383.png)
### build job 
![Screenshot from 2023-02-03 18-26-12](https://user-images.githubusercontent.com/58703269/216655172-b1273486-7dc2-4d43-83d9-0142c1f4c6c6.png)
## review
### free style job jenkins to review
![image](https://user-images.githubusercontent.com/58703269/216656803-bb353283-fc2a-4c98-aa48-75cd2d603fb0.png)

![image](https://user-images.githubusercontent.com/58703269/216657746-1b27452f-8f85-491c-bc56-c99d23072762.png)
### build job
![image](https://user-images.githubusercontent.com/58703269/216658029-5413f26b-9439-4828-affb-900f9282507c.png)

## testing
### free style job jenkins to test
![image](https://user-images.githubusercontent.com/58703269/216656803-bb353283-fc2a-4c98-aa48-75cd2d603fb0.png)

![image](https://user-images.githubusercontent.com/58703269/216659262-3e99a49a-c7b3-4dcd-8c8a-1ec3860213a6.png)
### build job
![image](https://user-images.githubusercontent.com/58703269/216659599-1293e3a0-09ed-437c-b4af-74747ec0c006.png)

![image](https://user-images.githubusercontent.com/58703269/216659811-6fb1be06-8785-4ec3-807d-a710f4231081.png)

## pipeline
![image](https://user-images.githubusercontent.com/58703269/216662007-5bd42bc6-3ac3-480e-8ae3-1e2cdd9689c3.png)

![image](https://user-images.githubusercontent.com/58703269/216662512-840b7cdf-9733-44e6-8521-de6893f86366.png)

![image](https://user-images.githubusercontent.com/58703269/216663043-0561e345-ec02-41e5-965c-5f8d62da4c72.png)

![image](https://user-images.githubusercontent.com/58703269/216663585-43385bbd-632d-4711-b324-73fe7034b3be.png)

![image](https://user-images.githubusercontent.com/58703269/216664674-12385408-9c0e-4e47-8bbb-788589d1c91f.png)

## build docker-compose
![image](https://user-images.githubusercontent.com/58703269/216678034-958749cd-9e1e-4ce9-8409-170ea57c6487.png)
```bash
docker-compose -f docker-compose.yml up -d
```

## pipeline for build and publish the image automatically

### pipeline job 
![image](https://user-images.githubusercontent.com/58703269/216688124-a4f51f9b-8a96-4861-b0d5-17bfeee1c4b6.png)

![image](https://user-images.githubusercontent.com/58703269/216688478-38fc3a50-8459-4121-84cb-1be4f6fb9029.png)

![image](https://user-images.githubusercontent.com/58703269/216688559-3209c99c-8ed6-4a98-a65b-f8a42a3e2ec6.png)

