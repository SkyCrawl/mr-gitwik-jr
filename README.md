## Mr. Gitwik Jr.

> a.k.a. "Markup resistant git-based Wiki on JRuby"

This Wiki system is inspired by Gollum. Gollum has been around for many years and enjoys a large userbase but it also faces many problems and suffers from serious caveats.

The purpose of this project is to write a brand new next-gen Wiki system, similar in functionality to Gollum, that addresses most of Gollum's drawbacks, defects and deficiencies. For example:
* Target Ruby implementation is JRuby.
  * This sole fact is a big win because support for various platforms is ensured, just like that. No additional cost of maintaining support for multiple git adapters and the like for the devs.
  * In general, performance may be a little worse and memory usage a little higher than running with MRI but on other hand, JRuby brings its own advantages. For example, easy threading.
* Source code quality and internal design. The principal causes for Gollum's bad maintainability and slow development, as well as many bugs.
* Configuration and customizability. Gollum has great potential to be VERY configurable and customizable (on-user level) and yet, it is really not.
* Performance, namely with large repositories and pages.
* Security, especially regarding handling files and cross-site scripting.

In addition to all that, we want our Wiki to be:
* Truly modern and next-gen, with lots of new features and possibilities. You might be amazed at how many wonderful ideas we have.
* Young and fresh, like a singing bird in the morning.
* User-friendly. Despite how configurable and customizable Gitwik should be, running out of the box is something we believe in and for the more playful, extensive documentation must be ready.
* Fast. We want to make loading pages as fast as possible but hey... loading large pages with a lot of content may still take about 2-3 seconds, no getting around that.

Also, we want to have a tighter relationship with our users. Should you subscribe, we want to:
* Inform what we're currently working on.
* Announce when the new awesome versions are coming out, with helpful information.
* Share good tips about using our Wiki, should we learn some.
* Ask our users which features they wish for most. Short polls for those who'd like Gitwik to walk a certain way, soon.

And we can't stress this enough...
* We want Gitwik to be secure.
* We want Gitwik to excel in code quality, making it really maintainable.
* We want everything about Gitwik to scream with the word "quality".
* Eventually, we want to bring you official Docker support.

So much for the plans... Gonna take a while to make a reality :).
