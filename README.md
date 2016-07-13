# Achieve fame and glory, expand your personal brand, and live your wildest dreams by building a free GitHub powered website!

_Based on [@barryclark's Jekyll Now](https://github.com/barryclark/jekyll-now) repository and awesome [article on Smashing Magazine](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/)._

You don't have your own website? 😱

![taylor swift saying 'pathetic'](http://cdn4.teen.com/wp-content/uploads/2014/02/week-in-review-taylor-swift-gifs-pretty-little-liars.gif)

Not to worry, let's get to work!

![silicon valley apple getting eaten by russ](http://i.giphy.com/xT0GqrBXjVVBJajQNG.gif)

## 1. Create a Github Account

### [github.com/join](github.com/join)

If a brand new account, make sure you verify your email with github.

## 2. Copy the [Jekyll Now](https://github.com/barryclark/jekyll-now) repo. 

In Github terms a copy is called a 'fork' so you need to fork the repo. Look for the 🍴 button in the upper right.

## 3. Rename the repo to your `<YOUR_USERNAME>.github.io`

Click on **Settings**. Follow the exact process from the following image if you are stuck:

![funny image?](https://media-mediatemple.netdna-ssl.com/wp-content/uploads/2014/07/step1.gif)

## 4. Edit a(ny) file

Github is taking our "raw" files and turning them into HTML for us. 
We need to edit a file so Github knows to rebuild our site.

The best one to start with involves the configuration of your new site - the name, description, etc.
Click on the `_config.yml` file then hit the 🖊 icon to edit the file in your browser.
`https://github.com/<USERNAME>/<USERNAME>.github.io/blob/master/_config.yml`

You can change anything you want, but the following are a good start:

![changes you might wish to make to your config](https://cloud.githubusercontent.com/assets/203683/16789111/e2c0595c-4867-11e6-9f93-783e919b22ed.png)

### Saving your changes

In git, "committing" the change means you are saving it. It's a good idea to include a helpful message to yourself about what you did.
I like to write **Why** I made the change in the subject line and more info on **What** or **How** I did it below.

![Screenshot of the UI when you are about to commit a change](https://cloud.githubusercontent.com/assets/203683/16789146/4acfdde2-4868-11e6-81ac-dbf3db1f6bbb.png)

## 5. Create a new post

We're almost done. We just need some sweet, sweet content!

### _What are these `.md` files?_
Posts (and most other files in our new repository) are written in Markdown, a lightweight text markup format (get it?). Hence the `.md` extension on these files. Our mostly plain text looking files will be turned into HTML that way.
[Github's guide to markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/) is a good resource.

### Let's create one.
Create a file in the `_posts` folder. It needs a specific name - `YYYY-MM-DD-<TITLE-OF-POST-GOES-HERE.md>`.
You can also start by editing the default **Hello World** post.

## 6. Check out your site at `https://<YOUR_USERNAME>.github.io`!

**Congratulations, you are awesome!**

![Well done, Jeremiah Johnson](http://i.giphy.com/12OTxgtyHG11QI.gif)

## Now what?

Write blog posts, post interesting links, share it with your friends and family so you can...

#### Achieve fame and glory

![Hitchcock hiding an award](http://i.giphy.com/j2mV6rFyM9dHG.gif)

#### Build your personal brand

![Betty white being awesome](https://toniclc.files.wordpress.com/2016/01/2013-09-24-gif9.gif?w=620)

#### Celebrate

![Aziz drinking wine](http://i.giphy.com/l3V0dUu8awcyNJqxO.gif)

## Seriously, where to go from here?

Excellent question.

### Want to know more about your options using Github?
* Explore [this document on different ways to setup Github pages ](https://help.github.com/articles/user-organization-and-project-pages/). For example, you can create an organization and host a site that way. Say you volunteer at a local food kitchen, you can create an organization in Github called **LocalFoodSharers** and host a site under their name (versus using your own username).
* Or, take a look at Github's info on [customizing Github pages](https://help.github.com/categories/customizing-github-pages/).

### Understanding what is going on under the hood and customizing your site

* If you want to tweak the look of your site, or what it can do, you'll want to learn more about Jekyll. Check out [Jekyll Casts](http://jekyll.tips/) - "Step by step tutorials and screencasts covering everything you need to know about Jekyll."
* Speaking of, you'll probably [want to start running Jekyll locally](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) so that you don't have to edit files directly using the Github web app.
* [This list of sites built with Jekyll](https://github.com/jekyll/jekyll/wiki/Sites) is great for looking at what is possible.

### What is git, anyway?
* You'll need to interact with Github using git, the version control system. [This course from CodeSchool covers the basics](https://www.codeschool.com/courses/try-git) in a fun fashion. Seriously, CodeSchool does a great job at breaking down information.

### I wanted `<AWESOME_DOMAIN_NAME>.com`, not this `*.github.io` thing?!??!
* This gets a little tricky but if you've gotten this far, you're going to crush it.
* If you need to buy a domain, Colorado's own [name.com](https://name.com) is a good one. So is [Hover](https://hover.com).

1. [Add a custom domain to your Github pages site](https://help.github.com/articles/adding-or-removing-a-custom-domain-for-your-github-pages-site/).
2. Follow this guide on [setting up an "apex" domains](https://help.github.com/articles/setting-up-an-apex-domain/). You'll need to interact with your domain provider as part of this. Some providers [have really good guides on how to do this](https://www.namecheap.com/support/knowledgebase/article.aspx/9645/2208/how-do-i-link-my-domain-to-github-pages), like that one from [namecheap.com](namecheap.com).
3. Be patient. It can take time for DNS settings to take hold around the world/Internet.

### I'm stuck. Help!?

* Just ask! [Post a question here](https://github.com/threecommas/yourownwebsite/issues) or shoot me an email. Ask your favorite developer friend for help or to find out why something works the way it does.
* Check [Meetup](meetup.com) for a local users group that may have covered Jekyll or may be hosting an event in the near future.

### So, this is just plain HTML? Isn't that boring?

* Yes! And fast. These sites are usually considered "static websites" which means their content only changes as fast as you can type or edit a `.md` file.
* This article on [why static website generators - like Jekyll - are the next big thing](https://www.smashingmagazine.com/2015/11/modern-static-website-generators-next-big-thing/) highlights the benefits of building your site this way.



