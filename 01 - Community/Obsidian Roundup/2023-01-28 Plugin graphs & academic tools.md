---
link: https://www.eleanorkonik.com/2023-01-28/
author: Eleanor Konik
published: 2023-01-28T13:30:01
publish: true
---

# 2023-01-28: Plugin graphs & academic tools
Tasks now supports custom statuses, table experiences are enhanced, & there are new tricks for emacs users.

## In The Community

* Here's a really neat [graph of plugins](https://observablehq.com/@mauforonda/state-of-obsidian-plugins) according to their popularity vs last update. "Copy button for code blocks" seems to have hit the sweet spot of being useful and easy to maintain. Here's an [accompanying writeup](https://mauforonda.github.io/garden/notes/state-of-obsidian-plugins/).
* Here's a totally different [graph of plugins](https://nevernotmove.github.io/obsidian-stats/) focused on a variety of stats, but the most popular use-case is that it lets users sort by different criteria, for example downloads over time.
* Here's a recording of a talk given to a Meetup group about how Erik Aybar uses [Obsidian & ChatGPT as a software engineer](https://www.youtube.com/watch?v=wULSqH1M-xw&t=665s). It touches on Excalidraw, PARA, Canvas, project logs, and more.

## Plugin News

### New in Community Plugins

_These plugins went through code review and are now available in Obsidian's plugin list._

* [The One Ring 2E Statblocks](https://github.com/modality/obsidian-the-one-ring-2e-statblocks) by `@modality`  lets tabletop roleplayers render TOR 2e statblocks in Obsidian.
* [Image Captions](https://github.com/alangrainger/obsidian-image-captions) by `@alangrainger`  adds captions to images when there is alt-text specified
* [Canvas Conversation](https://github.com/AndreBaltazar8/obsidian-canvas-conversation) by `@AndreBaltazar8`  lets users create a ChatGPT conversation using Canvas Cards.
* [Plugin Groups](https://github.com/Mocca101/obsidian-plugin-groups) by `@Mocca101`  makes it easier to enable and disable multiple plugins through a single command, or delay the startup of plugins to speed up your Obsidian start up time.
* [IVRE](https://github.com/ivre/obsidian-ivre-plugin) by `@p-l-`  is an IVRE integration for Obsidian that can grab data from IVRE and brings it into Obsidian notes, which is useful for pentesters and red team hackers.

### Pending (as of Friday morning)

_Note: Not all new plugins are available in the community list yet, as they need to go through code review first. You can manually install plugins that aren't in the community list yet by using the [Beta Reviewer's Auto-update Tool](https://github.com/TfTHacker/obsidian42-brat). Note, though, that this is not as safe as waiting for them to go through code review._

* [Flomo Importer](https://github.com/jia6y/flomo-to-obsidian) by `@jia6y`  lets users make Flomo Memos to Obsidian Notes
* [Adamantine Pick](https://github.com/notlibrary/obsidian-adamantine-pick) by `@notlibrary`  renders embeddable [Pikchr](https://pikchr.org) diagrams.
* [Advanced Close Tab](https://github.com/hdykokd/obsidian-advanced-close-tab) by `@hdykokd`  prevents pinned tabs and the last tab in pane from being closed.
* [Double Colon Conceal](https://github.com/msrch/obsidian-double-colon-conceal) by `@msrch`  will display double colons (i.e.e Dataview inline attributes) as a single colon in reading view (preview mode) for more natural experience.
* [S3 Image Uploader](https://github.com/jvsteiner/s3-image-uploader) by `@jvsteiner`  is an ad-supported plugin that lets users self host images on AWS s3.
* [Codeblock Customizer](https://github.com/mugiwara85/CodeblockCustomizer) by `@mugiwara85`  lets you customize your codeblocks.
* [Pivotal Tracker Integration](https://github.com/JonnyDeates/obsidian-pivotal-tracker-integration-plugin) by `@JonnyDeates`  allows the user to pull stories, chores, bugs from their pivotal tracker counterpart.
* [Custom Classes](https://github.com/LilaRest/obsidian-custom-classes) by `@LilaRest`  is a minimalist plugin that allows you to add custom HTML classes to markdown blocks.
* [Extra Styles](https://github.com/ironfroggy/obsidian-extra-styles-plugin) by `@ironfroggy`  adds custom text styling with markdown syntax.
* [Scratch Pad](https://github.com/ocubist/obsidian-scratch-pad) by `@ocubist`  provides functionality to auto-delete notes that match specific patterns.
* [Awesome Reader](https://github.com/AwesomeDog/obsidian-awesome-reader) by `@AwesomeDog`  improves the reading experience for epub and PDF.
* [Vextab](https://github.com/luigman/obsidian-vextab) by `@luigman`  is for writing and displaying music notation using the Vextab API. There's [more information about it](https://www.reddit.com/r/ObsidianMD/comments/10j13cu/i_created_an_obsidian_plugin_for_rendering_guitar/) on Reddit, along with some examples.
* [Canvas Filter](https://github.com/IKoshelev/Obsidian-Canvas-Filter) by `@IKoshelev`  filters Canvases to only show items of specific color, tags or only connected to currently selected node.
* [Note aliases](https://github.com/pulsovi/obsidian-note-aliases) by `@pulsovi`  manages aliases of notes in Obsidian.
* [Text Wrapper](https://github.com/smx0/obs-text-wrapper) by `@smx0`  lets users quickly wrap selected text with HTML tags by using a shortcut or from the command palette
* [Tag Search](https://github.com/rwblickhan/obsidian-tag-search) by `@rwblickhan`  lets you fuzzy-find your tags!
* [Kill and Yank](https://github.com/inouetakuya/obsidian-kill-and-yank) by `@inouetakuya`  enables kill and yank (a la Emacs) in the editor.

### Updates

_If you want a comprehensive list of what plugins updated this week, check out this [plugin updates index](https://obsidian-plugin-stats.vercel.app/updates) by Ganessh Kumar._

* [Excalidraw 1.8.11](https://t.co/jX6FHU4kxt) includes YouTube thumbnails, mouse wheel and pinch zoom settings, images from URLs that aren't in  your vault. Also, the Set Grid script now remembers the previous grid setting.
* Mkdocs Publisher users should check out this [update announcement in Discord](https://discord.com/channels/686053708261228577/855181471643861002/1066144217182785596) about a new repository for tracking essential files, and a helpful new Github action.
* [Metadata Menu 0.4.11](https://github.com/mdelobelle/metadatamenu) revamped its auto suggester, now displays empty fields as blank instead of null, and more.
* The [Obsidian RTL plugin](https://github.com/esm7/obsidian-rtl) now fully supports per-line (auto/dynamic) text direction.
* [Tasks 1.23.0](https://github.com/obsidian-tasks-group/obsidian-tasks/releases/tag/1.23.0) now supports custom statuses. There's more information in [the documentation](https://obsidian-tasks-group.github.io/obsidian-tasks/getting-started/statuses/#done-date-recurrence-and-statuses) about how to make sure done dates are correctly handled.

### Betas

_Note: these plugins have not yet been submitted for code review, and are being made available primarily for testing purposes._

* [Table Enhancer v0.5.2](https://github.com/Stardusten/ob-table-enhancer) lets users generate a table with a specified shape, edit cells by clicking them, and generally manipulate tables without interacting with the code.

## Ancillary Code

* Here's a [python script to make batch edits to metadata](https://www.reddit.com/r/ObsidianMD/comments/10izlby/python_script_to_make_batch_updates_to_obsidian/)  using the command line.
* Here's a [dataviewjs snippet to display 4 random notes with a particular tag](https://discord.com/channels/686053708261228577/710585052769157141/1065956866988974110) (Discord).

## Guides

* This is a fantastic 20 page write-up from Dr. Andy Roddick about [note taking and Obsidian](https://docs.google.com/document/d/1365bPgh4iv-MciZx9BiguCJRJo-D3Zh7J_mrT-_Ws6g/edit) aimed at his Anthropology students but just a generally wonderful comprehensive guide.
* This is one of the best explanations I've seen so far of exactly what [the make.md plugin does](https://beingpax.medium.com/make-md-the-most-beginner-friendly-plugin-for-obsidian-6e521769d6e0).
* Here's how to [set up a Chromebook](https://reddit.com/r/ObsidianMD/comments/10jvxsl/how_to_setup_high_ram_vaults_on_chrome_os/) to switch between the Android Obsidian app for tablet/touchscreen/stylus stuff and the Linux Obsidian app for laptop/keyboard/mouse stuff.
* Here's how to get [LaTeX like figures and section referencing](https://www.reddit.com/r/ObsidianMD/comments/10lp7e0/latexlike_figures_and_section_referencing_in/), similar to how citations work in Pandoc, which is particularly useful for academics. You can also use it to reference equations.
* Also particularly useful for academics, here's a new (up to date) guide for how to [connect Zotero to Obsidian](http://gizn.org/notes/2023/01/20/how-to-connect-zotero-with-obsidian.html), using the Zotero Integration plugin for Obsidian and Better BibTeX for Zotero. The accompanying [Reddit discussion](https://www.reddit.com/r/ObsidianMD/comments/10k2pl2/how_to_connect_zotero_with_obsidian/) has some additional tips, as well.
* In a similar vein, here's a [demo vault for academics](https://github.com/rlaker/Obsidian-for-Academia) that also explains how to use Zotero, along with git and Obsidian in general. It's aimed at the author's research group who are new to Obsidian.

## Discussions

* This discussion of [atomic notes](https://www.reddit.com/r/ObsidianMD/comments/10jsrma/the_leap_into_atomic_notes/) was short but had some really insightful commentary about the relative value of atomicity and linking vs. doing what feels natural and then searching.
* This discussion of [how to organize lecture notes](https://www.reddit.com/r/ObsidianMD/comments/10jltrh/those_that_use_obsidian_for_taking_notes_in_class/) was very insightful.
* There was a nice discussion on pkm.social about Curtis McHale's admonishment to [take fewer, better notes](https://pkm.social/@donovanpalmer/109750814606005859). It reminded me that I haven't taken very many notes at all in the last six months... but my Obsidian vault has still been as useful as ever, because I've still been able to write despite a severe dip in my productivity thanks to being utterly exhausted by my pregnancy.

## Showcases

* Here's how `u/Level82` uses Obsidian to track information about [foraging and fermentation](https://www.reddit.com/r/ObsidianMD/comments/10i8v8v/another_fun_usecase_fermentation_and_foraging/).
* Here's a [weekly review template](https://www.reddit.com/r/ObsidianMD/comments/10l3axw/weekly_review_template_loosely_based_on_second/) based on "Getting Things Done" and "Building a Second Brain."
* Here's a [system to capture, organize, prioritize and execute](https://techblog.commercetools.com/a-systematic-approach-to-organizing-yourself-with-obsidian-944d9d1cf98f) work, focused on task management.

%% Hub footer: Please don't edit anything below this line %%

# This note in GitHub

<span class="git-footer">[Edit In GitHub](https://github.dev/obsidian-community/obsidian-hub/blob/main/01%20-%20Community/Obsidian%20Roundup/2023-01-28%20Plugin%20graphs%20%26%20academic%20tools.md "git-hub-edit-note") | [Copy this note](https://raw.githubusercontent.com/obsidian-community/obsidian-hub/main/01%20-%20Community/Obsidian%20Roundup/2023-01-28%20Plugin%20graphs%20%26%20academic%20tools.md "git-hub-copy-note") | [Download this vault](https://github.com/obsidian-community/obsidian-hub/archive/refs/heads/main.zip "git-hub-download-vault") </span>
