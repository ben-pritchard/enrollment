#Description

This is an app written with Ruby, Rails, and Javascript that manages a database of enrollments. Through this app you can enroll, screen, unenroll, and edit subject enrollment information. You can also see the enrollment history of the subject as well as the current enrollment.

Additional features I added include a search feature that allows you to filter your list of enrollments based off of certain attributes. Integration tests are also included.

#Setup Instructions

Once you have your Ruby and Rails environments set up (which you can find details for here: http://guides.rubyonrails.org/getting_started.html) and your MySQL server running (which you can find details for here: https://dev.mysql.com/doc/refman/5.5/en/windows-server-first-start.html), then:

1. Run `rake db:create`
2. Run `rake db:seed` (without the "migrate" folder in the project)
3. Run `rake db:migrate`
4. Run `rails s` in your console
5. Go to "localhost:3000" in your browser

#Author

Ben Pritchard

ben.s.pritchard@gmail.com