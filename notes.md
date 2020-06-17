# Notes — Week 5

## Sound

### Podcasting

* I talked about whatever came to mind regarding "things that have driven me nuts about learning digital history" for just over two minutes as a short podcast excerpt and saved it to the file "[podcast.m4a](sound/podcast.m4a)". I only did one take and didn't plan or draft any ideas beforehand.
* Transcript, verbatim (2:15):
  > So the thing about learning about digital history is that, you know, when your own educational background isn't of a very historical one, there are a lot of terms that will just, you know, go over your head. Like, you can read the term "historical argumentation" and go "yeah, yeah; it has the word "argument" in it, so they're uh... they're probably talking about proving history and how historical accounts disagree." But what does that mean? What does that mean? Like, uh... "argumentation" is still a- is still a pretty broad term and then there's another thing; like how is it that digital history can still be considered so different from the uh... regular, traditional, uh... run-of-the-mill history where, you know, they just argue about what happened in the... the antiquity or whatever? You know, right? Old stuff. Uh... shouldn't digital history just an extension of that? Like, uh... are there... are there historians abandoning the ways of the old and then, uh... exclusively using these newfangled technologies? Or... unless uh... are they- are they otherwi- if they're not forced to create footnotes and white papers or anything (unintelligible), can't they still use everything else that's... that was- that was- that historians used before, you know? And then, uh... y- you know, it shouldn't have to be that way. And then... uhh, you know, some papers I've seen, um... some papers from- from digital historians are suggesting that if your historical study involves you using something like, you know, computer vision, uh... machine learning, uh... you know, neural networks, that sort of thing... uh, then novices who go and try to replicate your study uh... won't be able to. (unintelligible) You know, novices in terms of uh... digital history. And then because you know, maybe they'll... they'll... they think that they'll forget to do the whole "close reading" thing and just, you know, actually a- manual analysis and then, they'll- they'll just rely on the computer to do all the distant reading. Like, why- why would they stop there? You know, a good historian isn't just going to take only half of the steps you took to develop the data for your argument, and then say you know, (foolish voice) "I couldn't replicate your study, so I- I- I can't evaluate your historical argument", right? Right? Yeah. No one- No one's gonna take only have the steps to replicate the study, so- so that part's pretty crazy, you know; stuff like that's pretty difficult to understand. 
  * When I said "can't evaluate" I meant "can't validate".
  * In hindsight, this transcript probably should have been edited to remove pauses.
  * I've used Audacity before and use it regularly; it's great software, but in this case, no editing was done.

### Sonification

* A tool that generates an audio track from data in a CSV. This seems like a niche use, but you could use it to create some background music for a video of another visualization rather than trying to pitch-shift or guess the notes yourself.
* Here, I did not feel the need to change much; the most distinct change is changing the instrument to Church Organ, which was fitting given the pace and slow change of the data.
* I exported both a "sonification-roman-count-of-coins.mp3" and a "sonification-roman-count-of-other-materials.mp3".

## Mapping

### Telling stories with StoryMaps

