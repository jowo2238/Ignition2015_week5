# Ignition2015_week5
Diving deeper in the MVC aspects of Rails

# Week 5: Rails MVC

#### Required 
1. Read the [Odin Project Routing Guide](http://www.theodinproject.com/ruby-on-rails/routing) and use it to <strong>answer the following questions</strong>
  1. **What is the "Root" route?**  
   The Router is basically just a matching service and matches the URL with the appropriate controller action to run. 
  **1. What are the seven RESTful routes for a resource?**  
  get "/posts" => "posts#index"
  get "/posts/:id" => "posts#show"
  get "/posts/new" => "posts#new"
  post "/posts" => "posts#create"  # usually a submitted form
  get "/posts/:id/edit" => "posts#edit"
  put "/posts/:id" => "posts#update" # usually a submitted form
  delete "/posts/:id" => "posts#destroy"  
  **1. Which RESTful routes share the same URL but use different verbs?**  
 1 (posts#index) and 5 (posts#edit) refer to the same url but use different html  
  **1. How do you specify an ID or other variable in a route?**    
 Rails gives you a helper mothod that lets you create links (link_too) inwhich you need to supply text and a related URL  
  **1. How can you easily write all seven RESTful routes in Rails?**  
by typing  -- 
...
resouces :posts
...  
  **1. What is the Rails helper method that creates the HTML for links?**  
link_to  
**1. Read the [Odin Project Controller Guide](http://www.theodinproject.com/ruby-on-rails/controllers)**  
1. Read the [Odin Project Views Guide](http://www.theodinproject.com/ruby-on-rails/views) and use it to <strong>answer the following questions</strong>
  1. What is a layout?
  1. What's the difference between a "view template" and a "layout"?
  1. What is a "Preprocessor"?
  1. Why are preprocessors useful?
  1. How do you make sure a preprocessor runs on your file?
  1. What's the outputted filetype of a preprocessed *.html.erb file? What about a *.css.scss file?
  1. What is the difference between the <%= and <% tags?
  1. What is a view partial?
  1. How do you insert a partial into your view?
  1. How can you tell that a view file is a partial?
  1. How do you pass a local variable to a partial?
  1. What's the magical Rails shortcut for rendering a User? A bunch of Users?
  1. What are asset tags and why are they used?
1. (By Monday 3/9) By yourself, complete the [Odin Project: Basic Routes, Views and Controllers](http://www.theodinproject.com/ruby-on-rails/basic-routes-views-and-controllers)
  1. Skip step 1 of the Application Skeleton section.  As we did last week, you will:
    1. Create a new Rails workspace on C9
    1. Add `/.c9` to your `.gitignore` file
    1. Setup git and commit the project:
      1. `git init`
      2. `git add .`
      3. `git commit -m 'initial commit'`
    1. Create a new repo on GitHub without a `README` or `.gitignore`
    1. Add your remote and push to github (replace the `<username>` and `<repo>` with your username and repo name)
      1. `git remote add origin https://github.com/<username>/<repo>.git`
      2. `git push -u origin master`
1. (By Thursday 3/12) As a group, complete the Rails tutorial [Chapter 5](https://www.railstutorial.org/book/filling_in_the_layout#top). Make sure to trade off coding, one person should not write everything.  
  1. Pick up where you left on your week 4 assignment with your new partner.  One person should be new to the codebase, one should have been working on it the previous week.

#### Optional
- Read the [Rails Guide on Routing](http://guides.rubyonrails.org/routing.html)
- Read the [Rails Guide on Controllers](http://guides.rubyonrails.org/action_controller_overview.html)
- Read the [Rails Guide on Layouts](http://guides.rubyonrails.org/layouts_and_rendering.html)
- Read the [Odin Project Guide on Asset Pipelines](http://www.theodinproject.com/ruby-on-rails/the-asset-pipeline)
