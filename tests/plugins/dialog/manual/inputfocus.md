@bender-tags: 2395, bug, 4.10.2
@bender-ui: collapsed
@bender-ckeditor-plugins: wysiwygarea, toolbar, link

1. Scroll down until editor is visible.
1. Press link button.

## Things to check:

### Touch devices:

- Play around focusing and blurring inputs, zooming and scrolling page.

#### Expected:

- When opening dialog or focusing input caret page should be scrolled in a way caret is visible.

#### Unexpected

- Caret is outside of current viewport.

### Desktop computers:

- Resize browser window.
- Resize dialog window.
- Drag dialog window.
- Close and reopen dialog.

#### Expected:

- When dialog is shown scrollbars are invisible.
- When resizing browser window dialog is still horizontally and vertically centered.
- When window too small to fit dialog window scrollbars should appear allowing to scroll dialog.
- Dialog window can be resized and dragged around.
- When closing and reopening dialog it has same size and position as it had before when it was closed.

Note: When you reposition dialog it won't be centered when resizing browser window.
