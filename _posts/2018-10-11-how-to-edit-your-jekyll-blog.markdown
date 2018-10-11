---
layout: post
title: How to Edit your GitHub-hosted Jekyll Blog
date: 2018-01-17 20:45:20 +0200
description: # Add post description (optional)
img: hello-world.png # Add image post (optional)
tags: [How-to]
---

So! You've got a Jekyll blog hosted on GitHub and you have no idea how to add new posts? You've found just the right blog post then! The first thing you need to do is set up your development environment.
* Download [GitHub Desktop](https://desktop.github.com/)
* Download [Atom](https://atom.io/)
* Clone your GitHub blog repository
  * It should look something like this: https://github.com/username/username.github.io/
  * To clone click the green clone or download button.
* If you're collaborating on the project and it's been a while since you cloned then make sure to click Fetch origin in GitHub Desktop before making any edits
* Open your blog folder in Atom, it should be inside your GitHub folder
* Open the posts folder (note that it has an underscore before its name)
* Right click on a post and duplicate it (note the post is a .md file)
* Rename the file name according to the correct date and name of the post (put dashes where there should be spaces and omit punctuation)
* Open the file and edit the details in the top of the file (title, date, description, tags)
* Underneath the content at the top (on a new line after the triple dash) you can start writing. If you've already written your post elsewhere then just paste it in.
* Format your post
  * If you want to hyperlink a word or phrase, surround it with square brackets and then immediately follow the square brackets (no spaces) with parenthesis including the URL
  * If you want to make a word italics add an asterisk either side of it
  * If you want to make a word bold add two asterisks either side of it
  * For more formatting tips use this [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Add the image for the blog post
  * Save the image that you want to use into the img folder (can be found under assets)
  * Update the data at the top of your md file blog post to include the name of the image file
  * Make sure the name and file extension are an exact match (including capitalisation e.g. .png/.PNG/.jpg/.JPG/.jpeg/.JPEG) otherwise your image might not show
* Save your md file (Ctrl + s)
* Open GitHub Desktop
* Add a **Summary** of the changes in the input box in the bottom left, e.g. New blog post about cute dogs
* Click the **Commit to master** button
* Click the **Push origin** button
