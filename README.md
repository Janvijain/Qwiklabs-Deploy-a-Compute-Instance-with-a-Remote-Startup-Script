# Qwiklabs Deploy a Compute Instance with a Remote Startup Script
Step by Step guide to solve this challenge. Can refer my YouTube video for the same : https://youtu.be/RZIlVh9gIeM                                       

Navigation Menu -> Storage -> Create Bucket               
Name : [GCP Project Id]                     
Create                                                                              
Upload files : Select file you downloaded in starting = resources-install-web.sh                       
Edit permissions                             
Add entry                 
Entity : Public                       
Name  : allUsers                  
Access : Reader         

If you get error in adding entity                             
Go to Permssions Tab                  
Change access to Fine-Grained                      
 
Copy URL under Public Access                                 

Navigation Menu -> Compute Engine ->VM Instances->Click on lab monitor instance                  
Metadata                
Key=startup-script-url                       
Value=[Copied URL of Public access]                       
Firewall - Check HTTP                            
Save                      

Click on External IP                    
Add http://[External IP]                      
Check My Progress      

# Congratulations! you have successfully completed this challenge lab

LinkedIn                           
https://www.linkedin.com/in/janvi-shree-shrimal-9433401aa/                                             

Twitter                               
https://twitter.com/janvissm                            

Qwiklabs Profile                       
https://run.qwiklabs.com/public_profiles/5c709a0a-adf5-4f7d-9e9d-9f71d6c49c6e                             

Medium                               
https://janvissm.medium.com/                          
