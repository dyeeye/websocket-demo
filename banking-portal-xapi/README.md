# WebSocket connector usage

The application **banking-portal-xapi** shows the usage of WebSocket connector. More you can find at my [article](http://ambassadorpatryk.com/blog) about it.


## Configuration
In orther to test it you need to provide AmazonSQS **accessKey** and **secretKey** to application.yaml file. 

## Test
This application should be run together with [banking-forex-sapi]() and [banking-papi](). 
After you run the application enter following [url](http://localhost:8081/rates) in the web browser and open the Console. You should see that the application has subscribe itself two time.

rates:{
  "status": "subscribed"
}