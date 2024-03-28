# Hackathon Website

To maintain this website, there's a couple things that you will need to install to either your local machine or your virtual development environment. You will also need to be a member of the UWW ISACA organization and have the necessary permissions to make changes in the repository. 

# Requirements

### Install [Ruby on Rails](https://www.ruby-lang.org/en/documentation/installation/)
For a quick rundown on what the Rails framework is, please watch [this video](https://www.youtube.com/watch?v=UYm0kfnRTJk). 

### Install [Jekyll](https://jekyllrb.com/docs/installation/)
We will be utilizing [Ruby Gems](https://medium.com/@morgannegagne/what-is-a-ruby-gem-1eec2684e68) to install Jekyll on top of Ruby.

### Install [Git](https://git-scm.com/downloads)
Git is a version control technology that allows us to track changes in code over time ([learn more](https://www.youtube.com/watch?v=hwP7WQkmECE)).

### Install [VSCode](https://code.visualstudio.com/)
VSCode is a lightweight text editor that can easily be transformed into an integrated development environment. 

# Getting Started

Once you have setup your developer environment, you should be able to run this command in your terminal: \
` git clone https://github.com/UWW-ISACA/hackathon.git `

If you have the correct version of Ruby & Jekyll installed, you should be able to run:\
` bundle install `

To generate a live mockup of the website, run:\
` bundle exec jekyll serve `

To see the live site, visit `localhost` in your web browser.

# Troubleshooting

### Ruby Errors

While Ruby installation is fairly straightforward, sometimes you run into versioning errors. This typically is a result of your computer not understanding which version of Ruby to use. For starters, try running `ruby -v` and note which version you have running. Anything below Ruby 3.0 isn't capable of running Jekyll.\
\
A great way to get rid of this issue is by using a version manager. While there are many version managers out there, probably the best one to use is chruby (change Ruby). 

### Gem Errors

If you experience Gem errors, check to see the version of Gem you are running. Anything below 2.0 will be incompatible with Jekyll.