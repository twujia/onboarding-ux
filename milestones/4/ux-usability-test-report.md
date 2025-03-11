## Usability test report
**Name:** Z.L\
**Date of test:** 10/03/2025\
**Operating system:** iOS (via TestFlight)

## User's observations during testing
### Login Page
- No password rules displayed initially; had to wait for a popup message.  
- First attempt at creating a password was often incorrect, making the process inefficient.  
- Expected the T&C agreement button to be positioned on the left rather than the right.  

### Enabling Focus Bear's Features
- Liked the suggested main goals and selected all available options.  

### Choosing Habits
- Found the habit selection boxes visually inconsistent due to unequal sizing.  
- Confused by the second screen that showcases added goals—tried tapping on them, expecting interaction.  
- Selecting too many goals caused the container to overflow, making the UI look out of place.  
  - Suggested fix: Resize the container and move the “Add Another Goal” button below the container.  
- Unclear why a similar screen appeared again right after choosing goals.  

### Choosing Habits for Morning/Night & Setting Time
- Unsure if setting minutes for habits is ideal since different habits require varying time durations (e.g., exercise vs. reading).  
- Some habit names were unclear (e.g., “Record energy level” was not self-explanatory).  
- Display showed time in minutes and seconds, but input field required seconds only, causing inconsistency.  
- Attempted to remove habits by pressing "Edit Habits" but was confused by duplicate functionality in the main screen.  
  - Suggested fix: Consolidate habit modification into a single location to reduce confusion.  
- Edge case issue: Maximum habit duration was set at 999 minutes, but there was no total duration limit (allowed an 8-hour morning routine).  
- Edit Habits screen issues:  
  - Pressing the X button did not save changes; had to press Finish, which was stuck at the bottom instead of floating for easy access.  
  - Redundant "Add Habit" buttons at both the top and bottom of the screen.  
  - Some text content overflowed past the container.  
  - Emojis/icons at the top of each habit were unintuitive and did not feel part of the UI.  
    - Suggested fix: Attach short descriptive text inside the container next to the icons.  
  - Inconsistent icon behavior—some displayed text, while others did not.  
  - Unclear how to add icons to habits (e.g., associating the handwriting emoji with a journaling habit).  

#### YouTube Video URL Attachment
- Info button content was hidden behind the container.  
- "Manage YouTube URLs" button blended into the header, making it hard to recognize as interactive.  
- Liked the feature of embedding YouTube videos into habits.  
- Bug: Editing habit duration caused an issue—changing the seconds field also altered the minutes field.  

### Skip Button Functionality
- Unclear purpose—did it skip just the habit selection step or the entire onboarding process?  

### Choosing Time for Morning & Night Routine
- Unable to go back after choosing a time for the morning routine.  
- Night routine selection was labeled "Finish work/studying," which was unclear.  
- Appreciated the playful language used throughout the app.  

### Choosing Apps to Block
- Apple integration was well-implemented.  
- Grouping apps by function was intuitive and well-received.  

### Starting a Focus Session
- Unclear what a "focus session" was; no definition provided.  
- Unable to receive messages from blocked apps (was this expected behavior?).  
- Onboarding tasks like "Start focus session" and "Edit habits" were not well-explained, making it unclear what actions were expected.  

## Follow up questions
### General  Experience

**What was easy or intuitive about the process?**
- The process was straightforward; starting a session was easy.  
- The app automatically blocks distracting apps, which is very helpful.  
- The onboarding/tutorial was clear in guiding habit and routine generation.  
- Liked the confirmation step before postponing or pausing blocking—this feature could serve as a last resort to encourage productivity. 

**What was difficult or confusing?**
- Large amounts of text on the screen made it difficult to process information, especially when choosing morning/night routine times.  
  - Suggested improvement: Use visuals like pie charts or videos to explain concepts.  
- Editing habits was confusing—pressing "X" did not indicate that changes were unsaved.  
  - Suggested improvement: Add a confirmation message or auto-save function.  

### Navigation and Clarity

**Did anything feel unclear or unexpected?**
- Blank screens appeared at certain times (e.g., habits screen when it's not morning or night), making it unclear what was supposed to be there.  
- Customization options being in the settings page felt unintuitive, as users may want to adjust these frequently.  

**Were you able to find everything you needed?**
- Yes.

### Design and Accessibility

**Was the text and UI easy to read and interact with?**
- Text-heavy screens were difficult to read and process.  
- Some buttons did not look like buttons, such as:  
  - "Manage YouTube URLs"  
  - Onboarding tasks (Start Focus Session, Edit Habits)  

**Did anything feel too overwhelming or distracting?**
- Minor UI inconsistencies, such as button alignment and positioning, were slightly distracting.  

### Overall Feedback

**How would you describe your experience in a few words?**
- Overall, the app was well-structured, and everything was easy to find.  
- However, some interactions need polishing for a smoother experience.  

**Is there anything you would change or improve?**
- Reduce the amount of text displayed at once.  
- Consider implementing a reward-based system similar to the Forest app (e.g., growing a tree for successful focus sessions, losing progress when distracted).  

**Would you use this app again? Why or why not?**
- Yes, because it effectively blocks distracting apps and helps reduce phone usage.

## Reflection
### What surprised you the most about how your test participant used the app?
I was not expecting the participant to be so detailed in their feedback, especially when they were just speaking their thoughts out loud during the testing session. I believe the participant has said that they held prior experience as a QA tester, which may explain their thoroughness. Regardless, I am still appreciative of their input and I am confident their insights will contribute towards improving the app.

### Did they encounter any issues that you didn’t expect?
The participant encountered some unexpected issues, particularly with recognising interactive buttons, such as the "Manage YouTube URLs" option which did not appear clickable. The process of editing habits also proved more difficult than expected, as they did not realize that pressing "X" did not save their changes. Additionally, inconsistencies in UI elements, such as different button styles and misaligned content, made navigation more challenging than anticipated.

### How could this test improve your approach to UX design?
This usability test reinforced the importance of incorporating visual cues (e.g. icons, images, interactive elements, etc.) to reduce the usage of text-heavy instructions. It also highlighted the need for consistency in UI design, ensuring that all interactive elements are clearly distinguishable. The test further showed that error prevention and feedback messages (e.g. confirmation prompts, tooltips) are crucial for a smoother user experience.
