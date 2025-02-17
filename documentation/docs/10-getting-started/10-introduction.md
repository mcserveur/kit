---
title: Introduction
---

## Before we begin

> If you're new to Svelte or SvelteKit we recommend checking out the (experimental!) [interactive tutorial](https://learn.svelte.dev).
>
> If you get stuck, reach out for help in the [Discord chatroom](https://svelte.dev/chat).

## What is SvelteKit?

SvelteKit is a framework for rapidly developing robust, performant web applications using [Svelte](https://svelte.dev/).

## What is Svelte?

In short, Svelte is a way of writing user interface components — like a navigation bar, comment section, or contact form — that users see and interact with in their browsers. The Svelte compiler converts your components to JavaScript that can be run to render the HTML for the page and to CSS that styles the page. You don't need to know Svelte to understand the rest of this guide, but it will help. If you'd like to learn more, check out [the Svelte tutorial](https://svelte.dev/tutorial).

## What does SvelteKit provide on top of Svelte?

Svelte renders UI components. You can compose these components and render an entire page with just Svelte, but you need more than just Svelte to write an entire app.

SvelteKit provides basic functionality like a [router](/docs/glossary#routing) — which updates the UI when a link is clicked — and [server-side rendering (SSR)](/docs/glossary#ssr). But beyond that, building an app with all the modern best practices is fiendishly complicated. Those practices include [build optimizations](https://vitejs.dev/guide/features.html#build-optimizations), so that you load only the minimal required code; [offline support](/docs/service-workers); [preloading](/docs/link-options#data-sveltekit-preload-data) pages before the user initiates navigation; [configurable rendering](/docs/page-options) that allows you to render different parts of your app on the server with [SSR](/docs/glossary#ssr), in the browser [client-side rendering](/docs/glossary#csr), or at build-time with [prerendering](/docs/glossary#prerendering); and many other things. SvelteKit does all the boring stuff for you so that you can get on with the creative part.

It uses [Vite](https://vitejs.dev/) with a [Svelte plugin](https://github.com/sveltejs/vite-plugin-svelte) to provide a lightning-fast and feature-rich development experience with [Hot Module Replacement (HMR)](https://github.com/sveltejs/vite-plugin-svelte/blob/main/docs/config.md#hot), where changes to your code are reflected in the browser instantly.
