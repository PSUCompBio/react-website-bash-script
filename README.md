# react-website-bash-script
 Bash script for creating and deploying react.js website on AWS instance
 - Allow TCP requests in Security Groups for EC2 while creating EC2 Instance.
 - Before executing the script . Update the correct value of User executing the script in init_script.sh & deploy_script.sh ( Variable $UNAMEX ).
 ```
# To start initialization & Dependencies installation:
$ sudo bash init_script

# Update the config file

# Deploy the Application
$ sudo bash deploy_script
```
 - Please add entries given below in /etc/hosts
```
127.0.0.1       nsfcareer.io
```
# IMPORTANT STEPS TO EXECUTE SCRIPT
Instructions to follow to set up the application on nsfcareer.io:

0. Point the nsfcareer.io domain to your EC2 Instance IP address.
And set the IP updation time to 1m (In Google Domains section).
1. clone the above repository
 - git clone https://github.com/PSUCompBio/react-website-bash-script.git
2. Run the init_script
```
$ sudo bash init_script
```
3. Input the domain name like given below without double quotes
     http://nsfcareer.io
4. Wait for the Initialization to complete
5. Update the configuration_keys.json file in <react-website-directory>/config/configuration_keys.json
6. Run the deploy_script
```
$ sudo bash deploy_script
```
7. Input the domain name like given below without double quotes
     http://nsfcareer.io
8. Your app is deployed visit http://nsfcareer.io
