--- 
title: Ruby on Rails Tutorial for Rails 4.0 (beta)
layout: post
---

Bleeding-edge stuff, you may get cut

For example, as of this writing Spork doesn't work with Rails&nbsp;4. To work around this, the Gemfile in the book pulls directly from a fork I made of a repository that fixes the issue (and whose pull request hasn't yet been accpets). Another example, needed to work around changes in Capybara, is to pull the XPath and Capybara libraries directly from the latest master branches on GitHub, which introduces a significant risk of instabality. Finally, Rails&nbsp;4 doesn't yet work on Heroku, so all the deployment examples currently fail. 

Once the situation has stabilized a bit, I plan to make a short supplementary screencast highlighting the relevant changes. The truth is that there aren't many: if you have a solid grasp of Rails&nbsp;3.2 (as covered in the Rails 3.2 edition of the Rails Tutorial) then learning the relevant changes for Rails 4 shouldn't take more than an afternoon. 

At some point I plan to release a complete revision with a new screencast series. That will involve some more extensive changes, including the incorporation of the new feature spec syntax supported by the latest version of RSpec.