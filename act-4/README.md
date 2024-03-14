# Building Modal 4️⃣

Modal popups are common in web design for displaying information, gathering user input, or guiding users through multi-step processes. This activity combines CSS positioning, combinators, and pseudo-classes to create a simple yet functional modal popup that appears over the page content.

## Objective

Create a modal popup that appears when the user clicks on a button. The modal should be centrally positioned over the webpage content, with a backdrop that dims the rest of the page to focus attention on the modal content.

## Expected Output

- Initially, the modal is not visible on the page.
- When the user clicks the "Open Modal" button, the modal appears centered on the screen with a semi-transparent backdrop that covers the webpage content, creating a focus on the modal.
- The modal contains a close button (×) in the top right corner. Clicking this button or the backdrop outside the modal content closes the modal, returning focus to the main page content.
- Implement the modal functionality (opening and closing) using CSS only, possibly leveraging the `:target` pseudo-class or hidden checkboxes with labels if you prefer a no-JavaScript approach.

![output](https://iili.io/JWEQ4Ns.gif)

## Extra Challenge

- Add animations for the modal appearance, such as fading in or sliding down, using CSS transitions or keyframes.

## Things to Remember

- Using `position: fixed` ensures the modal stays in place over the content and `z-index` controls its stacking order over other page elements.
- The modal is centered using margin auto and a top percentage value. This method works well for various screen sizes but adjust as needed for specific design requirements.
- Ensure interactive elements like the close button are easily clickable and that modal functionality is intuitive for all users, including those using keyboards or screen readers.

This activity offers a practical approach to combining various CSS techniques to achieve a common web design pattern, enhancing user interaction and focus on specific content.
