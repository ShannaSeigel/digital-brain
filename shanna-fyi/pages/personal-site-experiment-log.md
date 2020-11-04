<small>← [Home](../../page-1)</small>

# Experiment Log
Keeping track of questions and problems as I, a person with minimal recent experience in website building, try to build a website.
<!--Add a table of contents if this page gets too long?-->

## Bookmarks
- [Getting started with GitHub pages](https://guides.github.com/features/pages/)
- [Main GH guide](https://docs.github.com/en/github/working-with-github-pages) 
	- [Guide GitHub Custom Domains](https://medium.com/@hossainkhan/using-custom-domain-for-github-pages-86b303d3918a) 
	- [Custom domains w/GitHub](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/about-custom-domains-and-github-pages) 
	- [GH Pages management](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site)
	- [Troubleshooting](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/troubleshooting-custom-domains-and-github-pages)
- [Jekyll pages](https://docs.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll) 
	- [blog w/Jekyll+GH Pages](https://kalyanv.com/2018/09/12/build-a-blog-using-jekyll-and-deploy-to-github-pages-and-set-custom-domain.html)
	- [GH Themes/CSS](https://docs.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll)
	- [Layouts](https://jekyllrb.com/docs/step-by-step/04-layouts/)
	- [Liquid Intro](https://shopify.github.io/liquid/basics/introduction/)
	- [Liquid date format](https://shopify.github.io/liquid/filters/date/)
	- [Minima theme](https://github.com/jekyll/minima)
- [Many posts from Tania Rascia](https://www.taniarascia.com/)



## Formatting with .md pages
What I've learned when it comes to using markdown pages for website pages: 
1. File names MUST be a single string with no spaces in order to create links.
2. Stick to lowercase text in naming because links are case-sensitive.
3. Wikilinks `[[notes with double brackets]]` are not a standard markdown tool.
	- Use standard link format with `[anchor text](link location)`


<br>

# Questions


`❓ Can a personal website and a site for zettels live in different GitHub repositories?`

I was thinking the answer would be no but I wondered if having a repository folder inside my main site folder would help. I can certainly create links in obsidian between those folders. I'll try adding my previous experiment site ["Shanna's Slipbox"](https://shannaseigel.github.io/slipbox/). It currently shows up as a subsection of shanna.fyi.
- Testing link to another repo: "2020-08-28-test-post" This nearly worked. It did go to shannafyi/slipbox, but blog files are named differently on github.
- new test link to a stand alone page "new_format_rules"	
	- i think these links to .md files aren't being translated to .html?
- Checking links to other pages within the same repo and they are rendered just fine.

`🧪 Result: Maybe I can't easily link between to two repositories the way I can easily link between files in Obsidian. Or at least I don't know how to do this.`

<br>

`❓ Can a website for personal projects, professional info, and my LYT system coexist under one domain?`

- [Maxime V personal garden/blog combo](https://maximevaillancourt.com/) and [breakdown of his personal site vs garden template](https://github.com/maximevaillancourt/digital-garden-jekyll-template/issues/19)
- [Question in LYT forum](https://forum.linkingyourthinking.com/t/thoughts-on-online-notes-personal-website/157)

Nov-2020: New repository of all digital brain related files, which could include notes, cv, or other articles, and using .gitignore to skip drafts or anything not ready for display.


<br>

## Older Notes
What have I been learning since starting this experiment?

#### 2020-08-22
- Just exploring themes rather than really learning anything tonight. 
- Curious how to get logo working. Or literally any of the theme. Kind of just guessing here.
- Going to try the desktop option. Esp b/c GH says their desktop program doesn't use the command line and I have limited command line experience.
  - see d/l page: [https://desktop.github.com/](https://desktop.github.com/)
  - see directions page for getting familiar with program: [install instructions](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/creating-your-first-repository-using-github-desktop)
  - Spent time testing out how to correctly create links between .md files.
- Able to see different types of links in my Obsidian graph that don't translate to links in GH Pages.
	- `[zk note test](202008231210 zk note.md)` worked fine but the filename has spaces. Immediately broke rule #1 about formatting.

#### 2020-08-23
- Spent like four hours trying to solve a problem I didn't need to solve.
	- Wanted to try a private repository hosted to Netlify. I got as far as installing Homebrew, Ruby, etc. before Jekyll just would not install for me and I gave up. I was following tutorials but since I don't normally use the command line I really had no idea what I was doing.
	- Really no reason to have a private repository and add the extra steps of using a service outside of GitHub, I just wanted to learn more.
		- Forgot another plan I had for myself: **keep it simple, get fancy later.** 
- Now just trying to clear out all my scrap notes and test files.
- How in the holy hell did I spend so long just trying to add an image and a caption. What is this shit? Like text gets stuck to the previous line somehow and doesn't want to cooperate with me?
	- Guess I'm glad I deleted my earlier notes full of F-bombs.

#### 2020-08-24
- After a bazillion commits because I haven't figured out local view, I think it's good enough. I forgot how many tiny, tiny changes suck up hours of time. And I'm not doing anything complicated.

#### 2020-08-28
- No major changes, just reading more about command line and working with Jekyll. My first attempts at following a tutorial to install Jekyll was a bust but I didn't even know what I was doing. Trying to back up a bit.
- Also trying to pace myself since I have loads of other things to do in my life and it's not like anything I share here has a deadline.
- The page titles keep getting duplicated and I saw last week how to fix this but it's still driving me slightly bonkers when I want one title in the navigation and a more descriptive title on the page. It seems like there are other ways to add navigation links ([review here](https://jekyllrb.com/tutorials/navigation/)) but I haven't had time to review.
- I might need to figure out if/how I'm using tags. They just exist in Obsidian right now but they're rendered on pages and are just plain text online.








------------------------
<small>↳ <i>Created Oct-28-2020 / Updated Nov-04-2020 </i></small>