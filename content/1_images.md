---
title: Images
nav: Images
gallery: true
---

<br>

{% include feature/nav-menu.html sections="Getting Started;Text as Images;Adding and Editing Alt Text;Decorative Images;Complex images;PDFs;" %}

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

To check if images on your page are missing alt text, there are a variety of web browser plug-ins that are available. The one I use is called [Check My Links]{https://chromewebstore.google.com/detail/check-my-links/aajoalonednamcpodaeocebfgldhcpbe?pli=1} and it quickly flags both invalid links as well as valid redirect links.

To add or edit the alt text of the images in your LibGuides, select the edit icon in the lower right corner of the box where the image is located, then select `Edit` from the dropdown:

{% include gallery-figure.html img="lib_remed_03.jpg" alt="Screen shot of the cover page for the Agricultural Economics LibGuide with a photograph of people and animals and a red arrow pointing at the lover right hand corner of the box." %}

Double click the image within the editing window:

{% include gallery-figure.html img="lib_remed_05.jpg" alt="Screen shot of the same image within the editing window with the photograph selected." %}

Within the `Image Properties` window, add or edit descriptions in the `Alternative Text` field. 

{% include gallery-figure.html img="lib_remed_06.jpg" alt="Screen shot of the image properties field, with various fields to configure and add alt text to images." %}

{% include feature/alert.html text="When writing alt text, a good rule of thumb is that the image description is generally everything that is _not_ in the image (date, time, location and names of people in the image) and the alt text description is everything that _is_ in the image (Two people wearing hats and suits beside a sign that reads Hat Store, standing on the sidewalk)." color="light" align="left" %}

If you are wondering how to classify an image to determine whether it needs alt text, please visit the WCAG [Alt Text Decision Tree](https://www.w3.org/WAI/tutorials/images/decision-tree/).

<br>

## Decorative Images

<br>

Decorative images are the only image types that should not have any alt text, so a patron using a screen reader will skip past that element on a page. These are defined by the [Web Content Accessibility Guidelines](https://www.w3.org/WAI/tutorials/images/decorative/) as images that don't add information to the content of a page and can include:

- Visual styling such as borders, spacers, and corners;
- Supplementary to link text to improve its appearance or increase the clickable area;
- Illustrative of adjacent text but not contributing information (“eye-candy”);
- Identified and described by surrounding text.

{% include gallery-figure.html img="remed_pdf_21.jpg" alt="Highlight of an older U of I logo on a page." caption="Example of a decorative image." %}

Although this shouldn't really come up too much in LibGuides, if you do have a decorative element, simply leave the alt text field blank for the item so patrons using screen readers will skip over it.

<br>

## Complex images

<br>

While these elements don't seem to be incorporated in our LibGuides frequently, complex images such as charts and graphs need to have detailed descriptions in the body text that convey their full information. These images also need alt text that is less detailed but still conveys a sense of what is being communicated visually. An example from the [WCAG guide for creating alt text for complex visual images here](https://www.w3.org/WAI/tutorials/images/complex/):

- "Bar chart showing monthly and total visitors for the first quarter 2014 for sites 1 to 3, described in detail below."

This signposts to patrons using screen readers that this image will be unpacked shortly.

<br>

## PDFs

Check any PDF files that are being hosted onto our LibGuide or library servers, as we are responsible for making this material accessible. 