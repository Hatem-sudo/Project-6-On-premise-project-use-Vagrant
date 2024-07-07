# Project-6-On-premise-project-use-Vagrant
## on premise project

![On project](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/fd661c7d-4060-4d58-a38e-2db411e69e1d)


#### Project Description
-. on premise project use vagrant to automate virtual box and upload webapp like linkedin or facebook 
-. An application that used to share posts and make commant like facebook application connected with database to save info
-. and you can see your profile picture and cover.
#### Tools :-
1. Windows.
2. Git Bash.
3. Virtual Box.
4. Vagrant.
5. Linux.
6. DataBase MariaDB
7. Cashing DB like Memcashe to handel the query
8. Message Broker Rabbit MQ
9. Web server Tomcat
10. Nginx 

#### Step 1 - Creat our Inviroment.
1. install Virtualbox.
2. Download Centos OS .
3. Download Vagrant.



#### Step 2 - Make automation with Vagrant file.

1.creat Vagrant file.
2.Creat 5 virtualmachine DB-MC-RMQ-APP-Web.
3.Edite all Memory and Ports Make sure to set Hostsname and make private network.
4. Make Vagrant file up.
 ![3e4c46d8-fca7-47a4-a8b9-818bf2a8e905](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/27a6d64a-7dc5-41d2-b176-93165019b0c7)

 ![41d11d0c-4b38-4f00-8f2a-bee42659c760](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/6490f468-13ce-4f05-87c7-9f3ab6e0644b)
  
    
#### Step 3 – Handeling the serveces.

1. Login with ssh port by GitBash.
2. username and password is vagrant.
3.Cheak Hostnames and IPS.


#### Step 4 - setup and install MYSQL.

1. Login to VM-DB and update OS Cheak Hostname and IP.
2. Install Mariadb package and starting enable Mariadb server.
3. Set Database username and password.

![51903b42-0ae9-4f0e-a84f-a4f9286d9a3e](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/c3287729-58f2-4508-be66-23b1a666097f)



#### Step 5 – setup and install MEMCASHE.

1. Login to VM-MC and update OS Cheak Hostname and IP.
2. set repository and install the depdensies.
3. Install and enable memcahe on port 11211 and starting firewall  

![dd62a63d-04a6-4319-93c7-3aec8dfa3ff8](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/da6dad0d-3ea7-4341-985d-09bac369da3f)

#### Step 6 - setup and install Rabbit-MQ.

1. Login to VM-RMQ and update OS Cheak Hostname and IP.
2. set EPEL repository and install the depdensies.
3. setup access to usertest and make it admin and starting firewall and open port 5672.

![83600589-67f7-4e65-a931-e25a822c74fe](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/1d368b8c-50dc-41f6-886b-3bf2581f3b91)

#### Step 7 - setup and install Tomcat.

1. Login to VM-App and update OS Cheak Hostname and IP.
2. Set repository and install the depdensies.
3. Download Tomcat package and change dir dir to /tmp and add user
4. Copy Tomcat home dir and creat Tomcat server file and enable firewall

![f56442b3-4aa8-4821-8d78-337201d76582](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/a6749319-76d4-4544-9a08-39cf0131e932)

#### Step 8 - Code Build.

1. Download source code from gitHub or any version controll.
2. deploy the artifact.

![54b1b2e4-d58a-4811-8cf0-7fb31da33a60](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/facfe5d1-05db-4f0a-8ff8-6b5e6dc52cd5)

#### Step 9 - setup and install Nginx

1. Login to VM-Web and update OS Cheak Hostname and IP.
2. Creat Nginx configration file and update contant
3. Delete old file and creat link to active website and resart Nginx.

![3e2d986c-986a-44ee-963f-ed5995a69793](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/e80a69d4-47c1-4c97-9440-8c7bab5022b8)

it's Done !!!
![17aff301-dce7-4ad1-87a2-796a6d8d375e](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/07afa950-810b-4173-8fd9-894b2b0e3762)

![be1abf22-5f2d-4fce-88f7-debafbc7a44a](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/7065cab5-b6d4-4d9a-80f7-f0f8558c10b5)

![2553539b-d518-4aaa-81c9-8105b23d99cc](https://github.com/Hatem-sudo/Project-6-On-premise-project-use-Vagrant/assets/113099054/0f24eba6-5a83-44e8-909e-40513414c908)

