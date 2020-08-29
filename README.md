# GSOC2020
Summary of GSOC2020 participation


GSOC 2020 experience
Internationalization and Spanish Localization for p5.js web editor
For my GSOC2020 project, I worked on Internationalization and Spanish Localization for the p5.js Web Editor. The p5.js Web Editor is a web-based code editor that lets artists, educators, and programmers create and share p5.js sketches online.
The journey about how I ended up in this program starts with the aspects that I considered to apply to this specific organization with my proposal were the following:
I knew Processing from previous works, and always has been an appealing project, even if I usually ended using OpenFrameworks or Unity3D.
Other projects of this foundation already had translations for their pages, which suggested to me that the Processing foundation required that functionality in this particular project. 
The project has been released, but there was a real opportunity to add value and to reach and connect with people from Latin America (and US), which given my background, I perceived as a priority.
From a selfish point of view, I didn’t know anything about internationalization, localization, and basically all the tech stack involved in this project, so I thought that was a good idea to learn some skills over the summer. 
I´m in the last year of my PhD, so it was now or never.
Once that I got accepted and maintained the first meetings with my mentor, Andrew Nicolaou, we agreed to narrow the scope of my proposal and specify a work dynamic, including weekly meetings, and open channels through Slack, email and google meet to discuss any problem.
Some of the first tasks were:
Study the different alternatives that existed to internationalize software projects given the current libraries used by the project.
Define how to organize the translations, given that the p5.js Web Editor is a big project, and several components interact to provide functionality.
Take into account that moving from English to Spanish introduces some discussion about the use of gendered terms, and how to tackle those issues in concordance with Processing Foundation principles. 
Going back to the project, once that a library was defined, the project was considered over three dimensions: what functionality is required (functionality), how to simplify the process for future contributors (workflow) and why the translations are performed in any specific way (accessibility).
 The following functionality was required.
How to switch back and forth between languages
How to serve the translations just once per language
Dynamically load the translations when required
How to save the user’s preferred language
Provide the actual translations for the web page components
In the workflow side, the following issues were tackled:
How to split and organize the translation file : flat vs embedded structure
Naming conventions for the keys: CamelCase, etc
Specific problems: dates, interpolation, plurals
And in the cultural/accessibility side: 
Do we have to use genders in the language, or we can use non-gender nouns?
 What happens when this is not possible? 
Are we thinking in terms of accessibility, using ARIA labels, using the simplest option for Screen readers? 
 
 The full list of Pull Requests I worked on is here. 
In the end, my participation in GSOC program was a great experience, I was lucky for being part of a welcoming community, and my first experience within an Open Source community has been very likeable, expecting to contribute more in the future.


https://docs.google.com/spreadsheets/d/1ohsRqqzKiOPaURopZOeyJzxy9SIx7vW5L37kKLuWN3M/edit?usp=sharing
