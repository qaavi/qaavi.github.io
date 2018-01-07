---
layout: post
title: "Adding DISQUS to Jekyll"
author: Abdul Qavi
date: 2017-12-31 09:30:00 +0500
permalink: 2017/12/31/adding_disqus_to_jekyll/
comments: true
categories: jekyll update
tags: jekyll 3.6.2 disqus _config.yml minima blog github-pages github
description: This post is about adding DISQUS to Jekyll v.3.6.2
---
 
I recently setup a [Jekyll] based blog, and was integrating DISQUS into it. Most of the
blogs on Internet, and even DISQUS documentation itself was not updated, so thought to 
write the steps so that others save time.

I'm using latest version as of today - **Jekyll 3.6.2**

1. Create [Disqus] account. Then create a new site with your unique site name.

![useful image]({{ site.url }}/assets/images/1.png){:class="img-responsive" height="50%" width="50%"}

2. Then select the platform **Jekyll**
 
![useful image]({{ site.url }}/assets/images/2.png){:class="img-responsive" height="50%" width="50%"}

3. Note down the first step below. You just need to add **comments=true** in your posts' frontmatter. if you set 
**comments=false**, [DISQUS] comments box won't be added on that post.

![useful image]({{ site.url }}/assets/images/3.png){:class="img-responsive" height="50%" width="50%"}

4. Under "Website URL" in below image, use your WEBSITE name where you're going to add [DISQUS] - 
like if you're hosting your blog on [Github pages], you can use  `<yourUniqueURLName>.github.io`

![useful image]({{ site.url }}/assets/images/4.png){:class="img-responsive" height="50%" width="50%"}

Almost DONE with configuration.

5. One last step is to add `<yourUniqueURLName>` in your Jekyll project's `_config.yml` file, as show below.

![useful image]({{ site.url }}/assets/images/5.png){:class="img-responsive" height="50%" width="50%"}

**Done**. Now you can upload your site on [Github pages] or your own hosting provider, and you can see 
[Disqus] comments box on your posts. Only the posts where you've set **comments=true** in posts' frontmatter. 


[Jekyll]: https://jekyllrb.com/
[Disqus]:  https://disqus.com
[Github pages]: https://pages.github.com/
