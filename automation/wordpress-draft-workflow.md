# WordPress Draft Workflow

Purpose:

Create or update WordPress content safely.

## Rules

- Create drafts first.
- Do not publish automatically.
- Do not change pricing, legal text or live offers without review.
- Do not delete WordPress content.
- Do not expose Application Passwords.
- Keep secrets outside the repo.

## Current WordPress Page Source

Local source:

`wordpress-drafts/free-pwchi-demo-pack-page.html`

Recommended WordPress title:

`Free Pwchi Demo Pack`

Recommended slug:

`free-pwchi-demo-pack`

## WPCoder Pro Usage

If using WPCoder Pro:

1. Move CSS from the page into a WPCoder CSS snippet.
2. Keep the HTML structure in the WordPress page or shortcode.
3. Keep class names scoped under `.pwchi-demo-page`.
4. Test mobile layout after every major edit.

## REST API Usage

REST API can be used for:

- listing pages
- listing media
- creating draft posts
- creating draft pages
- updating drafts

REST API should not be used for:

- publishing without review
- deleting content
- changing user accounts
- changing plugin settings

