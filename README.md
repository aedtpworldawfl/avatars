# avatars
# Chataropica

| Field | Value |
| --- | --- |
| title | CHATAROPICA |
| image | ![](https://aedtpworld.neocities.com/icons/chataropica.png) |
| caption | Chataropica — Chat everyday with friends and families |
| Type | Instant messaging application, Chat Application, Website |
| Developer | AEDTP WORLD |
| Parent | AEDTP WORLD |
| Initial release | 2026 |
| Stable version | 1.0.0.0 |
| Platforms | Android (com.aedtpworld.chataropica), Windows |
| Application Name | Chataropica |
| License | Freeware |
| Base URL | https://aedtpworld.com/chat/ |
| Login URL | https://aedtpworld.com/chat/login.php |
| Register URL | https://aedtpworld.com/chat/register.php |
| Forgot URL | https://aedtpworld.com/chat/forgot.php |
| Website | https://aedtpworld.com/chat/ |
| Description | Chataropica: Chat everyday with friends and families, artists, business and loved ones, Connect with the world |
| Brand Colors | #0052FF brandblue, #FFD60A brandyellow |
| Theme | Day and Night toggle with localStorage chataropica_theme |
| Manifest | https://aedtpworld.com/chat/manifest.json |



**CHATAROPICA** is an instant messaging application developed by **AEDTP WORLD**. The software is primarily distributed as an application for Android and Windows, with additional access provided via a web interface, comparable to the distribution model of Facebook.

## Overview

**CHATAROPICA** allows users to chat everyday with friends and families, artists, business and loved ones. It connects users with the world. User accounts are categorized as personal, business, or artist.

Messaging is initiated through username-based URLs in the format [Chat With Username](https://aedtpworld.com/chat/index.php?with=username).

## Interface

The Chats interface is accessible only to logged-in users. The header contains the Chataropica logo and a count of users currently online.

## Features

* One-to-one direct messaging
* Inline text formatting including bold, italics, strikethrough, and lists
* Automatic hyperlinking of https URLs
* @username mentions that link to user profiles
* Verification badges: green for personal, black for business, blue for artist
* Day and night themes
* Avatar images set via external URLs; file uploads are not supported

## Login Page

* **Title** — Log In - Chataropica
* **Header Logo** — ![](https://aedtpworld.com/icons/chataropica.png) — 100x100 rounded-2xl
* **Heading** — Chataropica — text-brandblue dark:text-brandyellow
* **Subheading** — Welcome back
* **Form Method** — POST
* **Form Action** — [Login Action](https://aedtpworld.com/chat/login.php)
* **CSRF Token** — Hidden input name csrf
* **Username Field** — name username, required, autofocus
* **Password Field** — name password, required
* **Submit Button** — Log In — bg-brandblue dark:bg-brandyellow
* **Links** — [Forgot password](https://aedtpworld.com/chat/forgot.php) and [Sign up](https://aedtpworld.com/chat/register.php)
* **Footer** — Chataropica • © AEDTP WORLD

## Technical Details

* **Tailwind Config** — darkMode class, colors brandblue #0052FF, brandyellow #FFD60A
* **Theme Script** — Reads localStorage chataropica_theme default day, if night adds dark class to documentElement
* **Toggle Button** — Fixed top-4 right-4 text-2xl, themeIcon 🌙, onclick toggleTheme()
* **Assets** — /root/css/ads.css, /chat/assets/app.js
* **Classes** — app-transition bg-white dark:bg-black text-gray-900 dark:text-white min-h-screen flex flex-col
* **Input Style** — w-full border rounded-lg p-2 dark:bg-gray-900 dark:border-gray-700 focus:ring-2 focus:ring-brandblue

## SEO and Meta

* **Description** — Chataropica: Chat everyday with friends and families, artists, business and loved ones, Connect with the world
* **OG Site Name** — Chataropica
* **OG Title** — Chataropica
* **OG Image** — ![](https://aedtpworld.com/icons/chataropica.png)
* **Twitter Card** — summary
* **Icon** — ![](https://aedtpworld.com/icons/chataropica.png)

## External Links

* [Chataropica Official](https://aedtpworld.com/chat/)
* [Log In](https://aedtpworld.com/chat/login.php)
* [Sign Up](https://aedtpworld.com/chat/register.php)
* [Forgot Password](https://aedtpworld.com/chat/forgot.php)
* [Chataropica Icon](https://![](images/aedtpworld.com/icons/chataropica.png))
* [AWFL Meta](https://![](images/aedtpworld.com/icons/awflmetaawfl.jpg))

[Category:AEDTP WORLD](https://aedtpworld.com/wikiworld/index.php/Category%3AAEDTP_WORLD)
[Category:Technology](https://aedtpworld.com/wikiworld/index.php/Category%3ATechnology)