* [I made a StoryMap about King Tut's adventures in Ancient Egypt](https://uploads.knightlab.com/storymapjs/d1b23d0d71274aab66568347ebc8e1d4/demo-story-map/index.html).
* I mostly used images from Wikipedia and Wikimedia Commons.
* I noticed that the location entered would be lost if I switched slides without saving, so I made sure to save after choosing a location for the slide.
* I wish I could have just entered a coordinate pair from Google Maps rather than using KnightLab's coordinate syntax. I could have easily been more precise that way.
* Overall, the software is easy and quick to use.

### Webmapping with Leaflet

* I didn't experience any issues setting up the webmap or using `python` to start a webserver.

### Adding a new layer to our map

* That works pretty well! I've been hoping to do more with map services and APIs for the longest time; the possibilities seem truly endless.

### Georectifying a base map

* The scan is a bit askew, but I chose a plan of the township of Nepean, 1824, [MIKAN 4131276](http://collectionscanada.gc.ca/ourl/res.php?url_ver=Z39.88-2004&url_tim=2020-06-16T21%3A37%3A12Z&url_ctx_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Actx&rft_dat=4131276&rfr_id=info%3Asid%2Fcollectionscanada.gc.ca%3Apam&lang=eng). 
* Hey, not bad. It overlaid almost perfectly for only three points. Here's the exported rectified PNG map; it turned out pretty well. The original in the repository has transparency.

  ![Rectified map](https://i.imgur.com/FqFwCZH.jpg "Rectified map")  
  *Rectified map*

### Adding a layer control button

* No issues with this part.

### Adding animation

* No issues with this part. This could prove useful in the future.

## Posters

* Though I had heard of Inkscape before, I had not used it until this exercise.

### Sprucing up a PDF in Inkscape

* That is indeed quite the simple graphic / histogram / bar chart.
* Compared to Photoshop's default of holding Shift (or in recent years, *not* holding Shift), along with many other programs' Shift usage for the same purpose, Ctrl + Shift is a bit of an unusual keyboard combo for keeping proportions the same.
* It's not immediately clear how to set a stroke colour on a rectangle. I ended up right-clicking the shape and clicking "Fill and Stroke..." in the context menu.
* I made a bar cyan, then for the legend, I created a cyan rectangle (square) and put some text that made it seem like there was an increase in articles due to a fictional "1819 Italian economic miracle" event.
* The export option was actually called "Export PNG Image". I'm not sure if I need to select everything for the export to work, either, but maybe that gave it the nice dimensions that only show the chart, rather than the whole canvas (including the empty parts).
* This is pretty handy; I had thought PDFs were much harder to edit than this. I will probably keep this software installed unless I find a better alternative!

![Raster graphic of the edited chart](https://i.imgur.com/ofyssWT.png "Raster graphic of the edited chart")  
*Raster graphic of the edited chart*

### Making an academic poster

* It's entirely possible that I wouldn't have done a post-secondary academic essay by now, but luckily, I do have one.
  * I picked a very brief paper—just over two pages, double-spaced—written in TSES 3001: Technology–Society Interaction. Perhaps it's more of a report than an essay, but I don't remember the specifics. Hopefully there's enough material here to create a quick poster about it. 
* Normally, I would use an Adobe suite tool to create a poster, so I didn't trouble myself too long with making the poster while forcing myself to use Inkscape. Considering I'm working with time constraints, it would also be quite time-consuming to fine-tune the details.
* Luckily, this step suggests working from a template, so I don't have to spend too much time on the design so much as critiquing the layout I chose.
* I chose the "poster.svg" template and renamed it "poster-template.svg" before working on it. The general look to it reminded me of posters I've seen at the Canada Science and Technology Museum that were about satellites; dark blue, white, and grey is a recurring colour scheme with space technology, it seems. Because the essay I chose is about a satellite, it's perfect.
* Other difficulties I encountered using Inkscape included:
  * Difficulty pasting in text to existing text boxes
  * Undoing typing tends to undo one letter at a time
  * Pasting in text separated it into two separate text boxes for some reason
  * Resizing text fields isn't easy and might distort the proportions of the text
  * Certain elements not coming back with an undo after being deleted
  * Certain layers not rendering properly

!["Partial progress on an academic psoter demonstrating I mostly get the idea"](https://i.imgur.com/V2BgdUW.jpg "Partial progress on an academic poster demonstrating I mostly get the idea")
*Partial progress on an academic poster demonstrating I mostly get the idea*

#### Layout

##### What did work

* The poster features a pseudo-three-dimensional effect by purposefully overlaying an image of the satellite over a boundary, making it pop out.
* The colours match the theme well, and are mostly earth tones (blue, grey). Using two primary colours (blue and yellow), and different shades of the same colour (gradients), it followed basic colour theory.
* Yellow colours are used to highlight parts of an acronym.

##### What didn't work

* The template I chose had more space for information than I had to fill it, so I had to lop off the top half of it.
* I wasn't able to pay much heed to the rule of thirds or golden ratios.

## Static websites

* This isn't anything I haven't done before, but let's do it again for practice!
* GitHub Pages is something that tends not to work the first time even if you follow the instrutions verbatim, possibly due to how web hosting works, but it's a fun gamble.
* Because I don't want to affect the *username.github.io* I may already have set up on this GitHub account that's been around for awhile, I instead used this Week 5 repository for GitHub Pages. This makes the static website end up in a subdirectory of *username.github.io*. In my case, [erikhumphrey.github.io/hist3814o-s20-week5/](https://erikhumphrey.github.io/hist3814o-s20-week5/).
* I created the "[index.md](docs/index.md)" rather than at the top level, to separate it from the rest of the repository.
  * I also made [an HTML version](static-websites/unused-index.html) as a backup, in case Markdown didn't end up working.
* After selecting the "master branch /docs folder" as the GitHub Pages source in the repository's settings, I selected a Jekyll theme on GitHub as well. This created an automatic commit (with me as the author) to put the [_config.yml](docs/_config.yml) in the /docs folder.
* After this was done, the site was successfully published at [erikhumphrey.github.io/hist3814o-s20-week5/](https://erikhumphrey.github.io/hist3814o-s20-week5/)!
