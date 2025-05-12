# Phase III: Prototypes and User Testing

## Introduction

Following our successful Phase II refinement of wireframes, our UX team has now advanced to creating and evaluating a high-fidelity prototype of Archenemy. The primary objective of this phase was to conduct usability testing with actual users to validate the interface design, identify usability issues, and gather insights for further refinement before implementation. Our usability testing aimed to ensure that users can navigate through the core functions of account creation, matchmaking, communication, and profile management with ease and satisfaction. This report details our methodology, findings, and recommendations derived from these evaluations.

## Methods

For our usability evaluation, we employed a formative evaluation approach combined with a think-aloud protocol. This approach was selected to gain insights into users' thought processes, experiences, and pain points while interacting with our prototype. The formative nature of the evaluation allowed us to identify usability issues early in the development process, making it possible to refine the design before implementation.

The think-aloud protocol required participants to verbalize their thoughts, reactions, and decision-making processes while completing tasks. This provided valuable qualitative data about their mental models, expectations, and areas of confusion.

We had 6 participants (n=6) for our usability study. The participants had varied backgrounds and experiences with matching apps, which provided diverse perspectives on our design. The recruitment diversity included:

1. College students >18
2. Mix of genders
3. Varied experience with matching apps
4. Some interest in competitive activities

The usability tests were conducted using our Figma prototype (high-fidelity) with a standardized protocol and script for consistency; the participants' responses were written into our data collection spreadsheet. The participants signed an informed consent form, and an in-room moderator followed the protocol to effectively test the prototype.

We designed five tasks to evaluate different aspects of the user experience:

### Task 1: Account Creation

Participants were instructed to create a new account for themselves.
This task evaluated the learnability and efficiency of the registration process, with all required fields found on the Register and Create Account pages.

Research questions: Is the account creation process intuitive? Are the required fields clear? Can users complete registration without assistance?

### Task 2: Finding and Chatting with an Archenemy

Participants were asked to find an archenemy and start a chat to express their hatred.
This task evaluated the core matchmaking functionality of the app, found on the Home page.

Research questions: Is the process of finding and connecting with archenemies intuitive? Is the messaging interface easy to use? Do users understand the "yes/no" archenemy selection mechanism?

### Task 3: Password Reset

Participants were instructed to reset their account password.
This task evaluated the findability and usability of our **Reset Password** button in the Settings page.

Research questions: Can users locate the password reset function? Is the reset process straightforward and efficient?

### Task 4: Finding FAQ/Help Information

Participants were asked to access the FAQ for more information.
This task evaluated information architecture and navigation, notably the **HELP** button on the Settings page.

Research questions: Can users easily find help when needed? Is the help content organized in an intuitive location?

### Task 5: Edit Account Information

Participants were instructed to edit their account and update information.
This task evaluated the profile management functionality on the Account page.

Research questions: Is the profile editing process intuitive? Can users easily update their information?

For each task, we collected both quantitative and qualitative data. Quantitative measures included task completion rates (success/failure), ease of use ratings on a 5-point scale (1=Very Difficult, 5=Very Easy), and the likelihood to use the app in real life (1-5 scale). Qualitative measures were verbal think-aloud comments during task completion, observations of user behavior and navigation paths, and feedback during post-test debriefing.

## Findings

