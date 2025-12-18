---
title: Guide
nav: Guide
gallery: true
---

<br>

{% include feature/nav-menu.html sections="Getting Started;Text as Images;Adding and Editing Alt Text;Decorative and Complex Images;PDFs;Media;Semantic Content;Check Links" %}

<br>

{% include card.html text="Select any image embedded in this guide to expand" title="Note:" color="light" align="left" %}

<br>

## Getting Started

<br>

- To begin, visit the LibGuide you want to remediate, scroll to the bottom of the page and select `Login to LibApps.`

    {% include gallery-figure.html img="lib_remed_02.jpg" alt="Screen capture of the LibGuide interface with a red arrow pointing toward the bottom right of the screen." %}

<br>

## Text as Images 

<br>

- Images should not be used as replacement for text or tables. 

{% include gallery-figure.html img="lib_remed_04.png" alt="Example of an image being used for text in the form of a small Find It widget in a LibGuides box." caption="Example of an image being used for text in LibGuides." width="50%" %}

> A screen reader friendly version of the above example could be "Look for the Find It icon," and then add alt text to the embedded image ("Find It icon").

When reviewing images being used as text, it is helpful to think about what this is actually adding to guide that can't be achieved with text.

<br>

## Adding and Editing Alt Text

<br>

- Image must have alt text. 

To check if images on your page are missing alt text, there are a variety of web browser plug-ins that are available. The one I use is called [Image Alt Text Viewer](https://chromewebstore.google.com/detail/image-alt-text-viewer/nhmihbneenlkbjjpbimhegikadfleccd) and it quickly flags both invalid links as well as valid redirect links.

{% include gallery-figure.html img="lib_remed_10.jpg" alt="Screen shot of a LibGuide with black boxes and green text visualizing the alt text of two embedded images on a page." caption="Example of the Alt Text Viewer plug-in on a LibGuide." %}

To add or edit the alt text of the images in your LibGuides, select the edit icon in the lower right corner of the box where the image is located, then select `Edit` from the dropdown:

{% include gallery-figure.html img="lib_remed_03.jpg" alt="Screen shot of the cover page for the Agricultural Economics LibGuide with a photograph of people and animals and a red arrow pointing at the lover right hand corner of the box." %}

Double click the image within the editing window:

{% include gallery-figure.html img="lib_remed_05.jpg" alt="Screen shot of the same image within the editing window with the photograph selected." %}

Within the `Image Properties` window, add or edit descriptions in the `Alternative Text` field. 

{% include gallery-figure.html img="lib_remed_06.jpg" alt="Screen shot of the image properties field, with various fields to configure and add alt text to images." %}

{% include feature/alert.html text="When writing alt text, a good rule of thumb is that the image description is generally everything that is _not_ in the image (date, time, location and names of people in the image) and the alt text description is everything that _is_ in the image (Two people wearing hats and suits beside a sign that reads Hat Store, standing on the sidewalk)." color="light" align="left" %}

If you are wondering how to classify an image to determine whether it needs alt text, please visit the WCAG [Alt Text Decision Tree](https://www.w3.org/WAI/tutorials/images/decision-tree/).

<br>

## Decorative and Complex Images

<br>

Decorative images are the only image types that should not have any alt text, so a patron using a screen reader will skip past that element on a page. These are defined by the [Web Content Accessibility Guidelines](https://www.w3.org/WAI/tutorials/images/decorative/) as images that don't add information to the content of a page and can include:

- Visual styling such as borders, spacers, and corners;
- Supplementary to link text to improve its appearance or increase the clickable area;
- Illustrative of adjacent text but not contributing information (“eye-candy”);
- Identified and described by surrounding text.

{% include gallery-figure.html img="remed_pdf_21.jpg" alt="Highlight of an older U of I logo on a page." caption="Example of a decorative image." %}

Although this shouldn't really come up too much in LibGuides, if you do have a decorative element, simply leave the alt text field blank for the item so patrons using screen readers will skip over it.

**Complex Images**

While these elements don't seem to be incorporated in our LibGuides frequently, complex images such as charts and graphs need to have detailed descriptions in the body text that convey their full information. These images also need alt text that is less detailed but still conveys a sense of what is being communicated visually. An example from the [WCAG guide for creating alt text for complex visual images here](https://www.w3.org/WAI/tutorials/images/complex/):

- "Bar chart showing monthly and total visitors for the first quarter 2014 for sites 1 to 3, described in detail below."

This signposts to patrons using screen readers that this image will be unpacked shortly.

<br>

## PDFs

<br>

Check any PDF files that are being hosted onto our LibGuide or library servers, as we are responsible for making this material accessible. For a full guide to checking and remediating the accessibility of your PDF files with Adobe Acrobat Pro, please visit the [Adobe PDF Accessibility Remediation Workshop](https://aweymo-ui.github.io/remediate_pdfs/).

{% include gallery-figure.html img="lib_remed_07.jpg" alt="title card of the presentation Adobe PDF Accessibility Remediation Workshop, guide for University of Idaho Faculty, staff and Students, Andrew Weymouth, Fall 2025 and an image of two circles using a PDF file called Effective Farming Systems." %}

<br>

## Media

<br>

All embedded video and audio needs to have a description that let's patrons know there is media below, as well as a transcript of the recording. The majority of embedded media that is currently on our LibGuides is coming from YouTube, which will have an auto-generated transcript that screen readers can tab through and implement on playback.

In this example:

{% include gallery-figure.html img="lib_remed_08.jpg" alt="Screen shot of a LibGuide page containing four videos under a tabbed header." width="50%" %}

a short description before the video content would let patrons using screen readers know what is below and why it is relevant to the instruction topic. For example:

- "Below are four short videos by Mike Caulfield, Director of Blended and Nerworked Learning, to help you develop your online verifications skills. After the introductory video, the second video will show you how to investigate source materials, followed by how to find the original source of the subject you are investigating, and finally a guide for finding trusted work."

For video or audio media coming from a platform like YouTube that comes with an auto-caption, transcript will need to be created. Please reference [this guide to generate transcripts of either audio or video material using Adobe Premiere](https://aweymo-ui.github.io/premiere_transcripts/). This includes details on how to edit and export your transcripts, as well as turning the media into a video file with mono or bi-lingual captions.

{% include gallery-figure.html img="lib_remed_09.jpg" alt="title card of the presentation Adobe Premiere Transcript Workshop, guide for University of Idaho Faculty, staff and Students, Andrew Weymouth, Winter 2025 and an image of two circles using the cover of the book Voces Hispanas: Hispanic Voices of Idaho." %}

<br>

## Semantic Content 

## Check Links

