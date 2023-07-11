## Frontmatter
The beginning of the file will need the following yaml front matter:

```YAML
---
url: blog/daily/2023/2023-07-05
title: "5th Of July 2023"
date: 2023-07-05T20:48:07+01:00
draft: true
description: 5th Of July 2023 - Daily Journal of Jamie Storey
noindex: false
featured: false
pinned: false

nav_weight: 1003

# comments: false
series:
  - Daily 2023
categories:
#  - 
tags:
#  - 
images:

authors:
  - jamiestorey
---
```

___

Some of those are static but some will need to change and they are:  

 1. url
 2. title
 3. date
 4. description
 5. nav_weight

### Variables

 I will need a variable for the date in the format of YYYY-MM-DD which is used for url and date but also need a datetime.  

 The title and description both need dates with words and a suffix like ***"5th Of July 2023".***

nav_weight should increment by 1 for each day.  