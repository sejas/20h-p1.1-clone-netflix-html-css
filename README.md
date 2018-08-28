# Netflix Clone
This is the project description for the 20h bootcamp in Gran Canaria, in order to practice HTML and CSS development.
This project has educational purposes. It contains material owned by © Netflix.

Date: 2018-08-28

## Description
In this project, you'll show all your knowledge building a Netflix clone.
In the next weeks, we will use the same project to learn JS and React.
> Imagine that Netflix hired you as top talented Front-end Developer, and make your best effort.

The project is individual. Copying is forbidden.

## Project Instructions
### The design
We will use real tools that front-end developers use every day.
Because of that, you can access the design in these apps.
- [Invision](https://invis.io/CVNQRTQPKWD)
- [Zeplin](https://zpl.io/bznqlNz)
- [Screenshots](https://github.com/sejas/20h-p1.1-clone-netflix-html-css/tree/design)

You can register in these tools or you can use a common account that you will receive in slack. 
The JPGs are in this repo.
#### Build the three pages:
- Layout
	- Home
	- Search
	- Video detail
	- The three pages must be exact to the design. A.K.A **Pixel Perfect**.
- Behaviour
	- Each images row has a horizontal scroll.
	- The movie images link to the video detail
	- The search icon link to the search page
	- The video detail link to the home
	- The video detail plays automatically any youtube video. This one of [Rick Astley](https://www.youtube.com/watch?v=dQw4w9WgXcQ) is perfectly fine.
	- The netflix logo link to the home
	- The rest of menu and footer items link to https://google.es . Some of them open in a new window.
- Metadata
	- The three webpages has the right metadata.
		- Type
		- Title
		- Description
		- Image
```html
<title>Title Example</title>
<meta name="description" content="Some short description (50–300 characters)." />
<meta  property="og:type" content="website" />
<meta  property="og:title" content="Title Example" />
<meta  property="og:description" content="Some short description (50–300 characters)." />
<meta  property="og:image" content="http://static01.nyt.com/images/2015/02/19/arts/international/19iht-btnumbers19A/19iht-btnumbers19A-facebookJumbo-v2.jpg" />
```

In order to achieve the pixel perfect, I suggest you to use the design as a background image.
```css
html.debug {
	background: transparent url(/tmp/home.jpg) no-repeat top left;
	background-size: 100%;
	
	body {
		opacity: 0.7;
	}
}
```
You can use all the tools and libraries you want to use. But focus in good coding.
Be consistent in the decisions you take.

### CSS Animations and other effects
- Use CSS transitions for focus and hover states.
	- The nav bar is fixed at the top
	- The menu items has a opacity effect
	- The footer items has a underline effect
	- The Play and My List buttons have a hover effect.
	- Each movie image has a hover effect that shows more information.
	- 

#### Create a good Readme file.
- The Readme is written in Markdown
- It includes a title
- Describe what is the project about
	- ¿What technologies did you use?
	- **Make sure you explain that this project has learning purposes**.
	- It includes the demo link. You can use [Rawgit](https://rawgit.com/) as demo link.
	- It includes a screenshot of your real project.
	- The screenshot has a link to the demo.
- It shows how to run the project. 
	- In this case, what is the main index.html and how I can see it.
	- Did you used sass? What command do you use to run the sass compiler ?
- It shows the folder structure. With a short description about each folder.
- It includes a description about the author.
- Include the sublicenses and a License for your code (Copyright, Copyleft, MIT, Creative Commons ...)
- (Optional) Write if other people can colaborate in this repo or not.

## Extra Credit
### Responsive: 
- The HTML includes the viewport meta tag in the head of the document.
- You are free to make the website responsive as you want. Think how the layouts should behaivour and think in the UX.
- Test it in your phone.

### Analytics
- Create an account and add the snippet to track the views.
```html
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-XXXXXXXX-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-XXXXXXXX-1');
</script>
```


## Process
- Before start coding.
	- Divide the project in small tasks
	- Make a detailed estimation about the time you think you will need to develop this project. Write it in a different file using Markdown Tables.
- Track your time using any tool (Toggle, Timeneye, Pomello, ...)
- Each time you finish a task, write in your markdown file the real time you used.

### Table example.

| Task         | Estimation (hours) | Real(hours) |
|--------------|--------------------|-------------|
| Navbar items | 4                  | 6           |
| search input | 5                  | 3           |
| ...          |                    |             |


- Follow the Udacity HTML, CSS and GIT Style Guides
	- [HTML Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/index.html)
	- [CSS Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/css.html)
	- [GIT Style Guide](https://udacity.github.io/git-styleguide/)
- Don't use the `master` branch to develop.
- [Use Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

## Project Resources 
- [Original Nexflix Webpage](https://netflix.com)
- [MDN](https://developer.mozilla.org/es/)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Gitflow](https://danielkummer.github.io/git-flow-cheatsheet/index.es_ES.html)
- [Open Graph Guide](https://developers.facebook.com/docs/sharing/webmasters)
- [Markdonw Generate Tables](https://www.tablesgenerator.com/markdown_tables)
- [Timeneye Project Tracking](http://timeneye.com)
- [Toggl Time Tracking](https://toggl.com/)


## Author

With ❤️ from your new teacher [Antonio Sejas](https://sejas.es) .
-  [![Twitter](https://raw.githubusercontent.com/adamfairhead/webicons/master/webicons/webicon-twitter-s.png) @antoniosejas](http://bit.ly/2A1yeOT)
-  [![Medium](https://raw.githubusercontent.com/adamfairhead/webicons/master/webicons/webicon-medium-s.png) @sejas](http://bit.ly/2NyXDBw)
-  [![Linkedin](https://raw.githubusercontent.com/adamfairhead/webicons/master/webicons/webicon-linkedin-s.png) antoniosejas](http://bit.ly/2LghNDK)

## Contribution
Feel free to make a pull request to fix any typo or mistake.

# License
See the [LICENSE](LICENSE.md) file for license rights and limitations.