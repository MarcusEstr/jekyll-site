# to create new website with Jekyll use the command: `jekyll new folder-name`
# underscore posts folder is where you will put your posts.
# to initialize on Github did the following:
#git init
#git status
#git commit -m "Initialization project"
#bundle lock --add-platform ruby
#bundle lock --add-platform x86_64-linux
#to spin up server, do: `bundle exce jekyll serve`
#install themes froms ites such as jekyllthemes.org, and themes have their own methods for installilng.
#some want you to fork the theme repository on github... thenw ould not use jekyll new command.
# you would use git clone instead.
#others let you install the theme as a Ruby Gem. Go to Gemfile file. Minima is default theme.
#Comment out with hashtag icon. THen put in your own theme.
#Then go to underscore congif.yml and change `theme:` to say the new theme, jekyll-athena for ex.
#to install the new gem, need to go to cmd and run `bundle` command.
#the gem jekyll-compose added in gemfile file allows easier way to create posts.
#use the command `bundle exec jekyll post "Post Name Here"` 
#for it to automatically create file in underscore posts folder!
# front matter is the properties for every post
#jekyllrb.com/docs/front-matter