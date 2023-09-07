# Mellow Modal

Hello everyone,
Mellow Modal is a modal creation tool. On advanced systems, it makes more sense in terms of performance to recreate the bootstrap modals in the DOM instead of constantly adding them to the page. But it takes a lot of code to create a modal every time, and it's really cumbersome.

If you are using bootstrap modals in your project, the fastest and easiest way to create a modal is with Mellow Modal.

# Install

Mellow Modal is very simple to install. You can easily install it with the help of NPM:
```
npm i mellow-modal
npm install
```
or you can add the library directly to your project.
```
<script src="/path/your/folder/mellow-modal.js"></script>
```

# Usage

Mellow Modal is very easy to start. You can init with a single command
```
const modal = new MellowModal;
modal.fire();
```
this way, you can start a quick modal. By default a modal will be initialized.

You can add certain parameters in `JSON` format to design your modals.

# Parameters

| Parameter | Type | Default | Detail|

# Parameter Examples


Lets you specify an `id` for the modal.
```
modal.fire({
  /* ... */
  id : "exampleModal",
  /* ... */
});
```
------------------------------------------

Allows you to change the dimensions of the modal. `modal-sm`, `modal-md` or `modal-lg`. Default is `modal-md`

```
modal.fire({
  /* ... */
  size : "modal-lg",
  /* ... */
});
```
------------------------------------------

prevents the modal from closing when clicking outside the modal or pressing the `ESC` key. Default is `false`

```
modal.fire({
  /* ... */
  backdrop : true,
  /* ... */
});
```
------------------------------------------

In the upper right corner of the modal, it shows the close modal button. Default is `true`

```
modal.fire({
  /* ... */
  showCloseButton : true,
  /* ... */
});
```
------------------------------------------

Adds a title for the modal.

```
modal.fire({
  /* ... */
  title : "Example Modal Title",
  /* ... */
});
```
------------------------------------------

Shows or hides the Modal Header. Default is `true`

```
modal.fire({
  /* ... */
  header : true,
  /* ... */
});
```
------------------------------------------

Shows or hides the Modal Footer. Default is `true`

```
modal.fire({
  /* ... */
  footer : true,
  /* ... */
});
```
------------------------------------------

Adds confirmation button to Modal Footer. Default is `true`

```
modal.fire({
  /* ... */
  showConfirmButton : true,
  /* ... */
});
```
------------------------------------------

Sets the style of the confirmation button. Check Bootstrap Colors for other styles. Default `success`

```
modal.fire({
  /* ... */
  confirmButtonType : "primary",
  /* ... */
});
```
------------------------------------------

Sets the text of the confirmation button. Default `Confirm`

```
modal.fire({
  /* ... */
  confirmButtonText : "Save",
  /* ... */
});
```
------------------------------------------

Adds different buttons to Modal Footer.

```
modal.fire({
  /* ... */
  buttons : "<button type="button" class="btn btn-primary">Primary</button>",
  /* ... */
});
```
------------------------------------------

Adds HTML format content to Modal Content.

```
modal.fire({
  /* ... */
  content : '<p>This is the content of the modal.</p>',
  /* ... */
});
```
------------------------------------------

Lets you define a custom class for the modal's opening animation. Default `Fade`

```
modal.fire({
  /* ... */
  animation : 'custom-animation-class',
  /* ... */
});
```
------------------------------------------

Starts the modal in full screen. Disables the `size` parameter. Default `false`

```
modal.fire({
  /* ... */
  allowFullscreen : true,
  /* ... */
});
```
------------------------------------------

lets you add custom css for the overall modal.

```
modal.fire({
  /* ... */
  css : 'background:red',
  /* ... */
});
```
