# Made by HK
# CVE-2020-10238: Incorrect Access Control in com_templates
# Link
https://developer.joomla.org/security-centre/804-20200303-core-incorrect-access-control-in-com-templates.html
# My blog about this CVE
https://hocvahoc.me/2020/03/13/my-journey-to-find-out-joomlas-cvepart-1/
# PoC
# Run rce.py with your credentials and cccess link rce:

![image](https://user-images.githubusercontent.com/24661746/75947454-09939a00-5ed3-11ea-92dd-8136cf8edaba.png)

# Guide to use docker such as:
# #Step 1: 

# *docker pull hoangkien1020/joomla:hk*

# #Step 2:

# *docker run -d --rm -it -p 8080:80 hoangkien1020/joomla:hk*

# #Step 3: Access your domain/IP with port 8080:
![image](https://user-images.githubusercontent.com/24661746/75947931-9be86d80-5ed4-11ea-991d-f37309d4c41a.png)
