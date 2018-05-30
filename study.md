

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


## Vocabulary words
* ##### Box Model
 - a model that shows the properties of how space around an element is assigned and manipulated with [CSS](#css).
* ##### CSS
 - Cascading style sheets
* ##### DOM
 - 'Document Object Model', the DOM is an abstraction of structured text. It's a specific instance of any given HTML code that can be altered dynamically without changing the underlying code.
 - Elements in the HTML are considered 'nodes' of the DOM. The problem with the standard DOM is that for websites that load large amounts of objects (e.g. twitter, pinterest), the DOM then has wayyyy too many nodes, which makes it difficult to interact with efficiently.
* ##### Environment
 - A combination of the project dependencies.
* ##### Feature branches
 - branches specifically for testing new features.
* ##### Functional programming
 - the use of basic functions as its building blocks instead of objects
 - e.g. `var saySomething = function(whatToSay){
   alert(whatToSay);
   };`
 - organizes an application around its actions.
* ##### Inheritance
 - The process by which child elements receive the same properties of the parent elements
* ##### Inline style
 - Style that is added directly into the HTML (e.g. `<em>`, `<strong>`). These will always take precedence over CSS styling.
* ##### JSX
 - this is a [preprocessor](#preprocessor) that adds special syntax capabilities to JavaScript.
 - This is not inherently understood by the browser and must be [transpiled](#transpiler) before use.
* ##### loaders
 - the part of a program that is responsible for loading programs and libraries.
* ##### Minify
 - Minified code is the process of removing unnecessary characters (e.g. whitespace, comments, etc.) that humans need to read code but computers do not to reduce file size.
* ##### Module bundler
 - A tool that collects source code and dependency code and concatenates it into a central file
 - This is done to decrease load time
 - Most bundlers will also [minify](#minify) code
* ##### Object-oriented programming
 - The act of using objects to encapsulate data.
 - e.g. `function Contact(first,last){
   this.firstName = first;
   this.lastName = last;
   this.addresses = [];
   }`
 - organizes logic around the information that the application manages.
* ##### Package manager
 - A tool to manage dependencies.
 - npm is the most common, but yarn is also commonly used in the industry.
* ##### Plugins
 - a software component which adds a specific feature to an existing program.
* ##### Preprocessor
 - a program that modifies data to conform to the input requirements of another program.
* ##### Property
 - The characteristics a CSS rule alters (e.g. color, font size)
* ##### Rule
 - A block of CSS that details the stylistic instructions applied to an HTML element.
* ##### Selector
 - The part of a CSS rule that determines which HTML element the rule applies to (e.g. class/id/tag)
* ##### Self-closing element
 - an HTML element that doesn't require a closing tag.
* ##### Transpiler
 - a compiler that turns the source code in a given language into the equivalent source code in another language.
* ##### Value
 - The attribute a [CSS](#css) rule applies to the specified property.
* ##### Virtual DOM
 - an abstraction of the HTML DOM. considered React's local and simplified copy of the HTML DOM.
 - This is faster and better than the regular DOM because it doesn't need to communicate with the browser in order to make its changes.
 - React can calculate changes between the true DOM and the virtual DOM and update the true DOM to match the virtual. This is called *reconciliation*.
* ##### Webpack
 - A type of [module bundler](#module-bundler).
 - Has flexible configuration and supports [plugins](#plugins) and [loaders](#loaders)
 - Has [development server](#development-server) feature.
