# Novelist Concept

This repository is meant to be a development guide, roadmap and meta-issue tracker for the `novelist` project.

Novelist is a cross-platform writing suite for authors of all kinds, allowing you to produce novels, movie scripts and even scientific articles.


## Specification

Following is a quick and dirty spec for what novelist will be

 - Language: Vala for GUI stuff, maybe C++ or Rust for logic
 - GUI written in Gtk+ 3 (4 when it's released)
 - Commandline tool for exporting and working with files
 - A format that can easily be used with source control (git or similar)
 - "Page"-style what-you-see-is-what-you-get (WYSIWYG) editor
 - Distraction free mode
 - Analysis tools
   - Highlight certain word types
   - Highlight word collisions (repetitions within range)
   - Highlight only current sentence, line, paragraph, ...
 - Allow authors to arrange manuscript as folders (chapters) and files (scenes)
 - Provide templates for planning
   - Characters
   - Scenes
   - Locations
   - Embed pictures into planning area
   - Virtual storyboard
 - Export project as other editor formats (docx, odt, ...)
 - Export project as ebook types (epub, mobi, ...)


## Open questions

The project is currently not yet in development. This is a (curated) list of open questions regarding the project.

- [ ] Choosing a storage format ([#1](https://github.com/novelistapp/concept/issues/1))
