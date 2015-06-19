<!-- .slide: data-background="custom/images/opening-slide-1.png" -->




<!-- .slide: data-background="custom/images/opening-slide-2.png" -->




<!-- .slide: data-background="custom/images/opening-slide-3.png" -->




<!-- .slide: data-background="custom/images/opening-slide-4.jpg" -->




<!-- .slide: data-background="custom/images/opening-slide-5.png" -->

Note:
- First time in St. Louis, though I have take then trip to almost-St. Louis many times




<iframe width='100%' height='650px' frameBorder='0' src='https://a.tiles.mapbox.com/v4/alimac.mej466bj/attribution,zoompan,zoomwheel,geocoder,share.html?access_token=pk.eyJ1IjoiYWxpbWFjIiwiYSI6Ill4dmFqWDQifQ.2wLpCVaXG-sr8bTo1ueM0A'></iframe>

Note:
- Staunton, IL - about 40 miles northeast
- Tour de Donut - 32-mile bicycle race with 2 donut stops
- 5 minutes off total time for each donut eaten



<!-- .slide: data-background="custom/images/tour-de-donut.jpg" data-background-size="1068px" -->

Note:
- Personal record: 2 donuts



## <i class="fa fa-sign-in"></i> Finding the Entrance
####_Why and how to get involved in the Drupal community_



## [bit.ly/find-entrance](http://bit.ly/find-entrance)

Note:
- Slides and speaker notes available



## Alina Mackenzie
<img src="custom/images/alimac-avatar.png">

<a href="https://www.drupal.org/u/alimac"><i class="fa fa-drupal"></i> alimac</a>

<a href="https://twitter.com/czaroxiejka"><i class="fa fa-twitter"></i> czaroxiejka</a>

char • o • jay • ka
<!-- .element class="fragment" style="word-spacing: 8px;" -->

Note:
- Developer and system administrator based in Chicago
- Doing Drupal for ~4 years, active in the community for ~2 years
- Where is the Drupal community?



<!-- .slide: data-background="custom/images/xkcd-online-communities-map.png" data-background-size="680px" data-state="show-header" data-header="Source: xkcd.com/802/" -->

Note:
- "Map of Online Communities" by Randall Munroe of XKCD
- Slightly out of date (circa 2010)
- Drupal and community have been around longer



<!-- .slide: data-background="custom/images/xkcd-fragment-1.jpg" data-background-size="1280px" data-state="show-header" data-header="Source: xkcd.com/802/" -->

Note:
- Drupal community uses IRC for online chat
- First search location: IRC Isles
- No luck, and too close to Troll Bay



<!-- .slide: data-background="custom/images/xkcd-fragment-2.jpg" data-background-size="1280px" data-state="show-header" data-header="Source: xkcd.com/802/" -->

Note:
- Bay of Drama? Buzzword Bay?
- Adrift in the Sea of Opinions



<!-- .slide: data-background="custom/images/isle-of-drupal.jpg" data-background-size="1280px" -->
## Isle of Drupal
<!-- .element: class="hidden" -->

Note:
- Found: Isle of Drupal
- Landmarks, but no detail
- Maps are static, need another approach



## How is Drupal made?
<img src="custom/images/drupal-releases.png" class="fragment">

Note:
- Maybe we can find out how community works by looking at how the project is built?
- Ever wonder what goes into these files?



<!-- .slide: data-background="custom/images/christoph-spiegl-code.jpg" data-state="show-header" data-header="Photo: CC-BY-NC Christoph Spiegl http://flic.kr/p/7DmgDW, cropped" -->
## Code
<!-- .element: class="heading" -->

Note:
- Download Drupal, unpack and open up in a text editor
- Different kinds of code: PHP, HTML, CSS, Javascript
- How did that code get there?
- How do we change the code, and make Drupal event better?



<!-- .slide: data-background="custom/images/amanda-sewing-patches.jpg" data-state="show-header" data-header="Photo: CC-BY-NC-ND amanda https://flic.kr/p/7NSvF, cropped" -->
## Patch
<!-- .element: class="heading invert" -->

Note:
- Changes to code: adding code, removing code
- Set of changes is packaged into a file ("patch")



<!-- .slide: data-background="custom/images/amanda-sewing-patches.jpg" data-state="show-header" data-header="Photo: CC-BY-NC-ND amanda https://flic.kr/p/7NSvF, cropped" -->
<img src="custom/images/patch.png" alt="Contents of a patch file">
<!-- .element: class="stretch" -->

Note:
- A patch is a plain text file
- Lines added are marked with +, lines removed are marked with -
- Patch is applied to the project codebase, transforming it
- Where do patches come from?



