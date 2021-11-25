# Version 1.4.0 - 11/24/2021
- Using a better method for when userarea buttons and nametag shows (aka when you hover on your avatar). This closes **[pull #9](https://github.com/Discord-Theme-Addons/compact-userarea/pull/9)**.
- Changes to the status picker for it to function better when interacting.
- Some minor modifications for better theme compatibility (hopefully). This closes **[issue #7](https://github.com/Discord-Theme-Addons/compact-userarea/issues/7)**.
- Some file structure changes.
- README asset updates.

<details>
<summary><b> Version 1.3.2 </b></summary>

- A minor rework to use the entire userarea instead of moving things each by each, which helps clean the code for specific os types.
- When you hover on your avatar, the buttons now have a popout animation.
- All animations can now be found in `./src/main/_animations.scss`.
- Some more code "cleanup."
</details>

<details>
<summary><b> Version 1.3.1 </b></summary>

Better native support for [Bottom Bar](https://github.com/Discord-Theme-Addons/bottom-bar) for the recent rework.
</details>

<details>
<summary><b> Version 1.3.0 </b></summary>

- No longer using `@mixins` for os types, made the switch over to `@each` as it's easier to manage with OS types.
- Did a bit of tinkering and redid some things, should be less scuffed.
- Fixed some z-index issues (scuffed way tho cause im too lazy to figure out an actual way). This should resolve part of [issue #5](https://github.com/Discord-Theme-Addons/revamped-userarea/issues/5).
- Some file structure reconstructing.
- Misc changes to the repo itself to make it look a tad bit nicer.
</details>

<details>
<summary><b> Version 1.2.6 </b></summary>

Fixes for where the unread ping indicator wouldn't be positioned properly.
</details>

<details>
<summary><b> Version 1.2.5 </b></summary>

Fixes for when the BD notice pops up for an update.
</details>

<details>
<summary><b> Version 1.2.4 </b></summary>

I really need to learn how to NOT push changes unless I'M CERTAIN that shit is actually completely fixed.. 
- Fixed where on web the height of the name tag container would be 2px too short.
- Made width for name tag container a bit longer.
</details>

<details>
<summary><b> Version 1.2.3 </b></summary>

Positioning fixes for different operating system types.
</details>

<details>
<summary><b> Version 1.2.2 </b></summary>

Positioning fix for the status picker.
</details>

<details>
<summary><b> Version 1.2.1 </b></summary>

Added a separator below the user's avatar.
</details>

<details>
<summary><b> Version 1.2.0 </b></summary>

Recently I have recoded this to use SCSS, mainly for maintainability ~~(and the sake of my sanity).~~ Some other changes are:
- Bottom Bar support is basically gone (or well I won't be maintaining the branch anymore) because I'm too lazy to.
- Fixed where you couldn't quick clear your status.
- Readded back where the name tag would show next to the action buttions. NOTE: You will no longer be able to copy your username.
- Some position adjustmets + cleaner code.
</details>