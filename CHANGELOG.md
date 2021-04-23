# v1.3.0
Some minor adjustments, changes, and fixes.
- No longer using `@mixins` for os types, made the switch over to `@each` as it's easier to manage with OS types.
- Did a bit of tinkering and redid some things, should be less scuffed.
- Fixed some z-index issues (scuffed way tho cause im too lazy to figure out an actual way). This should resolve part of [issue #5](https://github.com/Discord-Theme-Addons/revamped-userarea/issues/5).
- Some file structure reconstructing.
- Misc changes to the repo itself to make it look a tad bit nicer.

# v1.2.6
Fixes for where the unread ping indicator wouldn't be positioned properly.

# v1.2.5
Fixes for when the BD notice pops up for an update.

# v1.2.4
I really need to learn how to NOT push changes unless I'M CERTAIN that shit is actually completely fixed.. 
- Fixed where on web the height of the name tag container would be 2px too short.
- Made width for name tag container a bit longer.

# v1.2.3
Positioning fixes for different operating system types.

# v1.2.2
Positioning fix for the status picker.

# v1.2.1
Added a separator below the user's avatar.

# v1.2.0
Recently I have recoded this to use SCSS, mainly for maintainability ~~(and the sake of my sanity).~~ Some other changes are:
- Bottom Bar support is basically gone (or well I won't be maintaining the branch anymore) because I'm too lazy to.
- Fixed where you couldn't quick clear your status.
- Readded back where the name tag would show next to the action buttions. NOTE: You will no longer be able to copy your username.
- Some position adjustmets + cleaner code.