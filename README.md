== README

I am building a personal site, where I can blog and share
examples of my work, and have people contact me.

The aim is to share what I am learning through the blog, which
can help others on the same journey. But also to show potential
employers I know what I am doing.

## Features

-Posts
  -Create/Edit/Destroy
  -Markdown
  -Syntax Highlighting
  -Comments (Disqus)

-Projects
  -Create/Edit/Destroy

-Contact
  -Contact form
  -Sendgrid

-User (Devise)

## Modeling Data

**Posts**
title:string
content:text

**Projects**
title:string
description:text
link:string

**User**

## Pages Needed
-Home
-Post#index
-Post#show
-Projects#index
-Projects#show
-Contact

<tt>rake doc:app</tt>.
