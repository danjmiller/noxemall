---
layout: post
title: Getting Github Pages gem installed on my Mac
---

I have a Macbook Pro running MacOs Sierra 10.12.3 and when I set out to create this blog, I wanted to use Jekyll and Github Pages.
So, following this tutorial:

I set out to get my local Jekyll setup I came to this step:


```
gem install github-pages

```

And I was greeted by this nastygram:

```

sudo gem install github-pages
Password:
Fetching: jekyll-redirect-from-0.12.1.gem (100%)
Successfully installed jekyll-redirect-from-0.12.1
Fetching: jekyll-github-metadata-2.3.1.gem (100%)
Successfully installed jekyll-github-metadata-2.3.1
Building native extensions.  This could take a while...
ERROR:  Error installing github-pages:
	ERROR: Failed to build gem native extension.
    current directory: /Library/Ruby/Gems/2.0.0/gems/nokogiri-1.6.8.1/ext/nokogiri

````

So, I did some googling and found this:
