
<h1>
    Programming Club Website
</h1>



 A simple non-static and responsive website of Programming Club which uses Django as back-end framework. The admin has the access to change the content of the website i.e. to upload resources or events or add or delete any data.  



<h3> Configurations </h3>


To install this repository the steps are same as any other Django project

+ Clone the repository

```
git clone https://github.com/dhatrikapuriya/PClub-website
```



+ Install the required packages. Using a virtual environment is recommended.

```
pip install -r requirements.txt
```



+ To run the project write the following in command prompt

```
python manage.py runserver
```





 <h3> Features and Functionalities </h3>



The admin can access the content of the website and can add or delete the contents in the following pages:

1. **Events Page:** This page shows the upcoming and past events along with the poster (downloadable) and upcoming events are provided with the registration link. Here admin can add and remove events, description accordingly
2. **Resources Page:** This page consist of the all necessary material for referring a particular topic such as PDF, Videos, links. This page consists of *tags* (eg. Web Development) and under that there are multiple *sub tags* (eg. Django, Node JS) where all the material is added. The access to change content of this page is provided to admin.
3. **Announcements:** This is a part of homepage where the announcement section describes and provides the direct link of any *up-coming events* or any recent *resources* added.
4. **Team:** This is again a part of homepage where all the *Core Committee* members and *Executive Committee* members are displayed with their photo, designation and linked and git hub links (if any). The team members can be changed according to the circumstances.
5. **Contact Us:** Any user having a look to this website can ask query or give suggestion through Contact Us mail, where they have to to provide their Email, and write the subject and message.
6. **Gallery:** Any pictures related to any event can be added by the admin in this section and they all are displayed on homepage.
7. **Subscription:** By subscribing with your E-mail address you will get all the updates about *resources* and *events*. Also for the events you will get the link to add that in your **Google Calender**. This was achieved by using **Google Calender API**.



<h3> Screen Shots

</h3>

 + HomePage
 

![Home](https://user-images.githubusercontent.com/65729151/85868404-d78ea680-b7e7-11ea-8ac8-3eaf992f39a9.PNG)


 + Announcements: All the upcoming events and updated resources can be seen in Announcemnets:
 
 
 
 ![announcements](https://user-images.githubusercontent.com/65729151/85868610-263c4080-b7e8-11ea-97c0-52b7dbfa17cc.PNG)



 + Events: All the upcoming events (with resgistration link) and past events are showed here.
 
 
 
 ![events](https://user-images.githubusercontent.com/65729151/85868832-70bdbd00-b7e8-11ea-8e1e-f6b785c12f67.PNG)



 + Gallery: This will show all the photos of the club events and whatever added by admin
 
 
 
 ![gallery](https://user-images.githubusercontent.com/65729151/85868909-8cc15e80-b7e8-11ea-82f7-1024e5a1f398.PNG)




 + Resources: All the resources of tags and its subtags are visible and downloadable.
 
 

 ![resources2](https://user-images.githubusercontent.com/65729151/85869440-4d474200-b7e9-11ea-8b84-6d6236cc1b77.PNG)



![resources1](https://user-images.githubusercontent.com/65729151/85869030-c09c8400-b7e8-11ea-9961-f37d5ea43ada.PNG)



 + Contact Page: You can contact us by sending your query or suggestion in this section
 
 
 ![contact](https://user-images.githubusercontent.com/65729151/85869255-1113e180-b7e9-11ea-95f4-685bf9b082a0.PNG)



 + Teams: You can have a look at all the core and executive committee
 
 
 ![team](https://user-images.githubusercontent.com/65729151/85869372-343e9100-b7e9-11ea-946e-0643c39ac20f.PNG)

 
 
