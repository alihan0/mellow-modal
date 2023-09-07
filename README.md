# mellow-modal

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
