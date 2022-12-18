color:#4c94f1;project 11
#636c79; project-12 #10181d;

#7030cc project-13 #faeaeb #fbf0ee #9cb9b9 #d083df


#f5f2f0 project 14 #333333

#111111 #1e1e1e #e73f3e  project 15

#303342  project-2



 #!/bin/bash
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl status httpd
sudo systemctl enable httpd
sudo echo "<h1>  hello from $(hostname -f) </h1>" > /var/www/html/index.html

