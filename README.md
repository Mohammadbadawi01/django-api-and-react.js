# django-api-and-react.js

Api rest frame work <br/>
mysql database <br/>
react.js <br/>
send email <br/>
Full authentication system <br/>
<br/>
# Note:
About the front end part, it's not good styling--> because i wasn't have UI design & I focs at Back End part.

# how to run 
install librarys from requirements file--> pip install -r requirements.txt <br/>
py manage.py runserver <br/>

Go to-->  127.0.0.1:8000/api/.....

# api urls
path('users/',views.get_users.as_view()), <br/>
path('users/<str:username>/',views.get_user.as_view()), <br/>
path('profiles/',views.get_profils.as_view()), <br/>
path('profiles/<int:pk>/',views.get_profile.as_view()), <br/>
path('comments/<int:pk>/',views.get_comments.as_view()), <br/>
path('comment/<int:pk>/',views.get_comment.as_view()), <br/>
path('movies/',views.get_movies.as_view()), <br/>
path('movies/<str:name>/',views.get_movie.as_view()), <br/>
path('signup/',views.Signup.as_view()), <br/>
path('logout/',views.Logout_view), <br/>
path('login/',views.Login_view.as_view()), <br/>
path('changePassword/',views.ChangePasswordView.as_view()), <br/>
path('likeDislike/<int:id>/',views.LikeDislikeView.as_view()), <br/>
path('commentLike/<int:id>/',views.CommentLikeView.as_view()), <br/>
path('sendMessage/',views.sendMessage), <br/>
path('resetPassword',views.resetPasswordRequest.as_view()), <br/>



