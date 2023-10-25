# Worlds-of-Choco-Boutique
I have create a dummy website of World of Choco Boutique
-----------------------------------------------------------------------------------------------
Aim: To deploy a website on Azure, establish a custom URL via DNS. Additionally, setting up a web alert rule, and employ access restrictions to prevent malicious users from accessing the website.
-----------------------------------------------------------
Youtube Video Link:
https://youtu.be/3hUzs8cpfNs?si=iVteVhklNn5lXoC_
-------------------------------------------------------------------------------------------------------------------------------------------------
World of Choco Boutique website link:
https://world.of.choco.boutique.redbusmagic.online/
------------------------------------------------------------------------------------------------------------------------------------------------
**Architecture**

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/b0c645be-157d-4dbe-8f75-aabf337cf1d4)


**Explanation of a diagram:**

Here we have created a V-Net in Central India with ip address 10.0.0.0/24. Inside that we have subnet1 with ip address 10.0.0.0/16. And inside the subnet1 there is a VM1 and web app.

In web app we are going to create DNS alert and access restriction.

**Now let us look how to deploy a website.**

Create a web app and go to the deployment center.

Connect the VM and install the FileZilla as well as install the website of your choice.

Form the web app give the FTPS credentials to the FileZilla and connect.

Copy the URL of where babe on the Google you will be able to view your website.

**NOTE:** 

You can view your website from any device.





![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/c37eb138-57ed-4f7d-8ce1-4c63a4c71867)


**Explanation of a diagram:**

Here we have created a V-Net in Central India with ip address 10.0.0.0/24. Inside that we have subnet1 with ip address 10.0.0.0/16. And inside the subnet1 there is a VM1 and web app.

In web app we are going to create DNS.

**Now let us look how to have a custom domain.**

Here we have taken the domain name as worldsofchocoboutique.redbusmagic.online.

We need to paste the CNAME and TXT in the hostinger. (Or else from wherever we have buy the domain)

We need to validate and wait for some time after validation we can add the domain name.

It will automatically get a binding or else you need to bind it.

Paste the new URL on the web app and you will be able to view the website.





![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/4cce314b-ae42-4c6a-93c8-f41521800e0e)


**Explanation of a diagram:**

Here we have created a V-Net in Central India with ip address 10.0.0.0/24. Inside that we have subnet1 with ip address 10.0.0.0/16. And inside the subnet1 there is a VM1 and web app.

In web app we are going to create alert and access restriction.

**Now let us look how to create alert rule.**

Here we have created an alert rule where we will be getting a notification on SMS and email on the registered phone number and the email ID.

The rule is that if a website is not working and user try to access the website a notification will be send on the given phone number and email. 

**Now let us look how to access restriction.**

Here we can restrict some VM and allow some VM to get the access. Also we can restrict some IP and allow other IP to get the access. 

If any of the devices is unable to view the website then we will be getting an notification.

**Now let us look how to restrict a VM1.**

Here I have restricted VM1 for this website but on the same time I can access it on my local machine or on my phone. 

Simultaneously I will also get a notification on email and SMS that someone is unable to view the website.

Suppose now you want to remove the restriction from the VM1.

Then you need to change the priority to 999 because the priority which was set to 1000 was to restrict the VM1.

After setting the priority will be able to view the website.

**NOTE:** 
Higher the priority lesser the number.





Create a VM

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/b0790a5d-6115-4437-9e34-732adf8bca2c)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/5c838212-3e50-4692-ad9e-4f324f82a192)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/4180c84d-d000-472c-bf81-cbca2ae9011f)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/f4f31353-a175-4498-90b4-c389f6e633e2)

Connect VM 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/aa1a005d-199b-48de-9acc-3482c75da7f4)

Download FileZilla

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/7716e89a-fa22-43e0-8386-d437e40826e7)

Install FileZilla

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/9b82d0ec-886a-4f26-b69e-b252e1287d79)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/bea84a51-889b-48a5-9f11-d9b041eb4a0e)

Create a Web App

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/bc81b237-d91a-463c-83ce-34c7a08b37f6)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/a3be2b10-b352-48b3-84a4-6345fda2e4d5)

