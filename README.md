# LinkedUp
LinkedUp is a chrome extension built with React to power up your LinkedIn! 

Project Page and Screenshots: https://devpost.com/software/linkedup-ikabwv

## Project Summary
Ever wondered how you can become a better networker? Well we can _Link you Up_ with our versatile extension! We created LinkedUp, a chrome extension to help early **career job seekers** leverage their connections to help maintain their network for career growth and job searching.    



## Inspiration
We started by asking ourselves what problems we have in our current disposition, particularly as students or recent graduates who are facing job loss, unproductivity, and the craving of human connection in the time of COVID-19. We brainstormed that it would be very **beneficial** to have a way to keep track of who we want to contact, what to say to them, and how to approach potential **professional relationships**.



## What it does
Have you ever saw someone you wanted to reach out to on LinkedIn and thought, "wow, I really wish I can read up on this person later," or "gosh, I'd love to connect with them!" Well LinkedUp, a chrome extension for LinkedIn, will help facilitate your networking process! It allows users to **bookmark people's profiles** and take notes on them for future reference, and to browse through saved profiles. It also allows users to browse message templates with guidelines on how to write **professional outreach emails** (for informational interviews, cold outreach messages, interview follow-up emails, etc). It also allows the user to create and save their own templates for future use.

**LinkedIn Profile** - A mini widget would open when the user clicks on the chrome extension, shows the tracked connection’s name, school/current work and position, and a notes input section in which people can log. People whom you haven’t heard back from the longest is highlighted and placed at the top by default. 

**LinkedIn Profiles List** - The data is displayed as a chart with the categories of name, company, school, notes that the user takes, and last contact date.

**Message Templates** - These are categorized by scenarios, and message templates include (but aren’t limited to) mutual connection intros, cold reach outs, etx. There is also a button to compose your own message and save it as a template. Users can compose and save messages (as templates) that they can then copy and send to people they want to network with

The extension's **target audience** are students seeking or who lost jobs/internships due to COVID-19. Our **secondary audience** is anyone using LinkedIn who currently wants to improve their network.



## How we built it
**User Research**
We sent out a Google Survey before we started any visual/design/code development to best gauge our target audience, and researched best practices for a greater user experience.

**Prototyping and Iteration**
We considered how users might sign into our extension, and thought directly via LinkedIn would be the best call. We also created a logo and brand standard for LinkedUp based on LinkedIn's color palette (though adjusted to best fit our extension and its flow into LinkedIn's existing UI). We referenced existing UI patterns to help us create more user-friendly projects, and reworked our mockups and designs in Figma to really develop our product.

**Front-End and Visual Development**
CSS was pulled from Figma but the styling was definitely not all there. We restyled the CSS and set up an aesthetic that best fit the brand standard. Colors and layouts were meticulously chosen, which was then translated to a stylesheet.

**Back-End and Web Scraping Development**
Chrome Storage API to persist with users' data, and Webpack, Babel to bundle all the React, SCSS, CSS, assets into the predefined chrome extension structure.

**Putting it All together**
We collaboratively worked on VS Live Code to make changes.



## Challenges we ran into
**Connecting our prototyped design** and translating it to code was difficult. **Time constraints** also challenged us to work fast and develop as thorough a project as possible. We had members on the east and west coasts, so Zoom-ing was beneficial for us. **Working Remotely** was especially difficult when attempting to connect the front and back-ends of our project, and as nice as VS livecode is, for a chrome extension it was hard to work quickly when you have to build the project every time you want to see visual updates.

We also encountered **technical difficulties** that inhibited us from opening a new tab on chrome via our extension.Chrome Extensions have been known for vanilla html, css and package.json, but our app functionality is way more complex for just few html, css files. So we have to look into React and how to use Webpack to bundle React components to html files.

## Accomplishments that we're proud of
We are very proud of our **robust concept** and **user research**. We conducted thorough data-backed research through our Google Survey (with over 100 responses) in a very short amount of time. We **overcame** many of the obstacles we faced and got to work with new software (some of us were new to Figma, Visual Studio Code Live Share) in a collaborative setting.



## What we learned
In terms of **user experience** we learned that **63.5% of our subjects stated they were worried** about not knowing what to ask about in the company, followed with the fear of sounding too forward (56.5%), and not knowing who to reach out to (54.8%). We addressed this issue by **allowing users to take save-able notes on the connections** they wanted to reach out to, so that when they eventually do reach out, they won't be as stuck on what to say.

Most people said that they way they network is usually by meeting another person in real life (70.4% of participants), followed by their next method of communication, through conversing through text (60%). Since meeting people IRL is no longer viable, we wanted to streamline communication through text by facilitating **message composing**.

In terms of technical, we managed to finish the MVP, we have also learned how to bundle web framework into vanilla html, css and js. Also, we learned how to use Chrome Storage API and use the Redux as Proxy Store to interact with it.


## What's next for LinkedUp
**Login Function** - We would like to allow users to see what connection degree they have in association with the profile they're viewing (1st, second, 3rd degree connection).

**AB Testing** - We thought it would be nice to conduct further user testing to see which features have the most usage by setting up control and subject groups to test LinkedUp.

**Time Tracking** - We would like to implement a time tracking system, connected with a user's calendar, to allow the user to be more proactive when tracking their networking progress.




