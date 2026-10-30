# mdia-3126

**My attempt at the 3126 midterm !!!!!!!**
It was ok i think but this readme will be so short because it is 4:12pm and i am running out of time D:

## Explanation of choices & understanding

- **Main Components identified:** Buttons, cards, input field (I feel like I didn't make enough now that I'm looking back...)

- **Purpose each component:** Buttons would be interactive elements that users can click on to view specific information, learn more, or register for classes. Cards held information about different classes and organized things in a way where viewers could identify information about distinguished classes or website functionality (and i may have repurposed them for what probably should've been banners or notifications instead...) The input field was for users who wanted to enter their email to subscribe to recieve Open Studio workshop updates.

- **Modifiers implemented:** I used modifiers to change the way buttons were presented depending on where they were located (ex. as a filter button active/inactive and free floating vs. a "register now" or "subscribe" button within a card.) As i mentioned earlier, i probably shouldn't have but i also used cards to frame the inital banner message ("Registration is now open!") as well as the email subscription input area. Other than the "--" modifiers, I also used "**" in cases like ".c-card**image" where i was modifying a child component within it's parent.

- **How my approach supports reuse:** My approach supports reuse because realistically I only used about 3 main components and I was able to use modifiers to slightly tweak the UI and make the interface look and feel more intuitive to users. The use of modifiers in things like my buttons or in styling different cards simplified the process because I did not have to make a bunch of new classes where I was re-writing basic things that I wanted applied to multiple components such as background colour, color, border radius, font family, margin, etc. etc. Instead of writing 5+ style changes in each class, i used modifiers that built off of the base component styles so I only had to add 2-3 style changes.
