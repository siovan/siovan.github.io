---
layout: post
title:  Markdown grew up while I wasn't looking
date:   2016-06-17 
categories: dh markdown tools
---

I recently got a new computer, so of course I am revisiting and reevaluating my work flow. My former workflow went something like this:

1. Write in LaTeX because plain text and proper bibliography managment make life easy.
2. Fiddle with obscure Latex formatting to get things looking just so.
3. Submit PDF.
4. Someone asks for the file in .doc or .docx because I'm a humanities scholar and that's how most people work in my field.
5. Try to remember the rather obscure process for converting LaTeX to .odt using `tex4ht`.
6. Think I have it figured out, run the conversion. Bibliography is eaten.
7. Swear colorfully.
8. Repeat steps 5 through 7 a few times. 
9. Remember that the only way to get the bibliography to work is to use a version of LaTeX from 2010.
10. Find the flash drive with that version and install it since I've overwritten it for some reason.
11. Run conversion again and pray.
12. It worked! Import into LibreOffice.
13. Fiddle with mangled styles for hours.
14. Save to .docx and send to appropriate person.

I started writing in LaTeX many years ago because I got addicted to writing in plain text and I stuck with it because of the magic it works with Chicago style references. It produces beautiful documents and the footnotes are automatically perfect every time. Having watched others struggle with the lack-luster bibliography support in word processors, I found that the problems involved with making it work in a Word-centric field were well worth it. 

Having found a system that worked (kind of) I left it alone because I find it very easy to spend more time tweaking workflow than actually writing, and I needed to write. But with an upgrade in my working computer, the move from Linux to a Mac (which is another post all together), and getting the funding to finish my book, I have a reason to re-evaluate how I work. The last time I looked at Markdown the support for citations was virtually non-existant. Oh, the joy when I ran across [this article](https://medium.com/@chriskrycho/academic-markdown-and-citations-fe562ff443df#.68u9kyn7q) discussing how to use Markdown and Pandoc with bibtex to produce Chicago style footnotes.

Being the highly skeptical person that I am, I didn't believe it could possibly be that easy. Surely there would be some hangup. I ran one of my LaTeX files through pandoc to convert it to Markdown. There are some funky things with brackets around certain parts of the citation keys, but nothing too strange. The moment of truth was when I ran the markdown file through pandoc again and had it spit out .docx. It worked. It was unbelievably easy. Yes, the styles were messed up, but they were much better than the styles produced by `tex4ht`. All the footnotes are there with appropriate long and short forms and ibid's in all the right places.

I'll write more about using markdown as I get used to the system (I can say right off the bat that it is much easier to read and to write than LaTeX is), but I'm thrilled that it has developed into such a useful and robust tool.