<!-- .slide: data-background="custom/images/wlodi-big-red-button.jpg" data-state="show-header" data-header="Photo: CC-BY-SA włodi https://flic.kr/p/5GCeGg, cropped" -->
## Starting point
<!-- .element: class="heading invert" -->

Note:
- A bug report, a feature request, an enhancement



<!-- .slide: data-background="custom/images/wlodi-big-red-button.jpg" data-state="show-header" data-header="Photo: CC-BY-SA włodi https://flic.kr/p/5GCeGg, cropped" -->
> <i class="fa fa-quote-left"></i>
> I mashed the button, but it didn't do anything.
> <i class="fa fa-quote-right"></i>

Note:
- Someone creates an issue in the issue queue on drupal.org
- And maybe...



<!-- .slide: data-background="custom/images/wlodi-big-red-button.jpg" data-state="show-header" data-header="Photo: CC-BY-SA włodi https://flic.kr/p/5GCeGg, cropped" -->
> <!-- .element: class="invert" -->
> <i class="fa fa-quote-left"></i>
> Me too!
> <i class="fa fa-quote-right"></i>
> <i class="fa fa-heart fragment current-visible" style="color: #c00;"></i>

Note:
- Someone comes along and adds a "Me too!" comment
- Meetoos are great. Meetoos validate our pain.
- What next?



## Issue summary

Note:
- Original post serves as "issue summary"
- Anyone can add words to the issue summary
- Steps to reproduce, screenshots or screencasts
- Finally...



## A patch appears!

Note:
- Someone writes the first set of changes to the Drupal codebase that fix the problem
- Maybe patch is incomplete
- Maybe automated tests fail
- But...



## Second patch

Note:
- Someone else can build on the work done in the first patch
- Process can be repeated, until the patch is ready to be reviewed



## Review

Note:
- Reviewing is important to the process of making Drupal better
- Does the patch fix the problem?
- Post before and after screenshots
- Check coding standards



## Reviewed and tested by community

Note:
- RTBC
- Drupal core committers review issues that reach RTBC status
- They check the changes and commit, if everything looks OK
- Issue creator, screenshot creator, patch contributors, reviewers all get commit mentions
- Watch this process happen live at 2014 DrupalCamp NYC



<!-- .slide: data-background-video="custom/holly-ross-2014th-contributor.mp4" data-state="show-header" data-header="Drupal Camp NYC 2014 Source: https://youtu.be/RNaPAzhxw58" -->



<!-- .slide: data-background="custom/images/littlelixie-patchwork.jpg" data-state="show-header" data-header="Quilt by Keiko Ohno. Photo: CC-BY-NC Littlelixie https://flic.kr/p/pF4Ekn" -->
## Contributions
<!-- .element: class="heading invert" -->

Note:
- Creating an issue, adding information, posting patches and reviewing are all valuable contributions
- Invisible element: organizing the event
- Let's bring the focus back to the *people* that make the Drupal community



