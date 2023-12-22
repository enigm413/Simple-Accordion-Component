# Accordion Component

The project involves creating an FAQ (Frequently Asked Questions) Accordion component using React. The Accordion displays a list of questions along with their respective answers in a collapsible format. Users can click on a question to reveal its answer while collapsing any other open questions.

### Functionality:

The main functionalities of the FAQ Accordion component include:

- Displaying a list of questions and answers.
- Allowing users to expand/collapse individual questions by clicking on them.
- Ensuring only one question is open at a time (closing others when a new question is opened).
- Styling the Accordion to provide a clear visual indication of the active/open question.

### Implementation Details:

- _FAQ Data:_ An array of objects containing questions (title) and their corresponding answers (text).
- _Accordion Component (Accordion):_ Responsible for rendering the list of Accordion Items.
- _Accordion Items (AccordionItems):_ Represents individual items in the Accordion. Handles the toggling of open/close state for each item.
- _State Management (useState):_ Manages the current open item to control the open/close behavior.

### Technologies Used:

- _React:_ Utilized for building the component-based structure.
- _useState Hook:_ Used to manage component-level state.
- _HTML/CSS:_ Styling and structuring the component.
