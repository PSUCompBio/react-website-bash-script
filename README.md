# react-website-bash-script
 Bash script for creating and deploying react.js website on AWS instance
 - Before executing the script . Update the correct value of User executing the script in init_script.sh & deploy_script.sh ( Variable $UNAMEX ). 
 - Please add entries given below in /etc/hosts
```
127.0.0.1       www.digitalbraininjury.com
```
# IMPORTANT STEPS TO EXECUTE SCRIPT
 - Execute init_script
 - Then update the file config/configuration_keys.json with proper credentials and values. Use sudo to update it
 - Execute the deploy_script
 - Access the site on http://www.digitalbraininjury.com/ 

