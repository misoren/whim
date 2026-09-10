# Welcome to Whim!

# Overview
## Philosophy
- **For people who love colors** 🌈
	- Pick an accent color -> get a colorful theme with your chosen accent color as the primary color and a contrasting color for accents.
		- If you pick a low-saturation or dark color, the resulting palette won't be THAT colorful. It's up to you!
	- This doesn't use any specific, pre-documented way to choose colors that go well with the chosen accent color. I just eyeballed what looked good enough to me.
		- One optional snippet shifts the hues in the opposite direction from the accent color as the default theme approach.
		- Another optional snippet shifts the hues less.
- **For people who love doohickeys** ⚙️
- **Not minimalistic** 🌌
	- This theme was def not designed with minimalism in mind. You could *choose* to use it in a somewhat ~minimal fashion...but then why wouldn't you just use a different theme?
- **Large (~15mb last I checked)** 💪
- **Supports, dare I say, whimsy** 🪄
	- Make your notes as eye-pleasing or as eye-hurting as you want
	- Maybe evokes scrapbooking energy
	- Or something like updating your MySpace/Neopets/Gaia Online profile
	- Make your notes look wildly different from each other if you desire
	- Core aesthetic is mildly inspired by art nouveau and woodblock prints, but you can do some more cyber/neon-y type stuff too
- **Dark mode first** 🌃
	- There's a light mode, but YMMV with that fellow. It's far from fully tested, and some cssclasses, snippets, etc., will not play nice with light mode.
- **Desktop first** 🖥️
	- I use Obsidian mobile regularly, but this theme was not built for mobile use in particular, and mobile use hasn't been tested much yet. In my experience, this theme is *usable* on mobile, but many of its features do not work properly.
## Features
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
	- 20 new "content" callout types (like "place", "chef", and "ugh") and 14ish new "style" callout types (like "rainbow" and a selection of SVG illustrations)
- **Some callout property things**
	- Just drop the extra property strings into the callout type bit, like turn "[!note]" into "[!note.readout.white_text]" to apply the mysterious properties "readout" and "white_text"
- **More checkbox states than you'll be likely to use**
	- There's over 80, including things like a cat, a UFO, and a donut.
- **Does not use Style Settings**
	- As a personal user, I love Style Settings. But this theme was also made with plugins-off users in mind, e.g., me at work. I might add Style Settings support in the future? But if I do update this theme in the future, I hope to do so with a vanilla Obsidian experience in mind first.
- *OPTIONAL*: **Several snippets available for this theme**
	- Most won't work with other themes, but some might!
    - Includes whole-app background alternatives and animations, including some backgrounds that layer (e.g., image and pattern backgrounds generally layer with each other)
- *IN PROGRESS/PARTIAL*: **Mobile support**
	- It's not totally dysfunctional on mobile, but it definitely has some issues, and all the stuff looks better on desktop anyway probably.
- *DOCUMENTATION*: **There's an examples folder.**
- *OTHER STUFF*
	- Embedded notes are borderless and titleless
	- Bold, italics, strikethrough, and horizontal are colorful
        - ...at least in the main note body, in edit mode...
	- Different heading colors using the dynamic palette
- **No AI involvement**
	- I crafted this CSS the old-fashioned way: copying and pasting from other sources and tweaking with my own two hands. 
	- The themes Minimal, Nebulux, and Fancy-a-story were useful points of reference/education/information. I took the checkbox styling approach from Minimal directly, which I think should be okay? :-)

❗❗❗❗***ADD RAINBOW IMAGE***
## Themes I like that you might like
I made Whim for my own use, but if I didn't, I'd be using one of these:
- Fancy-a-story
- Retroma
- Underwater
- Ultra Lobster
- cranky goblin
- Nebulux

## Improbable Future Stuff
> or: what this theme does not do/do well atm
- Improve mobile support
- Improve read mode
- *MAYBE*: Improve light mode
	- Like updating "light" and "dark" in the note and callout styles to actually mean what those words mean
	- Like adding lighter versions of the BG illustrations and darker versions of the callout stamps
- *VERY MAYBE*: Style Settings support
- *VERY MAYBE*: Canvas stuff
- *VERY MAYBE*: Graph stuff?
- *VERY MAYBE*: Support for some popular plugins, if needed
- *MAYBE*: More callout styles and note cssclasses
- *MAYBE*: More snippets

# Extended Feature Info
> this section is very long probably

## Examples
⌛I'll be working on adding markdown examples to the examples folder.
TODO:
- [ ] A single note with every note class that you can drop into your vault to get the classes added to your cssclasses suggestions. Warning: this note will be painful to look at.
- [ ] An every-checkbox note
- [ ] An every-callout note
- [ ] Some BG pattern + animation combo examples
- [ ] ...*Probably others?*

## Callouts
### Vanilla
These are callout types in vanilla Obsidian that Whim overrides.

### Custom
These are callout types that Whim adds.

### Callout Styling
These are additional callout styles, similar to note classes, that Whim adds.

#### Callout Backgrounds
These are callout backgrounds, similiar to note classes, that Whim addes.

#### Other

## Checkboxes
Whim adds a lot of checkboxes.

## cssclasses
### Note Backgrounds
#### Basic / Patterns
#### Images
#### Colors
The backgrounds from the "Basic / Patterns" should *generally* respond to these color classes. Usually, ncolor classes will impact the main background color, and ndraw classes will impact any elements that appear drawn on top of the main background color.

#### Animations
Most backgrounds will respond to at least some of these animations.

### Filters
You can generally only apply one filter at a time.

### Horizontal Rules
#### Types
#### Styling

### Borders
#### Basic
#### From SVG

### Masks

### Other

## Snippets
> All current snippets may assume dark mode. That is, they may not work with light mode.

### Utility

### App Backgrounds
#### Filters
> Filter apply to the first layer.
#### First Layer (Bottom): Images / Gradients
#### Second Layer (Top): Patterns / Illustrations

### Other

