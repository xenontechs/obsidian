
Xenos markdown stuff
# CSS snippets
sorted by Library, Format (in-editor things), Navigation (out of editor, navigation pane, similar)

there is so much to do here that I would love to say "stick your issues to a certain dark place" but I'm too happy about feedback to do so, so throw things may way in any shape or form. I didn't get to create a "list of issues" yet, but possibly soon™

## "library" snippets
they essentially exist to sort things to have variables for other places, in hopes it makes things easier. at this scale it probably doesn't, but I did it anyways. 

it is probably safe to add them regardless of which other things to pick.

### colorreference.css
just a bunch of colors, for "well known" brands/products/whatever. think about that "twitch" purple for example. 

### lucide-icons.css
terrible name, but that was the pursued purpose at the moment. onsidian ships with lucide, so I would like to stick to that library, but it's not freely referencable yet, so the icons go there as hardcoded svg for backgrounds(mostly)

hope is that obsidian changes icons to be grlobally addressed, then this can be "iconreference.css" as it should be, or DIAF

## Format snippets
whatever makes the .md more pretty. also extends features (more variants of things), I need to re-think all naming...

### callouts.css
- uses colorreference.css
adds additional callouts. at the moment:
**General**
- safety
- tool
- link
- iframe

**games**
- game
- eveonline
- factorio

**pride**
- pride
- transgender
- nonbinary
- agender
- asexual
- lesbian

### task-states.css
- uses lucide-icons.css

adds more task states:
- [-] cancelled/non-task
- [>] deferred/scheduled
- [?] question
- [!] important
- [/] in progress
- [t] delayed/backlog

### link-icons
- uses lucide-icons.css

replaces default "external link" icon with more fitting one if it matches. links to github get github logo

### mermaid.css
everything about this is unclear as it's been multiple minutes since I messed with mermaid.

### slide fixes
everything about this is unclear as it's been multiple minutes since I messed with ~~mermaid~~ _slides_.

## Navigation
targets the navigation pane (and possibly other areas of the client soon™)

### fileexplorer-hidden-items.css
hides certain folders, in this case every folder starting with an underscore (that's where I keep configuration files, templates, ...). you can always get access to them by disabling the snippet. they are just hidden from view, all other functions still work as expected

### folder-icons.css
- uses colorreference.css but you want to customize it anyways

using the "icon folder" plugin? here's where you can add colors to the icons based on folder name

