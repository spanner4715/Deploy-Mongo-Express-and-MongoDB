# Deploy-Mongo-Express-and-MongoDB
MongoDB can only interact with internal service by Mongo-express 

    Environmental variables can be searched on "mongo-express" dockerhub
    
    
  


## Process
![image](https://user-images.githubusercontent.com/103509243/219922252-30f1e734-75f5-4d7f-adf8-2ad5a7251d9d.png)

## Steps
1. Create MongoDB confidential
2. Create MongoDB POD by configuring yaml file and apply it (Deployment & Service)  
3. Create Mongo-express POD
4. Create configMap to reference MongoDB (Contains url)


  
