---
layout: post
title:  "The Thing About Jekyll"
date:   2024-09-28 09:22:15 +0000
permalink: /posts-page/:slug/
---
There's a lot to consider when setting up Jekyll for GitHub Pages. First off, if you're following GitHub's advice to install Jekyll with Bundler, you'll find yourself on the Jekyll website. Now, if you get confused during the process like I did, you might find yourself wandering through the "getting started" guides, trying to figure out how Bundler and Jekyll are supposed to work with each other and which depends on what. In the midst of that confusion, you may end up inadvertently stumbling on a second installation guide that is largely similar to the initial one linked in GitHub, but has the key difference of installing Jekyll through Bundler, rather than as a standalone program. This is the guide you should follow, at the risk of ending up like me, wondering why I had so many directories labelled "gems."

Another thing: be aware GitHub Pages does not use the most current version of Jekyll. Be especially aware of this if you decide to take a stab at installing a theme, as the instructions for adding a theme to your Jekyll site will vary based on the version of Jekyll you're using. In other words, save yourself multiple hours and don't use the theme's GitHub page to troubleshoot problems, as those instructions are not compatible with the version of Jekyll GitHub Pages utilizes.