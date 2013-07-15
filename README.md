μProse
====

μProse is a flat-file, javascript powered blogging platform that aims to be **super lightweight** &amp; **hassle free**.

The only requirements to get online is to have the contents of the build folder hosted someplace<br>
(actual webhost, github pages, Dropbox public folder, etc).

This will provide a very basic blogging platform without any bells or whistles. With this basic frame, <br>
customization will be a breeze as you only need to have a couple lines of code on your page to use μProse, <br>
thus allowing you to retrofit an existing page with a blog without any database requirement.

###That is an odd name.
I thought so too but it actually describes the essence of this project.

The Greek letter μ (Mu) is the International System of Units symbol for micro.<br>μProse is lightweight and small (micro) and lets you write your prose quickly and easily.
<br><br>μ also looks very similar to the letter U and would make the project's name to be Uprose.<br>Uprose *(v.)* - to come into existence or prominence.<br><br>I think either name fits the bill and don't care which one your take to heart.

###Why another blogging platform? 
I say why not. It is a nice little experiment and should be fun to code.

In addition since everything in μProse is stored in a flat-file there are no passwords to remember.<br>To update the blog you upload an updated file. It is that simple.

###Configuration
The blog configuration is all contained in JSON format within the conf.json file.

Here you can specify the basics such as:
- Blog Title
- Tagline
- Owner
- Footer (copyright etc)

μProse has an online editor that generates this configuration file for you. Just fill out the fields.

###Writing
μProse has an online editor which generates posts for you in JSON format. Since no database is <br>
used, μProse **does not** have any authentication. This means that to add new posts you re-upload<br>the flat-files 
with the changes.

The editor makes this easy. The editor will load your previous posts from the existing flat-file. When it<br>
is time to "save", the editor will append the new post(s) into the existing flat-file. From here you<br>
a zip file is generated. Just download, unzip, and overwrite the existing directory on your host.

That's it. All the work is handled for you. Except for the writing that is.

Did we mention the editor uses **Markdown**? Yup it's included. No more messing around with HTML and<br>worrying 
if you left off tags.

###License
μProse is licensed under the **MIT license**. Go ahead and break / improve it!

###Shout-outs
μProse is built on a really awesome projects made by cool people.

Shout out to the beautiful default theme used to get you started with μProse.

- [Minimal Theme](https://github.com/orderedlist/minimal) by [Steve Smith](https://github.com/orderedlist) 
