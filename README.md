hello
=====

Drupal module to greet hello in different languages exactly like flickr ! , More than 100 languages available,
Please feel free to add more here 
[https://docs.google.com/document/d/167gYqAI1T4gGuGs90GtnmYY_MjUrgOZVYflqfKgY_Sg/edit?usp=sharing]


== Usage ==
============

Provide a greeting block. Go to "admin/structure/block" to eanble.

Block will look like this 
"Hello <i>User Name</i></br>
Now you know to greet people in <i>Language</i>"

If you want to alter the "User Name" And subtitle i.e "Now you know to greet people in". You can call this function with two arguments.

greet_hello($name,$subtitle);

Empty arguments will lead in default text i.e :

Hello user</br>



