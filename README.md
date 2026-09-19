# Welcome to Whim!
---
![elegant whim](screenshots/whim0.png)
> This is a note made purely from elements included with Whim.
---
![basic whim](screenshots/whim.png)
> Vanilla Whim
---
![fancy whim](screenshots/whim5.png)
> Whim dressed up
---
![cute whim](screenshots/whim7.png)
> Whim with a cute note (snippets-or-Style Settings must be used for some of what's pictured for cuteness)
---
# Overview
- **For people who love colors** 🌈
	- Pick an accent color -> get a colorful theme with your chosen accent color as the primary color and a contrasting color for accents.
		- If you pick a low-saturation or dark color, the resulting palette won't be THAT colorful. And there's snippets/settings/cssclasses for making things grayer. It's up to you!
	- This doesn't use any specific, pre-documented way to choose colors that go well with the chosen accent color. I just eyeballed what looked good enough to me.
		- One optional snippet shifts the hues in the opposite direction from the accent color as the default theme approach.
		- Another optional snippet shifts the hues less.
- **For people who love doohickeys** ⚙️
- **Not minimalistic** 🌌
	- This theme was def not designed with minimalism in mind. You could *choose* to use it in a somewhat ~minimal fashion...but then why wouldn't you just use a different theme?
- **Supports, dare I say, whimsy** 🪄
	- Make your notes as eye-pleasing or as eye-hurting as you want
	- Maybe evokes scrapbooking energy
	- Or something like updating your MySpace/Neopets/Gaia Online profile
	- Make your notes look wildly different from each other if you desire
	- Core aesthetic is inspired by art nouveau and woodblock prints, but you can do some more cyber/neon-y type stuff too
- **Dark mode first** 🌃
	- There's a light mode, but YMMV with that fellow. It's far from fully tested, and some cssclasses, snippets, etc., will not play nice with light mode.
- **Desktop first** 🖥️
	- I use Obsidian mobile regularly, but this theme was not built for mobile use in particular, and mobile use hasn't been tested much yet. In my experience, this theme is *usable* on mobile, but many of its more fun features do not work properly.
- **Large (~15mb last I checked)** 💪
---
![basic whim](screenshots/whim6.png)
> Whim of two worlds: the future (simple scanline effect) and the past (combo embossing effect)
---
![space whim](screenshots/whim8.png)
> Whim thinking about space (snippets-or-Style Settings must be used for some of what's pictured for space thoughts)
---
![powerful whim 1](screenshots/whim2.png)
![powerful whim 2](screenshots/whim3.png)
![powerful whim 3](screenshots/whim4.png)
> Whim that has been training for 1000 years (in three accent color examples)
---
![vintage whim](screenshots/whim9.png)
> Whim feeling old-fashioned, or perhaps in half-mourning
---
![pop whim](screenshots/whim10.png)
> Whim influenced by pop art
---
# Features
- **MANY CSS classes**
	- Like, so many. This theme aspires to have a whole taxonomy for you to apply at will to your cssclasses note property
	- You'll find:
		- Note backgrounds
			- Gradients, blur, patterns, a selection of SVG illustrations
		- Background animations
		- Borders
		- Variety of heading fonts
		- Horizontal rule styles
		- Glowiness
		- Frame shadows
		- Vignettes?
		- Scanlines?
		- Color filters
		- Several blend modes
			- Most of which are functionally useless!
			- But maybe you'll find a use!
		- Spinning chicken* mode
			- * only spins the note for even cooking, no chickens harmed or rotated
- **New callout types**
	- Many new "content" callout types (like "place", "chef", and "ugh") and "style" callout types (like "rainbow" and a selection of SVG illustrations)
	- I'm probably not going to keep these images up-to-date if I add more, so check the docs for a full list! Or if the docs aren't updated, then...read the theme.css. :-)
---
![default callouts](images/default_callouts.png)
> The default callouts
---
![default callouts](images/custom_callouts.png)
> The custom callouts
---
- **Callout modifiers/properties/"classes"**
	- Just drop the extra property strings into the callout type bit--like turn "[!note]" into "[!note.readout.white_text]" to apply the mysterious properties "readout" and "white_text"
---
![callout style](images/callout_styles.png)
> A few examples of extra callout modifiers/styles/properties/whatever
---
- **More checkbox states than you'll be likely to use**
	- There's over 80, including things like a cat, a UFO, and a donut.
	- I'm probably not going to keep this image up-to-date if I add more, so check the docs for a full list! Or if the docs aren't updated, then...read the theme.css. :-)
---
![checkboxes](images/checkboxes.png)
> The many checkboxes of Whim
---
- **Style Settings = snippets**
	- As a personal user, I love Style Settings. But this theme was also made with plugins-off users in mind, e.g., me at work. I've endeavored to make nearly everything you can do in Style Settings with this theme available via snippets as well.
		- An exception to this currently is the mask/"emboss" setting in Style Settings.
- *OPTIONAL*: **Several snippets available for this theme**
	- Many won't work with other themes, but some might!
    - Includes whole-app background alternatives and animations, including some backgrounds that layer (e.g., image and pattern backgrounds generally layer with each other, with the pattern overlaying the image)
	- Many snippets are equivalent to Style Setting options, but some offer additional SVG illustrations not included in the main theme, to keep the theme.css file size at least a *little* smaller...
- *DOCUMENTATION*: There's an [examples](docs/examples/) folder and sections documenting available cssclasses, etc., in the [docs](docs/) folder.
	- [cssclasses](docs/docs/)
	- [callouts](docs/docs/)
	- [snippets](docs/docs/)
- *OTHER STUFF*
	- Embedded notes are borderless and titleless
	- Bold, italics, strikethrough, and highlight are colorful
        - ...at least in the main note body, in edit mode...other contexts' may not be yet.
	- Different heading colors using the dynamic palette
- **No AI involvement**
	- I crafted this CSS the old-fashioned way: writing and rewriting my own amateur CSS, with frequent lookin' up of stuff on the internet. As far as I know, none of the images and SVGs included in the theme proper or in the snippets folder were created with or modified by AI.

![blaaa](images/blaaa.png)
> Whim's creation

# Themes I like that you might like
I made Whim for my own use, but if I didn't, I'd be using one of these:
- Fancy-a-story
- Retroma
- Underwater
- Ultra Lobster
- cranky goblin
- Nebulux

The themes Minimal, Nebulux, and Fancy-a-story were useful points of reference/education/information. I took the checkbox styling approach from Minimal directly, which I think should be okay? :-)

# Improbable Future Stuff
> or: what this theme does not do/do well atm
- I may become convinced to make the scrollbars easier to see. Until then, there's a snippet available.
- Improve mobile support
- Improve read mode
- *MAYBE*: More callout styles, note cssclasses, junk like that
- *MAYBE*: More snippets
- *VERY MAYBE*: Improve light mode
- *VERY MAYBE*: Canvas stuff
- *VERY MAYBE*: Graph stuff?
- *VERY MAYBE*: Support for some popular plugins
