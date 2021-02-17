Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@Philip-Warren 
Philip-Warren
/
github-readme-stats
128
19k3.9k
Code
Issues
54
Pull requests
39
Discussions
Actions
Projects
Wiki
Security
Insights
docs: change github to GitHub (#657)

 master (#657)
@mmvanheusden
mmvanheusden committed 21 days ago 
1 parent c1a88ba commit ce0a97c29d2974abd8c8c973a4a12041c4cefd99
Showing  with 17 additions and 17 deletions.
 34  readme.md 
@@ -74,7 +74,7 @@ Copy-paste this into your markdown content, and that's it. Simple!
Change the `?username=` value to your GitHub's username.

```md
[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren)](https://github.com/Philip-Warren/github-readme-stats)
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren)](https://github.com/Philip-Warren/github-readme-stats)
```

_Note: Available ranks are S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), and B+ (everyone).
@@ -88,7 +88,7 @@ To hide any specific stats, you can pass a query parameter `?hide=` with comma-s
> Options: `&hide=stars,commits,prs,issues,contribs`
```md
![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&hide=contribs,prs)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&hide=contribs,prs)
```

### Adding private contributions count to total commits count
@@ -100,15 +100,15 @@ _Note: If you are deploying this project yourself, the private contributions wil
> Options: `&count_private=true`
```md
![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&count_private=true)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&count_private=true)
```

### Showing icons

To enable icons, you can pass `show_icons=true` in the query param, like so:

```md
![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&show_icons=true)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&show_icons=true)
```

### Themes
@@ -118,14 +118,14 @@ With inbuilt themes, you can customize the look of the card without doing any [m
Use `?theme=THEME_NAME` parameter like so :-

```md
![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&show_icons=true&theme=radical)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&show_icons=true&theme=radical)
```

#### All inbuilt themes :-

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/Philip-Warren/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Themes" width="600px"/>
<img src="https://res.cloudinary.com/Philip-Warren/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stats Themes" width="600px"/>

You can look at a preview for [all available themes](./themes/README.md) or checkout the [theme config file](./themes/index.js) & **you can also contribute new themes** if you like :D

@@ -208,16 +208,16 @@ Copy-paste this code into your readme and change the links.
Endpoint: `api/pin?username=Philip-Warren&repo=github-readme-stats`

```md
[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=Philip-Warren&repo=github-readme-stats)](https://github.com/Philip-Warren/github-readme-stats)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Philip-Warren&repo=github-readme-stats)](https://github.com/Philip-Warren/github-readme-stats)
```

### Demo

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=Philip-Warren&repo=github-readme-stats)](https://github.com/Philip-Warren/github-readme-stats)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Philip-Warren&repo=github-readme-stats)](https://github.com/Philip-Warren/github-readme-stats)

Use [show_owner](#customization) variable to include the repo's owner username

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=Philip-Warren&repo=github-readme-stats&show_owner=true)](https://github.com/Philip-Warren/github-readme-stats)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Philip-Warren&repo=github-readme-stats&show_owner=true)](https://github.com/Philip-Warren/github-readme-stats)

# Top Languages Card

@@ -299,37 +299,37 @@ Change the `?username=` value to your [Wakatime](https://wakatime.com) username.

- Default

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren)

- Hiding specific stats

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&hide=contribs,issues)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&hide=contribs,issues)

- Showing icons

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&hide=issues&show_icons=true)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&hide=issues&show_icons=true)

- Include All Commits

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&include_all_commits=true)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&include_all_commits=true)

- Themes

Choose from any of the [default themes](#themes)

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&show_icons=true&theme=radical)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&show_icons=true&theme=radical)

- Gradient

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Philip-Warren&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

- Customizing stats card

![Anurag's github stats](https://github-readme-stats.vercel.app/api/?username=Philip-Warren&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=Philip-Warren&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

- Setting card locale

![Anurag's github stats](https://github-readme-stats.vercel.app/api/?username=Philip-Warren&locale=es)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=Philip-Warren&locale=es)

- Customizing repo card

1 comment on commit ce0a97c
@vercel
 
vercel bot commented on ce0a97c 21 days ago
Successfully deployed to the following URLs:

github-readme-stats.vercel.app
github-readme-stats-git-master.github-readme-stats-team.vercel.app
github-readme-stats.github-readme-stats-team.vercel.app
@Philip-Warren
 
 
Leave a comment
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
 You’re not receiving notifications from this thread.
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