FTPS Credentials 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/9184712a-0cb9-414d-8780-e696e64edd27)

FTPS Credentials in FileZilla

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/e28bf8d9-72bd-4d08-8ca7-2446a492ee6f)

Transfer the file

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/92513d36-c866-45bd-84a3-0b382da01e67)

Website view in VM1

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/74a820ac-4cda-4bcc-a02a-6325a379d800)

Website view in local machine 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/bad4fc00-b14e-45ee-9654-09fb1d22014b)

Working Website

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/d2d80ddf-5bf7-4183-ac3a-174edacbaab8)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/5fd9f3ef-fe37-43a5-bd74-94c077de70e3)

Create a custom domain  

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/50cbfa19-6442-45b7-b28d-cca63f211164)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/272e9a18-372f-4112-9bbd-9823c2d64f8f)

Added it in Hostinger 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/1d24b5ca-e9d2-41fa-a16e-c4a2418462b2)

Validate the domain & Add 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/5b83dd88-6271-45df-9475-fc5e91c004ff)

Domain with SSL 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/2f22e678-b151-4c37-9199-cbe0b6aa0a30)

Viewing website with our own domain 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/2fa0617e-666c-4d51-a8a1-7c2775aaba2b)

Creating an alert rule for web App

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/12e1e347-7a12-4b2d-afb2-481921dd843e)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/f1ad9cb2-aa49-4ad8-a922-f68fec8ca768)

Identify the rule 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/b999f356-09c1-42ff-9735-3fbdfb281fe9)

Create an action group 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/f5afbb40-f1ec-48e3-93ad-385537b43474)

Giving email & phone number for notifications.

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/97ccd53b-11d7-465d-a7eb-7bc367b7cc0c)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/1a03d939-7c16-41e9-adda-8f2329391fdc)

Registered phone number 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/220f3e29-3d72-4912-9e00-a5e24bd6fcb9)

Registered email 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/114ce059-47ce-4ab2-ac0b-3383c425f85f)

Create an alert rule for choco bites 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/3762c920-ac8e-419d-807d-87d38b82bde1)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/28c46d0f-7ee9-4747-8485-4e46c4940b4e)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/1307fcfc-8a42-487c-93fb-7ec9f3be1b2c)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/8a2659b5-ae1c-496a-9b1a-88df46ffd7cd)

Access Denied

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/a4408ed1-e818-41c9-b7bd-bd59f7690529)

Email Received for error

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/4b7b1353-32b2-4994-97fc-4a8b87444e38)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/8828e768-9e55-4a7c-9757-1538dae386a9)

Email Received for error resolved

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/923ad59e-aa04-463c-b457-36d8be593ca9)

We can view website now

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/a995eeab-e584-4bdf-a431-3b8b4ec7cce0)

Create an alert rule for worldofchocoboutique 

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/f6f6e2dd-ee0c-43d7-9797-93868de3e107)
![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/0b16dd79-579d-41c0-bc90-0278a668033d)

Access Denied

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/a66f8d9e-7dad-403f-9894-25485fb7cc49)

Email Received for error

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/07734524-7285-430a-924f-a5d1e0623740)

We can view website now

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/cf5b2fbb-bd9e-4b79-9844-c92b3c3442ef)

Email Received for error resolved

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/29490401-eced-4b05-8e42-df8ead62d1b7)

Error Solved

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/d9193118-c6a4-49e1-a844-f020e41cef39)

Access restriction ON

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/5624e50d-3321-4b5d-b41a-e39b5c9d87ad)

Add Rule to deny access to VM1

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/79397031-73df-4849-86e4-3abca8d92a37)

Access Denied in VM1

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/d3787fef-45c5-4aa3-9706-73a32c755521)

But able to view in Local Machine

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/44c4fdcb-1442-4fdd-b2f4-0c7a5e88e5b9)

Add Rule to allow access to VM1

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/62121974-fdaf-4070-8851-5a4dd3bc2118)

Access granted to VM1

![image](https://github.com/Shahira-Ansari/Worlds-of-Choco-Boutique/assets/144965488/d1a0f47e-a342-4ef9-b65e-46249a3bf3a0)
















