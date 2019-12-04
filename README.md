# README
Conor McCandless
<<<<<<< HEAD
Assignment 3:
added devise gem for authentication of the user. added a simple navbar through layouts/application.html.erb
I mostly followed this guide here for setting up devise https://guides.railsgirls.com/devise
I am impressed about how easy it is to implement a user login feature through a rails gem as this would traditionally be a more
difficult task to implement. The navbar was also easier than expected as the html code is applied through all of the views in
rails. 
Could add more to navbar and look of page in the future.
=======
<<<<<<< HEAD
Assignment 1:
command line:
rails new ...
rails generate scaffold Make name:string country:string
rails generate scaffold Car make:string model:string VIN:string country:string make:references
rails generate scaffold Part part:string
rails generate model CarsParts car:references model:references --force-plural
rails db:migrate
=======
Assignment 2:
added validations to each model. assumed that length for each should be less than 2
and value presence should be true.
>>>>>>> WDA2/master

added search bars to each view by creating a search function in each controller
and calling this seach function in the view index for each model.

<<<<<<< HEAD
form changes:
added drop down form for car creation that references makes
added check box selection form for car creation that references Parts

What I learned:
the differences between private and public key for creating relational databases (:make_id vs :make)
the differences between scaffold and model
the meaning behind has_and_belongs_to_many, .. edit_car_path
I also should have named the field in my part model part_name rather than part in order to make things a little less confusing!
=======
still working on testing and fixing odd bugs, (car create doesnt work, part destroy doesnt work)
>>>>>>> WDA2/master
>>>>>>> WDA2/master