<!-- .slide: data-background="custom/images/eric-the-last.jpg" data-state="show-header" data-header="" style="margin-top: 175px; margin-left: 200px;" -->
> ## Eric Brown <a href="https://www.drupal.org/user/1037606"><i class="fa fa-drupal"></i> ericthelast</a>
> <i class="fa fa-quote-left"></i>
> I was always struck by his willingness to listen and share his knowledge. I learned a lot from him, not only technically, but by his modeling of humility and genuine care for others.
> <i class="fa fa-quote-right"></i>
> <span>Source: [ericthelast.org](http://ericthelast.org)</span>
<!-- .element: class="quote-source" -->

Note:
- In the words of Cecily Borzillo: "Eric was the cornerstone of the St. Louis user group. He was always the first to offer help to anyone that needed it, and believed strongly in making Drupal accessible to anyone that had interest."



<!-- .slide: data-background="custom/images/geerlingguy-photo.jpg" data-background-size="" data-state="show-header" data-header="" style="margin-top: 250px; margin-left: 50px;" -->
## Jeff Geerling
<!-- .element: class="hidden" -->
> <i class="fa fa-quote-left"></i>
> It helps to have a huge network of <span class="highlight">local and regional friends</span>, whether it be on Twitter, in IRC, or in person.
> <i class="fa fa-quote-right"></i>
> <span>Jeff Geerling <a href="https://www.drupal.org/u/geerlingguy"><i class="fa fa-drupal"></i> geerlingguy</a></span>
<!-- .element: class="quote-source" -->

Note:
- Maintainer of Honeypot module, Drupal.org Packaging Whitelist, 7 years with St. Louis meetup group
- Local events: meet and speak with many more people, sprints are more focused and less overwhelming
- Reviews patches, submits patches and feedback for core and contributed projects



<!-- .slide: data-background="#243F63" -->
## Fredric Mitchell
<!-- .element: class="hidden" -->
> <!-- .element: class="invert" -->
> <i class="fa fa-quote-left"></i>
> I've met a lot of great people, from Minneapolis to New York to Costa Rica and San Francisco. Having a <span class="highlight">network to lean on</span> and get support from is always helpful.
> <i class="fa fa-quote-right"></i>
> <span>Fredric Mitchell <a href="https://www.drupal.org/u/fmitchell"><i class="fa fa-drupal"></i> fmitchell</a><br><img src="custom/images/fmitchell-headshot.jpg"></span>
<!-- .element: class="quote-source" -->

Note:
- Mentorship, staying positive and promoting others doing greak work
- First got involved through work
- Promotes Drupal in all his ventures, including own startup
- Volunteers and speaks at events



<!-- .slide: data-background="custom/images/greg-dunlap-cathy-theys.jpg" data-background-size="" data-state="show-header" data-header="Photo: CC-BY Greg Dunlap https://flic.kr/p/eLDNyK" style="margin-top: 200px; margin-left: 150px;" -->
## Cathy Theys
<!-- .element: class="hidden" -->
><i class="fa fa-quote-left"></i>
>Being involved has given me interesting problems to solve, access to interesting <span class="highlight">smart people</span>, and has taught me a lot about programming and people. <i class="fa fa-quote-right"></i>
> <span>Cathy Theys <a href="https://www.drupal.org/u/yesct"><i class="fa fa-drupal"></i> YesCT</a></span>
<!-- .element: class="quote-source" -->

Note:
- Works on Drupal core and mentors new contributors
- Improving contribution process for new and ongoing contributors
- Stayed extra days at DrupalCon Denver to join the sprints



<!-- .slide: data-background="#7F141A" -->
## Kevin Thull
<!-- .element: class="hidden" -->
><!-- .element: class="invert" -->
><i class="fa fa-quote-left"></i>
>I used to be that shy guy in the corner, but community involvement has really <span class="highlight">grown my network</span> and my confidence.
>I wouldn't trade that for anything. <i class="fa fa-quote-right"></i>
><span>Kevin Thull <a href="https://www.drupal.org/u/kthull"><i class="fa fa-drupal"></i> kthull</a><br><img src="custom/images/kthull-headshot.jpg" style=""></span>
<!-- .element: class="quote-source" -->

Note:
- meetup and camp organizer, print support for Drupal core mentoring
- many firsts: issue queue, meetups, camps
- affordable session recording kit
- shares non-Drupal expertise to fill gaps needed at events



<!-- .slide: data-background="custom/images/kgoel-photo.jpg" data-state="show-header" data-header="Photo: CC-BY Boris Baldinger https://flic.kr/p/paDdif" style="margin-top: 200px;"-->
## Kalpana Goel
<!-- .element: class="hidden" -->
><i class="fa fa-quote-left"></i>
>It has not only helped me <span class="highlight">become a better developer</span> but I have recognized hidden skills inside me which I wasn't aware of before.
><i class="fa fa-quote-right"></i>
><span>Kalpana Goel <a href="https://www.drupal.org/u/kgoel"><i class="fa fa-drupal"></i> kgoel</a></span>
<!-- .element: class="quote-source" -->

Note:
- Contributes patches, reviews, mentors new contributors
- Tried different areas in span of about 3 years to find the right place: Drupal 8, Symfony
- Increased social circle and confidence



<!-- .slide: data-background="custom/images/kandra-photo.jpg" data-state="" data-header="" style="margin-top: 250px; margin-left: 200px;"-->
## Karen Da Cruz
<!-- .element: class="hidden" -->
><i class="fa fa-quote-left"></i>
>It has provided me with plenty of <span class="highlight">opportunities</span> for growth, exquisite challenges and hard learned lessons.
>And I am not talking about tech alone!
><i class="fa fa-quote-right"></i>
><span>Karen Da Cruz <a href="https://www.drupal.org/u/kandra"><i class="fa fa-drupal"></i> kandra</a></span>
<!-- .element: class="quote-source" -->

Note:
- Co-organizer of Drupal Lima meetup: shares knowledge through workshops and talks, effort to involve women
- Introduced by a friend to open source: ability to build sustainable career path
- Goal: increase women's participation in the tech community
- Learned mor about people than tech: being a team player vs. lone wolf
- Visibility converts into reputation, which gives opportunities to grow career-wise and as a person



<!-- .slide: data-background="custom/images/isle-of-drupal-sea-routes.jpg" data-background-size="1280px" -->
## Sea routes
<!-- .element: class="hidden" -->

Note:
- Movement: Drupal community is part of intersecting communities
- Communities around technologies like PHP
- Topics: accessibility, multilingual, user experience, automation



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Support
<!-- .element: class="heading" -->

Note:
- Do you like a challenge? Figuring things out?
- Support online: forums, chat. In person: at meetups, user groups



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Usability testing
<!-- .element: class="heading" -->

Note:
- Find and document bugs
- Test and review patches



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Documentation
<!-- .element: class="heading" -->

Note:
- Add and remove words, like code
- Make things clear and easy to understand
- Describe new features



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Translate
<!-- .element: class="heading" -->

Note:
- Translate words



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Front-end
<!-- .element: class="heading" -->

Note:
- Style user interfaces and experiences



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Back-end
<!-- .element: class="heading" -->

Note:
- Review code
- Write code



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Marketing
<!-- .element: class="heading" -->

Note:
- Meet other open source contributors?
- Introduce and promote Drupal



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Core initiatives
<!-- .element: class="heading" -->

Note:
- Interest areas
- Initiatives: configuration management, design, mobile, multi-lingual, web services
- Topics: accessibility, documentation, performance, testing, usability
- [MAINTAINERS.txt](http://cgit.drupalcode.org/drupal/tree/core/MAINTAINERS.txt)



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Attend events
<!-- .element: class="heading" -->

Note:
- You are here and you are awesome
- Even if you can't attend in person, watch recorded talks
- Give feedback to presenters: "I really liked... I wish that..."



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Give talks
<!-- .element: class="heading" -->

Note:
- Great way to learn about a topic
- As a beginner at something, you are an *expert* at being a beginner



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Help organize events
<!-- .element: class="heading" -->

Note:
- Organizing events is a tough but rewarding task
- Got spare time? Help organize DrupalCamp St. Louis next year



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Start a meetup
<!-- .element: class="heading" -->

Note:
- Hyperlocal: meetup at your workplace, school



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Write blog posts
<!-- .element: class="heading" -->

Note:
- Similar to giving talks



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Make screenscasts, podcasts
<!-- .element: class="heading" -->

Note:
- Somewhere between giving a talk and writing a blog post



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Build a module or theme
<!-- .element: class="heading" -->

Note:
- Release your custom code to the community



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Donate
<!-- .element: class="heading" -->

Note:
- Drupal 8 Accelerate fund supports work on Drupal 8



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Join Drupal Association
<!-- .element: class="heading" -->

Note:
- Drupal association provides community grants and organizes DrupalCons
- Europe, North America, South America, Asia



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Sponsor an event
<!-- .element: class="heading" -->

Note:
- Meetups, camps, sprints need sponsors
- Offer event space, buy snacks, coffee and tea, lunch
- Meet current and future developers, contributors, project managers, generalists, designers and learners



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Become a mentor
<!-- .element: class="heading" -->

Note:
- Online mentoring on IRC chat
- In person mentoring at events
- One on one mentoring



<!-- .slide: data-background="custom/images/" data-state="show-header" data-header="" -->
## Encourage others
<!-- .element: class="heading" -->

Note:
- One of the most powerful things you can do is give encouragement to another person, and invite them to do something together



<!-- .slide: data-background="custom/images/australian-afternoon.jpg" data-state="show-header" data-header="" -->
## My story
<!-- .element: class="heading invert" -->

Note:
- Feeling of inadequacy about making a meaningful contribution
- Global Sprint Weekend 2014: asked about my goals ("what do you want to learn?"), autonomy in defining objectives was powerful
- benefits: learned to ask questions, be around accessibly smart and kind people, learned to communicate in shared spaces vs 1-on-1, learned to be explicit, learned to break complex things down into simpler bits, learning to delegate




<!-- .slide: data-background="custom/images/nancy-nance-door.jpg" data-state="show-header" data-header="Photo: CC-BY nancynance https://flic.kr/p/srX6Dn" -->
## Tomorrow
<!-- .element: class="hidden" -->
> <i class="fa fa-quote-left"></i>
> When you develop an interest, it usually comes from an environment that de-dramatizes things.
> Because then you’re able to <span class="highlight">find your own entrance</span> into it.
> <i class="fa fa-quote-right"></i>
> <span><a href="http://pitchfork.com/thepitch/746-what-happens-when-there-are-no-boys-in-the-room-a-report-from-robyns-tekla-conference/">Robyn</a></span>
<!-- .element: class="quote-source" -->

Note:
- People of all skills welcome at the sprint
- Write down top three things about Drupal (or related technologies) that you are interested in, right now.
- Pick a thing on the list. break it down into smaller parts, if needed
- Learn it! ask questions
- Learn more about core contribution process