![Our Quantitative Data](https://github.com/user-attachments/assets/37c08dc6-75c7-49b8-9b9b-22d5c310d57f)

### Quantitative Results (graph above)

Our usability testing yielded strong quantitative results across all tasks. All participants (100%) successfully completed each of the five tasks, demonstrating that the core functionality of the Archenemy app is navigable and usable, albeit with varying degrees of ease. Our spreadsheet can be found [here.](https://docs.google.com/spreadsheets/d/1wkU67Ii0XeaUfzzLd5b22Wcr9DBEqPfqJ_evFl1MAww/edit?gid=0#gid=0)

#### Task Completion and Ease of Use

The following chart summarizes the task completion rates and average ease of use ratings for each task:

| Task | Description | Completion Rate | Ease of Use (1-5) |
|------|-------------|----------------|------------------|
| Task 1 | Account Creation | 100% | 5.0 |
| Task 2 | Finding & Chatting | 100% | 4.3 |
| Task 3 | Password Reset | 100% | 3.8 |
| Task 4 | Finding FAQ/Help | 100% | 4.0 |
| Task 5 | Edit Account | 100% | 5.0 |

Task 1 (Account Creation) and Task 5 (Edit Account) received the highest ease ratings (5.0), indicating these features are highly intuitive. Task 3 (Password Reset) received the lowest ease rating (3.8), suggesting potential room for improvement in the findability or process of this feature.

#### Likelihood to Use

When asked about their likelihood to use the Archenemy app in real life, participants gave an average rating of 2.8 on a 5-point scale. This moderate rating suggests that while the app is functional and novel, there may be concerns about its practical utility or appeal in real-world contexts.

### Qualitative Results

Qualitative data from the think-aloud protocol and debriefing sessions revealed these insights:

#### Task 1: Account Creation
- Users found the registration process straightforward and intuitive
- Some confusion about what the "subtitle" field represented
- Some users attempted to click on images to select profile pictures

#### Task 2: Finding and Chatting with an Archenemy
- Users expected more feedback after clicking "Yes" to confirm a match
- Some confusion about the meaning of "Yes" and "No" buttons (vs. traditional swiping)
- Users wanted clearer indication of who sent which messages in the chat
- Need for notifications when new matches occur

#### Task 3: Password Reset
- Users had difficulty locating the reset password function
- Several users looked for it in the Account section before finding it in Settings
- Suggestions to move this functionality to the Account tab for better findability

#### Task 4: Finding FAQ/Help
- Users had significant difficulty locating the FAQ/Help section
- Several navigation paths were attempted before finding it in Settings
- Confusion about the difference between "Help" and "FAQ"
- Suggestions that Help should be more prominently displayed in navigation

#### Task 5: Edit Account Information
- Users found account editing straightforward and easy
- Suggestions for real-time preview of profile changes
- Clear and intuitive field editing

### Background Context

Our background questions revealed that half of our participants had no prior experience with matching apps. Those who did mentioned features they valued: swiping mechanisms, chat functionality, location-based matching, and profile customization. Common frustrations with existing apps included ghosting, repetitive interactions, and limited filtering options for non-binary users. All participants engaged in some form of competitive activities, most commonly video games, sports, and friendly competitions with friends. Motivations for competition primarily centered around the simple desire to WIN.

### Overall Impressions

Participants generally found the Archenemy concept novel and entertaining, calling it a "Great idea, hilarious", "Really excited, not sure if needed but a fun app", and a "Cool app if [you] want to 'brawl'". The most valued features included the main matchmaking functionality, chat pages, and the overall concept of finding rivals. The confusing aspects included navigation issues, the location of help/FAQ, a lack of system feedback for actions, and an unclear meaning of Yes/No buttons versus swiping.

## Conclusions

Based on our findings, we recommend the following design improvements:

1. **Improve Navigation and Information Architecture**
   - Move Help/FAQ to a more prominent location in the main navigation
   - Make the Home/Haters tabs visually distinct from other tabs (enhance visual hierarchy)
   - Ensure consistent naming between "Help" and "FAQ"

2. **Enhance Feedback Mechanisms**
   - Add clear feedback after matching decisions
   - Implement notifications for new matches/haters
   - Provide visual confirmation when actions are completed successfully

3. **Refine Chat Functionality**
   - Add sender names to all messages for clarity
   - Consider adding emojis or other expressive elements
   - Provide more visual distinction in the chat interface

4. **Optimize Account Management**
   - Move password reset functionality to the Account section
   - Add real-time preview of profile changes while editing
   - Clarify the purpose of fields like "subtitle"

5. **Improve Onboarding**
   - Consider adding a brief tutorial or walkthrough for first-time users
   - Provide clearer instructions for the matching mechanism (Yes/No vs. swiping)
   - Add tooltips for unfamiliar elements

6. **Visual Design Enhancements**
   - Improve color scheme/theme
   - Reduce whitespace in the home page
   - Better center profile images

### Features to Maintain

The following aspects of the design were validated by our testing and should be maintained:

1. **Account Creation and Editing**
   - These processes received the highest ease of use ratings
   - Users found these flows intuitive and straightforward

2. **Overall Layout and Structure**
   - Users appreciated the clean, simple layout
   - Basic navigation was generally understood

3. **Core Matchmaking Concept**
   - Users found the rivalry concept novel and entertaining
   - The basic match-and-chat flow is working well

4. **Chat Interface Foundation**
   - While needing some refinements, the basic chat functionality works
   - Users successfully found and initiated conversations

## Caveats

Several limitations should be considered when interpreting our findings:

1. **Sample Size and Composition**
   - With only 6 participants, our sample size is relatively small
   - Participants may not represent the full diversity of potential users
   - Half of our participants had no prior experience with matching apps

2. **Prototype Limitations**
   - As a Figma prototype, some interactive elements had limited functionality
   - In a real application, users might encounter different constraints or performance issues
   - Some user paths may not have been fully implemented in the prototype

3. **Testing Environment**
   - The controlled testing environment may not reflect real-world usage contexts
   - Users might behave differently when using the app in their natural environment

4. **Subjective Evaluations**
   - Ease of use ratings and likelihood to use are subjective measures
   - Different users may have different thresholds for what constitutes "easy" or "difficult"

5. **Novelty Effect**
   - The uniqueness of the Archenemy concept may have influenced initial reactions
   - Long-term engagement might differ from first impressions

Despite these limitations, our usability evaluation provided valuable insights that will guide the refinement of Archenemy. We could create a more intuitive, engaging, and satisfying user experience by addressing the identified issues while maintaining the strengths of our current design.
