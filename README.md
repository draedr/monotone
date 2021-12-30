# monotone
monotone is a solo.to clone made with eleventy and tailwindcss.
It doesn't use javascript, and can be managed completely by modifying the config json via an headless cms like forestry!

## Settings

### `app.json`
---

> `name`: Your name!
>
> `location`: Your address
>
> `bio`: Your bio
>
> `theme`: something
>   > `color`: Color to use for icons and default backgrounds
>   >
>   > `background`: Background image for the header
>   >
>   > `footer`: Should the footer be displayed?
>   >
> `content`: A list of links
>
> `contacts`: A list of contacts
>

### `links`
---
> `content`: A list of objects
>   > `url`: The url of the link, required
>   >
>   > `invert`: Should the image' colors be inverted? defaults to 'false'
>   >
>   > `preset`: A preset from presets.json, defaults to 'default'
>   >
>   > `type`: The type of content. EIther section, embed or link. Defaults to link
>   > 
>   > `title`: Title of the section. defaults to none
>   >

### `contacts`
---
> `contacts`: A list of objects
>   > `icon`: The icon to use. required
>   >
>   > `name`: The name to show. required
>   >
>   > `uri`: The uri to link, comprising of protocol