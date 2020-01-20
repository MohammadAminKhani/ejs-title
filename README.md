# ejs-no3
98.10.30  title | from tinyProjects

[This is final video!](...)

## Overview
embed js in html!
```
<title><%= pageTitle %> | <%= siteTitle %></title>
```
## step by step

### Review
index.js changes over time.
```
re.send('...')
res.render('index1')
res.render('index1',{...})
```
### app.js
```
app.locals.
```
### index.js
```
res.render('index1',{
  pageTitle:'Home',
  pageID:'home'
})
```
### index.ejs
```
<title><%= pageTitle %> | <%= siteTitle %></title>
```
