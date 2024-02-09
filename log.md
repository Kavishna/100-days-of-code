# 100 Days Of Code - Log

### Day 0: January 14, 2024

**Today's Progress**: Started working on signup form.

**Thoughts:** It's been a while since I've worked with React, and I've forgotten some things. However, I've learned about nested statements in CSS, and it's amazing because it supports nesting by default without any additional library.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 1: January 15, 2024

**Today's Progress**: Started working on mynote component.

**Thoughts:** I've completed the styling and structural aspects of both the signup and signin components. While I faced challenges with the CSS grid, I successfully resolved the issue related to email autocomplete.

solution to autofill issue

     input:-webkit-autofill,
     input:-webkit-autofill:focus  {
	    transition: background-color 0s  600000s, color 0s  600000s;
    }

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 2: January 16, 2024

**Today's Progress**: Finalized working on mynotes component (CSS and HTML).

**Thoughts:** I'm not very experienced with CSS Grid, but I did manage to figure out and address the grid-related issues on my "mynotes" component. I've learned quite a bit, though I still need to stay vigilant and keep an eye on CSS Grid.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 3: January 17, 2024

**Today's Progress**: Started working on addnote component.

**Thoughts:** I'm just about done with the addnote component, but I'm having some trouble with the borders—they seem to be a jumping around when focus.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 4: January 18, 2024

**Today's Progress**: Finished working on the newnote component.

**Thoughts:** I've completed styling for the newnote component and resolved the border issue (they were jumping around when I added a border on focus). The solution was to include a transparent border on each input, so when it's in focus, it just changes colors.

    input{
	    border:  1px solid transparent;
    }

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 5: January 19, 2024

**Today's Progress**: Added some logic to mynotes component.

**Thoughts:** I've made some updates to the interaction in my notes component, but I feel that the code is becoming a bit hard to read. I'm looking for a way to refactor the component for better clarity, even though the progress may not be significant.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 6: January 20, 2024

**Today's Progress**: Strated working on little side project

**Thoughts:** As the MyNotes app starts to become a bit intricate, I realized I need to dive into understanding user authentication, and that's taking a bit of time. To keep things fresh, I've started working on a side project – a password generator app for a Frontend Mentor challenge.

**Link to work:** [Password Generator]([https://github.com/Kavishna/todo-app](https://github.com/Kavishna/password-genarator))

### Day 7: January 21, 2024

**Today's Progress**: The app is actually creating passwords

**Thoughts:** I tried out ChatGPT to write some code, and it was really useful. I had this one long string that I needed to split into four arrays, and it's awesome how quickly it tackled the task.

**Link to work:** [Password Generator]([https://github.com/Kavishna/todo-app](https://github.com/Kavishna/password-genarator))

### Day 8: January 22, 2024

**Today's Progress**: Create a password strength check function

**Thoughts:** I found some issues with my current password generation function; sometimes, it fails to generate all possible combinations. I am still unable to find a solution to this problem.

**Link to work:** [Password Generator]([https://github.com/Kavishna/todo-app](https://github.com/Kavishna/password-genarator))

### Day 9: January 23, 2024

**Today's Progress**: Made the app look much closer to the design.

**Thoughts:** I'm still dealing with the same problem of generated passwords lacking variety, and there's also an issue with calculating password strength. I've been learning about how to style the input[type="range"].

**Link to work:** [Password Generator]([https://github.com/Kavishna/todo-app](https://github.com/Kavishna/password-genarator))

### Day 10: January 25, 2024

**Today's Progress**: Finalized all css styling

**Thoughts:** Still trying to slove the problem with password generation function. All the styles are very close to the design.

**Link to work:** [Password Generator]([https://github.com/Kavishna/todo-app](https://github.com/Kavishna/password-genarator))

### Day 11: January 26, 2024

**Today's Progress**: Project completed.

**Thoughts:** Yay! I've finished the project, and it closely aligns with the original design, reaching 96% completion (due to some missing resources). I still need to update the readme, and I'll be doing that on the go.

**Link to work:** [Password Generator]([https://github.com/Kavishna/todo-app](https://github.com/Kavishna/password-genarator))

### Day 12: January 27, 2024

**Today's Progress**: Tried codewars challenge.

**Thoughts:** This test made me realize coding isn't always easy. It took me over an hour to figure out the challenge, but I finally completed it (Array.diff).

### Day 13: January 28, 2024

**Today's Progress**: Another codewars challenge.

**Thoughts:** Even though I feel like I could do more, I decided to take on another challenge on Codewars. My favorite part is checking out the answers section, where some really clever developers tackle these problems with just one line of code – it's pretty

### Day 14: January 29, 2024

**Today's Progress**: Learned about the HTML dialog and popover API.

**Thoughts:** Leveled up on CodeWars, and I'm also impressed by the HTML dialog and popover API. Their default styles are cool, eliminating the need to create manual modals and popovers with divs.

### Day 15: January 30, 2024

**Today's Progress**: Back on todo app.

**Thoughts:** I've begun working on the backend of the todo app project, but I've run out of free clusters in my existing MongoDB account. So, I need to set up a new account specifically for this project.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 16: January 31, 2024

**Today's Progress**: CRUD operations are finished.

**Thoughts:** Completed the CRUD operations for the app today and successfully finished two codewars challenges.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 17: February 01, 2024

**Today's Progress**: Working on frontend.

**Thoughts:** Having a bit of a struggle today because, even though I'm anticipating a JSON response, the server is actually returning HTML. Interestingly, when checking with Postman, it does show the expected JSON response.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 18: February 02, 2024

**Today's Progress**: Finnaly found that error.

**Thoughts:** I came across an issue where my application was giving back an HTML file instead of the expected result. Turns out, because I'm using Vite, I need to set up a proxy in the vite.config.js file to fix this.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 19: February 03, 2024

**Today's Progress**: Now I can add a post to database from app.

**Thoughts:** I went ahead and included the post request in the app, but now I realize my code is a bit of a mess. Need a clean up!

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 20: February 04, 2024

**Today's Progress**: Full of bugs.

**Thoughts:** I've figured out that it's not a good idea to jump into the design without sorting out the logic first. Starting today, I'll make sure to integrate both design and logic in my implementation process.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 21: February 05, 2024

**Today's Progress**: All the CRUD operations are working.

**Thoughts:** Great news! I've fixed all the errors, and things are running smoothly now. A simple useEffect really came to the rescue and saved the day. However, I must admit, my code is still a bit messy, but it's getting the job done.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 22: February 08, 2024

**Today's Progress**: Again full of bugs.

**Thoughts:** I tried to make my app more informative by adding context, but I ended up making a mess of things. I need to spend more time learning about useContext and useReducer because I'm having trouble understanding how to use them properly.also i missed two days in row.

**Link to work:** [Todo App](https://github.com/Kavishna/todo-app)

### Day 23: February 09, 2024

**Today's Progress**: Followed a video tutorial to create a Chrome extension.

**Thoughts:** I'm planning to develop a Chrome extension for my personal project. I recently followed a tutorial and successfully created one extension. Tomorrow, I'll be starting work on my own extension project.

**Link to video:** [Build a Chrome Extension ]([https://github.com/Kavishna/todo-app](https://www.youtube.com/watch?v=0n809nd4Zu4))

**Link(s) to work**
1. [Meta Invoice Renamer](https://github.com/Kavishna/meta-invoice-renamer)
2. [Resistor Color Code Calculator](https://github.com/Kavishna/resistor-color-code-calculator)
