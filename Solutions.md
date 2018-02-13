## Group Members
- Student 1:Yifan Xu(1002288366)
- Student 2:Fenglun Wu(1002596684)
- Student 3:Qiangyu Zheng(1002144128)
- Student 4:Luyao Yang(1002087500)

## Project Description:
The website we built for this assignment is a site that uses the 
information provided by Toronto Public Transit to be able to generate 
helpful information.

Note that during our final days of writing this website, one unfortunate
thing that had happened was our API provider <myttc.ca> went down. As a result,
we were coerced to give up the function of planning trips and showing live
transit information.

As an essential function of website, we developed our user authentification
system where user can create accounts. Users are not allowed to access any
traffic info without having an account. However, it is allowed that a external
administrator to get, delete and post messages to the visitor message board 
from outside without logging in. Other users who are logged in can view the 
new messages.

Like most traffic websites, we have pinned the stations of subway on the
google map so users can know the location of the subway stations. One notable
feature is that users can create live feedback that are logged into our databse
about each station with date and time information where every other user can
see. Nevertheless, these feedback can only be managed by its owner, the
publisher. For each selected station, only the three most recent feedback on
that particular station will be show.

How to use our website:
You can use the heroku link: https://sunshine-boys.herokuapp.com/
or run node app.js and localhost:4000.
After register and login to our main page, you can choose the station on the 
right hand side, and write some feedback to this station on the bottom right.
You can view and delete your own feedbacks after click on the top right 
feedback button. Also, you can view other user's feedback by clicking on their name.

Thanks for using Sunshineboys Website!