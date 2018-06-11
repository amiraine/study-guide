

## Questions/Answers:

* #### How does the process of making a Git commit differ when working in pairs, versus when working independently?
  - the command is different `git commit` vs `git pair`
  - the pair file can be opened and edited in atom, the single user git can be revised using `git config --global user.name 'your name'` and `git config --global user.email 'your email'`
* #### What is the significance of the word 'master' in the command $ git push al master?
  - It pushes to the master remote branch on Github as opposed to a different branch
* #### What is the difference between the local .git repository, and the repository created on Github?
  - the local git repository is the one you are revising when you're writing code, whereas the Github repository only stores changes when you push to it. Github repositories are available whenever you are connected to the internet and a local copy is only available to the machine you're working on.
* #### How are the local .git repository, and the repository created on Github 'connected'?
  - They are connected when you `remote add` your repository. They are technically the same document but the remote repository needs to be periodically pushed to.
* #### Why is indentation and spacing important?
  - These are important for readability during review or debugging.
* #### What benefit is there to ensuring it's consistent?
  - so that things like opening or closing braces can be found quickly (as they are fairly common errors) and generally to write code faster.
* #### When do we indent?
  - at the beginning of any new declaration, inside of another element (e.g. a div)
* #### How many spaces should make up one indent?
  - two.
* #### What does the abbreviation HTML stand for?
 - Hypertext markup language.
* #### Why does indentation and spacing matter?
 - It can literally make or break code depending on a language, but also helps readability and debugging.
* #### How do you know if a tag is an opening or closing tag?
 - the opening of the tag is facing your code.
* #### What is the difference between block elements and inline elements?
  - A block element takes up the full width available on the webpage whereas an inline element only takes up as much space as it needs to display the style.
* #### What are 2 examples of inline elements?
  - span, img, anchor
* #### Why is an alt attribute on an image necessary?
 - it's not actually necessary but it helps people with impaired vision or those who use screen readers to navigate the website.
* #### Why are READMEs important?
 - documenting your work and allowing other people to download and use your program effectively.
* #### What sections should be included in one? Why?
  - title, author, installation instructions, any known bugs, and copyright related information.
  - title and author for identifying the project
  - installation so other people can download and use your program
  - bugs so that you show you're aware of your projects flaws and also so user doesn't panic when the program breaks
  - Copyright info so your project can't be plagiarized.
* #### How do we format READMEs?
 - Markdown!
* #### How do we select a specific element of our webpage to style with CSS?
 - Using the selector in the CSS file.
* #### Name four CSS properties.
 - max-width, color, background-color, border
* #### Where should a CSS stylesheet reside?
 - inside of your project directory.
* #### How do we apply the styles created in our .css stylesheet to our .html web page?
 - in the most basic way, link your stylesheet in the `<head>` tag of your HTML file.
* #### What is the benefit of branching?
 - You can test new features without fucking up your primary file.
* #### How do we create a new branch of a project?
 - `git branch 'your-branch-name'`
* #### Why would we want to merge back into master?
 - to keep/finalize any changes you've made on your branch.
* #### What is the difference between a div and a span?
 - a div is a block element and a span is an inline element.
* #### When would you use a span but not a div?
 - When you're trying to style a string of text inline.
* #### When would you use a div but not a span?
 - When you're styling a block element.
* #### What different options are available when using floats?
 - you can get block elements to sit inline.
* #### What can be accomplished with floats?
 - text wrapping.
* #### What's the difference between margin and padding?
 - Margin is the whitespace between the element's edges and the boundary of the website and padding is the whitespace between the element and its own border.
* #### What are the rules of specificity? How do they effect CSS selectors?
 - More specific selectors take precedence.
* #### Why is inline CSS less preferable than CSS stylesheets?
 - It invalidates the power of CSS.
* #### How does CSS inheritance work?
 - nested/child elements receive the same properties of the parent elements.
* #### What is the difference between a media feature and media type?
 - media feature is a property of a media type (i.e. The screen's width), media type is the type of device used to view the content
* #### What does the term viewport mean?
 - the tool that the user is viewing content with
* #### With your partner, discuss some of the benefits of media queries and responsive design. Why is it important?
 - it makes sites more usable/readable on mobile devices.
* #### What setup needs to occur in order to use Bootstrap elements in a project?
 - Depends on the project. In intro, you link the style sheet via URL in the head tag of the HTML file. In webpacks, you save it as a dependency and import it from node_modules in one of your other files.
* #### How do we add a Bootstrap component into our own project?
 - we call on the classes and IDs specified in the Bootstrap documentation.
* #### Where must Bootstrap grid columns reside?
 - Bootstrap columns must be child elements in a div with the class `row`
* #### How many columns can fit in each grid row?
 - up to 12 if the column width is set to 1. The column widths must sum to 12.
* #### What is the difference between the classes col-md-4 and col-xs-4?
 - they refer to media query [breakpoints](#breakpoint).
* #### What is the difference between a CSS class and id? When do we use one over another?
 - Classes are reusable, id's are single-use. You would use a class if you plan on applying the same set of rules to multiple elements. id's are sort of arbitrary unless you are trying to specify that the set of rules should only be used once.
* #### How do we ensure our stylesheet takes precedence over Bootstrap's? Where does this occur?
 - Source it beneath Bootstrap.
* #### What is the % operator? How is the action it performs different than simply dividing?
 - The % operator gives you the remainder of the division, rather than returning a potential decimal.
* #### How can we access the JavaScript console?
 - `ctrl + shift + j` on windows, something else on mac.
* #### When might we see NaN
 - 0/0 or dividing by a string or something.

* #### What is the difference between a framework and a library? Which is React? How can you tell?
 - The difference between a framework and a library is that a framework dictates the way in which you write your program, i.e. it *frames* and boxes in your project. A library is a set of tools that you can use that generally focus on a single functionality that you can reuse but not extend.
 - React is a library. It doesn't coerce the architecture of the program, just changes the methods you use to build within a framework.
* #### What is the virtual DOM? How does React use it? What benefits does it offer?
 - The virtual DOM is kind of abstract, simplified version of the HTML DOM that doesn't need to communicate with the browser in order to make changes.
 - (not sure about this) React uses it by calculating the differences between the virtual and literal DOM and updating the literal DOM to match the virtual.
* #### Why might a developer choose React over another library or framework? What type of projects do you think are best suited to the React library?
 - Because of React's ability to create a virtual DOM, it works best for single-page websites where data is constantly being fetched.

## Vocabulary words
