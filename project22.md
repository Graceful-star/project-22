# DOCUMENTATION OF PROJECT 22

1. I ensured my aws credentials was well configured, then I created an aws cluster

      ![Projec22](images/image1.PNG)

2. I created a POD yaml manifest on my master nodes and I applied it

    ![Projec22](images/image2.PNG)


3. I got an output of the pods running in the cluster, Then I examined the output thoroughly
     
     ![Projec22](images/image3.PNG)

     ![Projec22](images/image4.PNG)

4. I checked the POD's ip address

      ![Projec22](images/image5.PNG)

5. I created a SERVICE yaml manifest file to access the pods and I applied the manifest

![Projec22](images/image5.PNG)
![Projec22](images/image6.PNG)     

6. I checked the created service, then I port-forward the service
    
    ![Projec22](images/image7.PNG)
    ![Projec22](images/image8.PNG)

7. I updated the POD manifest again, applied it, ran the port-forward command and I was able to access it from my browser

     ![Projec22](images/image9.PNG)
     ![Projec22](images/image10.PNG)
     ![Projec22](images/image11.PNG)
     ![Projec22](images/image12.PNG)
     ![Projec22](images/image13.PNG)

8. I created a rs.yaml manifest file for a replica set and I applied it
     
     ![Projec22](images/image14.PNG)

9. I checked the running pods and I explored the ReplicaSets

    ![Projec22](images/image15.PNG)
    ![Projec22](images/image16.PNG)
    ![Projec22](images/image17.PNG)

10. I scaled my replicaSets up and down
    
    ![Projec22](images/image18.PNG)

11. I updated my Service manifest file to add LoadBalancer then I applied it

    ![Projec22](images/image19.PNG)

12. I checked the service that was created

    ![Projec22](images/image20.PNG)
    

13. Then I accessed it on my website using the LoadBalancer's ARN
       ![Projec22](images/image21.PNG)


14. I deleted the RS
     
     ![Projec22](images/image23.PNG)

15. I created a deployment manifest file and applied it
    
    ![Projec22](images/image24.PNG)

16. I checked the deployments and I checked thhe ReplicaSets too

    ![Projec22](images/image25.PNG)  
    ![Projec22](images/image26.PNG)

17. I checked the pods too
    
    ![Projec22](images/image27.PNG)

18. I exec into one of the running containers to run Linux commands

    ![Projec22](images/image28.PNG)

19. I checked the files in the nginx directory 
      
      ![Projec22](images/image29.PNG)

20. I scaled the pods down to one 

    ![Projec22](images/image30.PNG)

21. I Exec into the only running pod and I installed vim editor
    
    ![Projec22](images/image31.PNG)

22. I updated the content of index.html file
    
    ![Projec22](images/image32.PNG)

23. Then I checked the browser
     
     ![Projec22](images/image33.PNG)

24. I deleted the POD and refreshed the webpage

    ![Projec22](images/image34.PNG)
    ![Projec22](images/image35.PNG)