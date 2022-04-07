# django-api-and-react.js

Api rest frame work <br/>
mysql database <br/>
react.js <br/>
send email <br/>
Full authentication system <br/>
<br/>
# Note:
About the front end part, it's not good because i focs at Back End part.

# how to run 
install librarys from requirements file--> pip install -r requirements.txt <br/>
py manage.py runserver <br/>

Go to-->  127.0.0.1:8000/api/.....

# api urls
path('users/',views.get_users.as_view()),
path('users/<str:username>/',views.get_user.as_view()),
path('profiles/',views.get_profils.as_view()),
path('profiles/<int:pk>/',views.get_profile.as_view()),
path('comments/<int:pk>/',views.get_comments.as_view()),
path('comment/<int:pk>/',views.get_comment.as_view()),
path('movies/',views.get_movies.as_view()),
path('movies/<str:name>/',views.get_movie.as_view()),
path('signup/',views.Signup.as_view()),
path('logout/',views.Logout_view),
path('login/',views.Login_view.as_view()),
path('changePassword/',views.ChangePasswordView.as_view()),
path('likeDislike/<int:id>/',views.LikeDislikeView.as_view()),
path('commentLike/<int:id>/',views.CommentLikeView.as_view()),
path('sendMessage/',views.sendMessage),
path('resetPassword',views.resetPasswordRequest.as_view()),



