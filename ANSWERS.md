# Q0: Why is this error being thrown?

Haven't created anything for 'Pokemon' reference to Rails throws an undefined error.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *

@pokemin retreives a random Pokemon object. None of the Pokemon have trainers.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

The button 'captures' the Pokemon by calling the capture method in the Pokemon Controller. Then, we're redirected back to the homepage.

# Question 3: What would you name your own Pokemon?

Guy

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

There is a path passed to redirect_to.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

This sends the error to an alert box by retreiving the error message.

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
