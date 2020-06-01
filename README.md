# README
Exercises 1 (2.2.1)
1. (For readers who know CSS) Create a new user, then use your browser’s HTML inspector to determine the CSS id for the text “User was successfully created.” What happens when you refresh your browser?
    
    id=notice. Massage was been hiden
2. What happens if you try to create a user with a name but no email address?
    
    User was successfully created
3. What happens if you try create a user with an invalid email address, like “@example.com”?
    
    User was successfully created
4. Destroy each of the users created in the previous exercises. Does Rails display a message by default when a user is destroyed?
    
    Yes.User was successfully destroyed.
    
Exercises 2 (2.2.3)
1. By referring to Figure 2.11, write out the analogous steps for visiting the URL /users/1/edit.
    
	
2. Find the line in the scaffolding code that retrieves the user from the database in the previous exercise. Hint: It’s in a special location called set_-user.
	
	
3. What is the name of the view file for the user edit page?
    
    edit.html.erb
    
Exercises 3 (2.3.1)
1. (For readers who know CSS) Create a new micropost, then use your browser’s HTML inspector to determine the CSS id for the text “Micro-post was successfully created.” What happens when you refresh your browser?
    notice. Notice is empty
    
2. Try to create a micropost with empty content and no user id.
    
    Created without id and content.

3. Try to create a micropost with over 140 characters of content (say, the first paragraph from the Wikipedia article on Ruby).

   Micropost was successfully created.    
4. Destroy the microposts from the previous exercises.

    Micropost was successfully destroyed.

Exercises 4 (2.3.2)
1. Try to create a micropost with the same long content used in a previous exercise (Section 2.3.1). How has the behavior changed?

    I take's error 1. Content need <140
2. (For readers who know CSS) Use your browser’s HTML inspector to determine the CSS id of the error message produced by the previous exercise.
    
    id: error_explanation

Exercises 5 (2.3.3)
1. Edit the user show page to display the content of the user’s first micropost. (Use your technical sophistication (Box 1.2) to guess the syntax based on the other content in the file.) Confirm by visiting /users/1 that it worked.

   Done
2. The code in Listing 2.18 shows how to add a validation for the presence of micropost content in order to ensure that microposts can’t be blank. Verify that you get the behavior shown in Figure 2.17.

   True
3. Update Listing 2.19 by replacing FILL_IN with the appropriate code to validate the presence of name and email attributes in the User model (Figure 2.18).
   
   Done

Exercises 6 (2.3.4)
1. By examining the contents of the Application controller file, find the line that causes ApplicationController to inherit from Action-Controller::Base.

    Done.1
2. Is there an analogous file containing a line where ApplicationRecord inherits from ActiveRecord::Base? Hint: It would probably be a file called something like application_record.rb in the app/models directory.

    Done.