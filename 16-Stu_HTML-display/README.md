# 🐛 List Items and Boxes Are Not Displaying Correctly

Work with a partner to resolve the following issues:

* Users should be able to see a horizontal navigation bar with three list items side-by-side.

*Compared to display: inline, the major difference is that inline-block allows to set a width and height on the element. Also, with display: inline, top and bottom margins & paddings are not respected, and with display: inline-block they are.

* Users should be able to see three boxes.

* Users should be able to see the boxes centered and stacked on top of each other.

## Expected Behavior

* All three list items in the navigation bar should display inline.

* All three boxes should be visible. 

* Each box should appear centered and on its own line.

## Actual Behavior

* Each list item in the navigation bar displays on its own line.

* Two boxes are visible, and one is not displayed.

* The two visible boxes display inline and aligned to the left. 

## Assets

The following image demonstrates the web application's appearance and functionality:

![Three list items are displayed on the right side of the navigation bar, corresponding with three boxes centered on the page.](./assets/image-1.png)

---

## 💡 Hints

Which `display` value hides an element? 

display: none;

## 🏆 Bonus

If you have completed this activity, work through the following challenge with your partner to further your knowledge:

* What is the CSS `visibility` property? How is it different from the `display` property?

- display:none turns off the layout of the elements, so they are not rendered
- visibility:hidden hides the elements without changing their layouts
- opacity:0 causes the elements to be very transparent but users can still interact with them.

Use [Google](https://www.google.com) or another search engine to research this.

---
© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
