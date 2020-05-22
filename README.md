# Udacity Udagram Project

![udagram for udacity](https://globalint.info/wp-content/uploads/udagram2020.png)

## Deploy a High-Availability Web App using CloudFormation

### CREATE
```
./create.sh Udagram-app complete.yml complete.json
```
### UPDATE
```
./update.sh Udagram-app complete.yml complete.json
```
### DESTROY
```
./destroy.sh Udagram-app
```

## The Basics

### Parameters

The more the better, but an exaggerated number of parameters can be messy ( say, 10 or more ). 1 or 0 is definitely lacking.

### Resources

This is the mandatory section of the script, we are looking for a LoadBalancer, Launch Configuration, AutoScaling group a health check, security groups and a Listener and Target Group.

### Outputs

This is optional, but it would be nice to have a URL here with the Load Balancer DNS Name and “http” in front of it .

### Working Test

If the student provides a URL to verify his work is running properly, it will be a page that says “it works! Udagram, Udacity”

### Demo video included

