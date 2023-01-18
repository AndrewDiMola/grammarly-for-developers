# Grammarly Text Editor SDK with suggestions config

This demo shows how to [mute categories of writing suggestions](https://developer.grammarly.com/docs/api/editor-sdk/editorconfig#suggestions) in the [Grammarly Text Editor SDK](https://developer.grammarly.com/).

## Try the demo

You can try the demo in [CodeSandbox](https://codesandbox.io/s/github/grammarly/grammarly-for-developers/tree/main/examples/editor-sdk-suggestions-config?file=/public/index.html).

## How it works

[index.html](./public/index.html) and the other HTML files in this repository contain `<div contenteditable>` elements. These elements are wrapped with the `<grammarly-editor-plugin>` web component so that Grammarly suggestions will be displayed in the specified text areas. 

HTML attributes on `<grammarly-editor-plugin>` toward the bottom of the file configure the Grammarly Text Editor SDK. See [index.html](./public/index.html) for the full code example.

## Get the code

A copy of this code is available in the [Grammarly for Developers GitHub repo](https://github.com/grammarly/grammarly-for-developers/tree/main/examples/editor-sdk-suggestions-config).

## Ask a question

If you want to ask a question, share a suggestion, or chat about how you're using the Grammarly Text Editor SDK in your application, join us in the [Grammarly for Developers Discussions](https://github.com/grammarly/grammarly-for-developers/discussions).
