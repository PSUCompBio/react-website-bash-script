# react-website-bash-script
 Bash script for creating and deploying react.js website on AWS instance
 - Allow TCP requests in Security Groups for EC2 while creating EC2 Instance.
 - Before executing the script . Update the correct value of User executing the script in init_script.sh & deploy_script.sh ( Variable $UNAMEX ). 
 - Please add entries given below in /etc/hosts
```
127.0.0.1       nsfcareer.io
```
# IMPORTANT STEPS TO EXECUTE SCRIPT
 - Execute init_script
 - Enter domain name when prompt
 - Then update the file in repository nsfcareer-react-website -> config/configuration_keys.json with proper credentials and values. Use sudo to update it
 - Execute the deploy_script
 - Access the site on http://nsfcareer.io/ OR http://DOMAINYOUENTERED/ 

