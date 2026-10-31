---
# Change these five lines as soon as you copy this starter.
title: CAPS/CTL
author: Heather McCuistion
category: Campus Services                 # change to a category from the student guide
header-image: zimmerman-library.jpg   # the filename of your own image
header-caption: John Tatchel, The History of Writing

# Fill these in later, once your research is under way.
card-description: Replace this with two sentences that summarize the story your essay tells and why it matters.
start:                                   # the year your story begins, shown on the map

# Leave this line as it is.
layout: essay
--- The history of academic support and peer tutoring at the University of New Mexico (UNM) is anchored by the evolution of the Center for Academic Program Support (CAPS) and its transformation into the modern Center for Teaching and Learning (CTL). For decades, these programs have served as foundational pillars for undergraduate retention, student success, and collaborative learning across the Albuquerque campus.

Origins and the Founding of CAPS (1979)
The institutional roots of undergraduate academic assistance at UNM trace back to 1979, when the Center for Academic Program Support (CAPS) was officially established [1.1.5]. Created to bridge gaps in undergraduate education and promote equity in retention, CAPS was designed to offer free-of-charge peer tutoring, study groups, and skill-building workshops for students enrolled in undergraduate courses (traditionally numbered 100 through 399) [1.2.1, 1.2.5].

Throughout the late 20th and early 21st centuries, CAPS grew into a prominent fixture of campus life, establishing its primary physical headquarters on the third floor of Zimmerman Library [1.2.5]. Staffed primarily by upper-division undergraduate and graduate students who underwent intensive pedagogical training, the program earned national certification from institutions like the College Reading and Learning Association (CRLA) [1.2.5]. Over the years, CAPS expanded its delivery methods beyond traditional drop-in and one-on-one sessions to include Supplemental Instruction (SI), specialized writing support, and modern digital platforms such as its Online Writing Lab (OWL) [1.2.3, 1.2.5].

The Evolution into the Center for Teaching and Learning (2015)
A major structural evolution occurred in 2015, when UNM consolidated its academic resources by merging CAPS with broader undergraduate teaching initiatives to formally establish the Center for Teaching and Learning (CTL) [1.1.1].

While the historical undergraduate tutoring functions commonly referred to as CAPS remained a core service, the structural shift under CTL aimed to create a more comprehensive hub supporting both sides of the classroom [1.1.2]. Located prominently in spaces like the lower level of Centennial Library (L185), CTL expanded to integrate specialized services such as STEM Tutoring, Learning Strategies, the Center for Digital Learning, and the Graduate Resource Center [1.1.4, 1.1.5, 1.2.1].

Impact and Contemporary Operations
In its modern iteration, CTL provides peer tutoring and structured academic support across more than 800 individual courses each semester [1.1.3]. Institutional metrics consistently highlight that undergraduate students who regularly utilize CTL resources achieve higher GPA averages and graduate at faster rates compared to non-users [1.1.3]. By blending the historic student-centered peer tutoring philosophy of 1979 CAPS with modern digital accessibility and teaching support, CTL remains a cornerstone of student persistence at UNM.

Sources and Further Reading
UNM Center for Teaching & Learning: Mission & History [1.1.1, 1.1.5]

UNM Center for Teaching & Learning: Undergraduate Support Services [1.1.3, 1.1.4]

UNM Digital Repository: Assurance Argument for CAPS Structure [1.2.5]

UNM Online Lobo Blog: Services Spotlight on CTL (2022) [1.1.2]

This first paragraph should give readers a quick way into your topic. Start with a scene, a question, a surprising fact, or a problem your essay will explain. You do not need to summarize everything here. Help the reader understand why this campus place, person, organization, object, or event deserves attention.

Keep the above lead paragraph first. Do not put an image, a heading, or any other component above it.

## Main Story

Use this section to tell the most important part of the history. Keep paragraphs short enough for online reading. A good paragraph usually develops one idea, source, moment, or change over time.

Use specific evidence from the archive. Name dates, people, places, decisions, conflicts, renovations, controversies, or missing records when they matter. The goal is not just to list facts. The goal is to explain what those facts reveal about UNM and its history.

<!-- Full-width figure. This is the default for any landscape photo wider than about 700px.
     image-path is just the filename: upload your images into this essay's folder,
     next to index.md. -->

{% include images/figure.html
  class="img-center"
  width="100%"
  caption="Replace this caption. Say why the image matters, not just what it shows, then cite where you found it: [Center for Southwest Research](https://econtent.unm.edu/), collection and box number."
  image-path="sample-archive-photo.jpg"
%}

Every image needs a caption, including this one. A caption should explain what the reader should notice and where the image came from. Captions accept Markdown, so use `[source](https://example.com/)` to link to a digital collection whenever the image has an online home.

## What Changed

Use this section to explain change over time. What did your topic used to be? How did people use it, describe it, fund it, argue about it, rename it, neglect it, preserve it, or forget it?

This is a good place to connect your specific topic to a larger campus pattern: enrollment growth, architecture, student life, race, gender, labor, protest, public memory, administration, technology, or access.

<!-- Carousel: use when you have three or more images that belong together but do not
     each need their own paragraph. Images are split on commas, captions on the | character.
     Carousel captions are plain text: Markdown links will NOT work here, so write out
     the collection name and box number instead of linking. -->

{% assign images =
"sample-archive-photo.jpg,
sample-second-photo.jpg,
sample-primary-source.jpg" | split: ','
%}

{% assign headers =
"Replace with a short slide title,
Replace with a short slide title,
Replace with a short slide title" | split: ','
%}

{% assign captions =
"Replace this caption. Explain what this slide shows and why it matters. Center for Southwest Research, collection name, box number.|
Replace this caption. Every slide needs one. Center for Southwest Research, collection name, box number.|
Replace this caption. Plain text only in carousels, so spell out the source instead of linking. Center for Southwest Research, collection name, box number." | split: '|'
%}

{% include images/carousel.html
  images=images
  headers=headers
  captions=captions
%}

Delete the carousel if you do not have a set of images that works this way. Three related photographs, a series of floor plans, or a run of newspaper clippings are all good candidates. Two images that need to be compared directly are usually better as a pair than as a carousel.

## Evidence

Use this section to show readers a document, not just a photograph. Scanned letters, meeting minutes, ledgers, clippings, and blueprints all reward close looking, and they prove you spent time in the boxes.

<!-- Portrait documents are the exception to the full-width rule. A tall scan at 100%
     is over 1200px tall and swallows the screen, so center it and leave it near 55%.
     Keep it centered, not floated. -->

{% include images/figure.html
  class="img-center"
  width="55%"
  caption="Replace this caption. Tell readers what to notice in the document and why it changes how they should understand your topic. Cite the collection, box, and folder."
  image-path="sample-primary-source.jpg"
%}

Explain what the document says, what it does not say, and how it fits the story. A source you actually read and explain is worth more than three you only mention.

## Why This History Matters

End by returning to the present. How should readers see this campus place, person, organization, object, or event differently after reading your essay? Point to continued use, memory, loss, gaps in the archive, or campus change rather than announcing a conclusion.

{% capture bibliography %}
- Replace this with your first source. Include enough detail that someone else could find it: collection name, box, and folder for archival material.
- Replace this with your second source.
- Replace this with your third source.
{% endcapture %}

{% include typography/bibliography.html
  title="Bibliography"
  content=bibliography
%}
