# IOPscience Accessibility Conformance Report International Edition
(Based on VPAT® Version 2.5rev)

**Name of Product/Version**: 21.77.0  
**Report Date**: 20 October 2025  
**Product Description**: Academic journal repository  
**Contact information**: jordan.rogers@ioppublishing.org, customerservices@ioppublishing.org  
**Notes**:  
**Evaluation Methods Used**: We evaluate accessibility compliance using a combination of manual and automated testing during development of the platform. We have partnered with an external supplier on multiple occasions to audit accessibility compliance. Any barriers discovered on the live version of the platform are reviewed and addressed as soon as possible.

## Applicable Standards/Guidelines

This report covers the degree of conformance for the following accessibility standard/guidelines:

<table cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td><strong>Standard/Guideline</strong></td>
<td nowrap><strong>Included In Report</strong></td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/2008/REC-WCAG20-20081211/">Web Content Accessibility Guidelines 2.0</a></td>
<td nowrap>Level A &nbsp; – &nbsp; <strong>Yes</strong><br>Level AA &nbsp; – &nbsp; <strong>Yes</strong><br>Level AAA &nbsp; – &nbsp; <strong>No</strong></td>
</tr>
<tr>
<td><a href="https://www.w3.org/TR/WCAG21">Web Content Accessibility Guidelines 2.1</a></td>
<td nowrap>Level A &nbsp; – &nbsp; <strong>Yes</strong><br>Level AA &nbsp; – &nbsp; <strong>Yes</strong><br>Level AAA &nbsp; – &nbsp; <strong>No</strong></td>
</tr>
<tr>
<td><a href="https://www.w3.org/TR/WCAG22/">Web Content Accessibility Guidelines 2.2</a></td>
<td nowrap>Level A &nbsp; – &nbsp; <strong>Yes</strong><br>Level AA &nbsp; – &nbsp; <strong>Yes</strong><br>Level AAA &nbsp; – &nbsp; <strong>No</strong></td>
<tr>
<td><a href="https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/final-rule/text-of-the-standards-and-guidelines">Revised Section 508 standards published January 18, 2017 and corrected January 22, 2018</a> </td>
<td nowrap><strong>Yes</strong></td>
</tr>
<tr>
<td><a href="https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.01.01_60/en_301549v030101p.pdf">EN 301 549 Accessibility requirements suitable for public procurement of ICT products and services in Europe, - V3.1.1 (2019-11)</a> <i>AND</i> <a href="https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf">EN 301 549 Accessibility requirements for ICT products and services - V3.2.1 (2021-03)</a> </td>
<td nowrap><strong>Yes</strong></td>
</tr>
</tbody>
</table>

## Terms

The terms used in the Conformance Level information are defined as follows:

- **Supports**: The functionality of the product has at least one method that meets the criterion without known defects or meets with equivalent facilitation.
- **Partially Supports**: Some functionality of the product does not meet the criterion.
- **Does Not Support**: The majority of product functionality does not meet the criterion.
- **Not Applicable**: The criterion is not relevant to the product.
- **Not Evaluated**: The product has not been evaluated against the criterion. This can be used only in WCAG Level AAA.

## WCAG 2.x Report<a name="wcag-2x-report"></a>

Tables 1 and 2 also document conformance with:
- EN 301 549:
  - Clause 9 - Web
  - Clauses 10.1-10.4 of Clause 10 - Non-Web documents
  - Clauses 11.1-11.4 and 11.8.2 of Clause 11 - Software
  - Clauses 12.1.2 and 12.2.4 of Clause 12 – Documentation and support services
- Revised Section 508:
  - Chapter 5 – 501.1 Scope, and 504.2 Content Creation or Editing
  - Chapter 6 – 602.3 Electronic Support Documentation

**Note**: When reporting on conformance with the WCAG 2.1 Success Criteria, they are scoped for full pages, complete processes, and accessibility-supported ways of using technology as documented in the [WCAG 2.1 Conformance Requirements](https://www.w3.org/TR/WCAG21/#conformance-reqs).

### Table 1: Success Criteria, Level A

<table>
<thead>
<tr>
<th><strong>Criteria</strong></th>
<th><strong>Conformance Level </strong></th>
<th><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr id="non-text-content" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#text-equiv-all"><strong>1.1.1 Non-text Content</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.1.1 (Web)</li>
<li>10.1.1.1 (Non-web document)</li>
<li>11.1.1.1.1 (Open Functionality Software)</li>
<li>11.1.1.1.2 (Closed Functionality Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Partially Supports<br><br>
Electronic Docs: Does Not Support
</td>
<td>
Web: Dedicated alternative text is not provided for figures in article and book content. Instead, we instruct users to reference the related figure caption. We acknowledge that the caption may not always provide equivalent information.<br><br>
There are a small number of images across the platform that are missing alternative text entirely, but we are working to identify these and provide descriptions.<br><br>
Electronic Docs: Text alternatives are not provided for non-text content.
</td>
</tr>
<tr id="audio-only-and-video-only-prerecorded" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-av-only-alt"><strong>1.2.1 Audio-only and Video-only (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.2.1 (Web)</li>
<li>10.1.2.1 (Non-web document)</li>
<li>11.1.2.1.1 (Open Functionality Software)</li>
<li>11.1.2.1.2.1 and 11.1.2.1.2.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Partially Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Video abstracts embedded in journal papers, provided by authors of journal papers, come with separate text transcript file.<br><br>
Occasionally we will publish video or audio content provided by third parties. This may not always be accompanied by a transcript.<br><br>
Electronic Docs: PDFs do not include audio or video media.
</td>
</tr>
<tr id="captions-prerecorded" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-captions"><strong>1.2.2 Captions (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.2.2 (Web)</li>
<li>10.1.2.2 (Non-web document)</li>
<li>11.1.2.2 (Open Functionality Software)</li>
<li>11.1.2.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: When necessary, videos have automated closed captions. These can be turned on and off within the video player interface along with options for caption text customisation.<br><br>
Electronic Docs: PDFs do not include videos.
</td>
</tr>
<tr id="audio-description-or-media-alternative-prerecorded" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc"><strong>1.2.3 Audio Description or Media Alternative (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.2.3 (Web)</li>
<li>10.1.2.3 (Non-web document)</li>
<li>11.1.2.3.1 (Open Functionality Software)</li>
<li>11.1.2.3.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Partially Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Video abstracts embedded in journal papers, provided by authors of journal papers, are accompanied by a text transcript file. We do not guarantee that all videos hosted on the platform include this.<br><br>
We currently do not provide any audio description for videos.<br><br>
Electronic Docs: PDFs do not include videos.
</td>
</tr>
<tr id="info-and-relationships" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-programmatic"><strong>1.3.1 Info and Relationships</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.3.1 (Web)</li>
<li>10.1.3.1 (Non-web document)</li>
<li>11.1.3.1.1 (Open Functionality Software)</li>
<li>11.1.3.1.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Does Not Support
</td>
<td>Web: The IOPscience platform is structured using semantic HTML patterns and has integrated Aria attributes where applicable to assist users of assistive technology in understanding the structure and content of web pages.<br><br>
We are aware that on some older pages there may be instances of incorrect heading levels being used. We are working to update this. All new content that is generated will follow the correct heading structure as defined in the WCAG 2.2 guidelines.<br><br>
Electronic Docs: We currently do not support PDF tagging and so document structure is not exposed to assistive technologies.
</td>
</tr>
<tr id="meaningful-sequence" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-sequence"><strong>1.3.2 Meaningful Sequence</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.3.2 (Web)</li>
<li>10.1.3.2 (Non-web document)</li>
<li>11.1.3.2.1 (Open Functionality Software)</li>
<li>11.1.3.2.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Partially Supports
</td>
<td>Web: Content is structured in a linear fashion to read in a logical order. If the order of items is manipulated using CSS and the visual order and programmatic order differ, this will never have any impact on the meaning of content and the overall page. This is mostly reserved for creating page layouts and positioning content labels and eyebrow elements.<br><br>
Electronic Docs: Content is presented in a visual logical reading order only, due to the absence of PDF tagging.
</td>
</tr>
<tr id="sensory-characteristics" valign="top">
<td><strong><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-understanding">1.3.3 Sensory Characteristics</a></strong> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.3.3 (Web)</li>
<li>10.1.3.3 (Non-web document)</li>
<li>11.1.3.3 (Open Functionality Software)</li>
<li>11.1.3.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Any inclusion of sensory characteristics in instructions for using content will be supplementary in nature and not crucial to the understanding of and interaction with content.</td>
</tr>
<tr id="use-of-color" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-without-color"><strong>1.4.1 Use of Color</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.4.1 (Web)</li>
<li>10.1.4.1 (Non-web document)</li>
<li>11.1.4.1 (Open Functionality Software)</li>
<li>11.1.4.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Partially Supports<br><br>
Electronic Docs: Partially Supports
</td>
<td>Web: We avoid using colour alone in the user interface of the website to convey information, however there may be some instances of author supplied content, such as figures, that do not fulfil this criterion. We have updated our author guidelines to educate and encourage the adoption of best practices around colour in data visualization, but we currently do not mandate that figures pass WCAG guidelines.<br><br>
Electronic Docs: Like Web, we cannot guarantee that all visual assets supplied by authors meet compliance.
</td>
</tr>
<tr id="audio-control" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-dis-audio"><strong>1.4.2 Audio Control</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.4.2 (Web)</li>
<li>10.1.4.2 (Non-web document)</li>
<li>11.1.4.2 (Open Functionality Software)</li>
<li>11.1.4.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: There is no audio that plays automatically for more than 3 seconds on IOPscience.</td>
</tr>
<tr id="keyboard" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-keyboard-operable"><strong>2.1.1 Keyboard</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.1.1 (Web)</li>
<li>10.1.1.1 (Non-web document)</li>
<li>11.1.1.1.1 (Open Functionality Software)</li>
<li>11.1.1.1.2 (Closed Functionality Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Partially Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: While most content can be navigated using a keyboard or a keyboard interface, interactive figures in articles and books cannot. Currently only a pointer style input, such as a mouse, can be used to navigate such figures.<br><br>
Electronic Docs: PDF documents only include links as interactive elements.
</td>
</tr>
<tr id="no-keyboard-trap" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-trapping"><strong>2.1.2 No Keyboard Trap</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.1.2 (Web)</li>
<li>10.2.1.2 (Non-web document)</li>
<li>11.2.1.2 (Open Functionality Software)</li>
<li>11.2.1.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: We make sure that keyboard focus does not become lost in the user interface. When content is presented in a modal, focus is moved to the first focusable element inside it. Focus is then intentionally trapped inside the modal, so it does not leave view. When closing a modal, focus is returned to the element that first opened it.<br><br>
Electronic Docs: We do not include any functionality in PDF documents which would present such a risk.
</td>
</tr>
<tr id="character-key-shortcuts" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#character-key-shortcuts"><strong>2.1.4 Character Key Shortcuts</strong></a> (Level A 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.1.4 (Web)</li>
<li>10.2.1.4 (Non-web document)</li>
<li>11.2.1.4.1 (Open Functionality Software)</li>
<li>11.2.1.4.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: IOPscience does not provide any keyboard shortcuts.</td>
</tr>
<tr id="timing-adjustable" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#time-limits-required-behaviors"><strong>2.2.1 Timing Adjustable</strong></a> (Level A 2.1 only)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.2.1 (Web)</li>
<li>10.2.2.1 (Non-web document)</li>
<li>11.2.2.1 (Open Functionality Software)</li>
<li>11.2.2.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: IOPscience does not contain any time limits.</td>
</tr>
<tr id="pause-stop-hide" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#time-limits-pause"><strong>2.2.2 Pause, Stop, Hide</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.2.2 (Web)</li>
<li>10.2.2.2 (Non-web document)</li>
<li>11.2.2.2 (Open Functionality Software)</li>
<li>11.2.2.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: The only instances of moving content on the website are rotating ad banners, served via Google’s advertising platform. In the top-right corner of each banner is a “More information” button, indicated by 3 vertical dots. Clicking on this button presents a new view, effectively pausing any motion. The button however does not have any visual label or programmatically accessible name, so it is not exposed to assistive technology.<br><br>
Electronic Docs: There is no moving, scrolling, or blinking content in documents.
</td>
</tr>
<tr id="three-flashes-or-below-threshold" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#seizure-does-not-violate"><strong>2.3.1 Three Flashes or Below Threshold</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.3.1 (Web)</li>
<li>10.2.3.1 (Non-web document)</li>
<li>11.2.3.1 (Open Functionality Software)</li>
<li>11.2.3.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: IOPscience does not contain any flashing content.</td>
</tr>
<tr id="bypass-blocks" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-skip"><strong>2.4.1 Bypass Blocks</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.4.1 (Web)</li>
<li>10.2.4.1 (Non-web document) – Does not apply</li>
<li>11.2.4.1 (Open Functionality Software) – Does not apply</li>
<li>11.2.4.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs) – Does not apply to non-web docs</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Where user interface elements are repeated across multiple web pages, a bypass block is provided to reach the main content of the page. These bypass blocks are only triggered when tabbing with a keyboard through the user interface.<br><br>
A ”Skip to content” is at the beginning of each page, allowing users to navigate directly to the main content.<br><br>
On pages with search functionality containing filters for content, skip links are implemented immediately before the filters to allow users to skip to search results.<br><br>
Page content is organized using ARIA landmarks with labels to allow users of assistive technology to navigate directly to blocks of content.<br><br>
Electronic Docs: Does not apply.
</td>
</tr>
<tr id="page-titled" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-title"><strong>2.4.2 Page Titled</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.4.2 (Web)</li>
<li>10.2.4.2 (Non-web document)</li>
<li>11.2.4.2 (Open Functionality Software) - Does not apply</li>
<li>11.2.4.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Partially Supports
</td>
<td>Web: All pages have descriptive titles, implemented with the HTML “title” element. These titles are used to label tabs in web browsers. A breadcrumb structure is used to ensure titles are unique and communicate to users their location within the website.<br><br>
Electronic Docs: PDFs display the file name, which consists of the author name, date published and journal name but is crucially missing the article title.<br><br>
Suitable titles already exist in the metadata of PDF documents. We are reviewing our production workflow to see if we can switch to using the document title by default.
</td>
</tr>
<tr id="focus-order" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-order"><strong>2.4.3 Focus Order</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.4.3 (Web)</li>
<li>10.2.4.3 (Non-web document)</li>
<li>11.2.4.3 (Open Functionality Software)</li>
<li>11.2.4.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Focus moves through web pages sequentially in an order that is logical. The tab order of pages matches the reading order, moving left to right, top to bottom. When content is injected dynamically into web pages, it is added in to the tab order at the same point where it was triggered, to retain a logical flow.<br><br>
Dialog windows and modals receive focus when opened. When closed, focus is returned to the invoking element.<br><br>
When using skip links, focus is moved to the first focusable element in the block of content that the skip links target. <br><br>
Electronic Docs: Focus moves in a linear fashion through PDF documents, matching the reading order.
</td>
</tr>
<tr id="link-purpose-in-context" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-refs"><strong>2.4.4 Link Purpose (In Context)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.4.4 (Web)</li>
<li>10.2.4.4 (Non-web document)</li>
<li>11.2.4.4 (Open Functionality Software)</li>
<li>11.2.4.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: Most links describe their destination and action through link text alone.<br><br>
Where the visible link label may not be sufficient, full context is provided utilising the “aria-label” and “aria-labelledby” attributes. For example, where the same link text is repeated on the page (e.g. “View abstract” on Journal pages with multiple articles), the ARIA attributes make them programmatically unique, by adding the article title.<br><br>
There are minimal instances where full link context cannot be determined from link text alone and relies on an enclosing paragraph. The W3C lists <a href="https://www.w3.org/WAI/WCAG22/Techniques/html/H78">combining link text with its enclosing paragraph as a sufficient technique</a>.
</td>
</tr>
<tr id="pointer-gestures" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#pointer-gestures"><strong>2.5.1 Pointer Gestures</strong></a> (Level A 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.5.1 (Web)</li>
<li>10.2.5.1 (Non-web document)</li>
<li>11.2.5.1 (Open Functionality Software)</li>
<li>11.2.5.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: IOPscience contains no content that relies on multipoint or path-based gestures.</td>
</tr>
<tr id="pointer-cancellation" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#pointer-gestures"><strong>2.5.2 Pointer Cancellation</strong></a> (Level A 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.5.2 (Web)</li>
<li>10.2.5.2 (Non-web document)</li>
<li>11.2.5.2 (Open Functionality Software)</li>
<li>11.2.5.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: No functionality is triggered on any type of platform down-event, such as “touchstart” and “mousedown”. If users accidentally click or touch a button by mistake, they can abort the action by simply moving the mouse pointer or finger away from the invoking element.</td>
</tr>
<tr id="label-in-name" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#label-in-name"><strong>2.5.3 Label in Name</strong></a> (Level A 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.5.3 (Web)</li>
<li>10.2.5.3 (Non-web document)</li>
<li>10.2.5.3 (Open Functionality Software)</li>
<li>11.2.5.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: Components are named to have a matching visible label and accessible name.<br><br>
Where more information is provided for users of assistive technology, this is added to the end of the accessible name. This is so speech-input users can still activate controls, even if the visible label and accessible name do not match, and labels do not lose meaning for text-to-speech users.<br><br>
There are few cases where contextual information is appended to the beginning of the accessible name, to help provide more understanding of the behavior of links. For example, on links that initiate a download of a file, the text “Download” is appended to the accessible name.
</td>
</tr>
<tr id="motion-actuation" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#motion-actuation"><strong>2.5.4 Motion Actuation</strong></a> (Level A 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.5.4 (Web)</li>
<li>10.2.5.4 (Non-web document)</li>
<li>11.2.5.4 (Open Functionality Software)</li>
<li>11.2.5.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: IOPScience has no functionality operated by device motion or user motion.</td>
</tr>
<tr id="language-of-page" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#meaning-doc-lang-id"><strong>3.1.1 Language of Page</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.3.1.1 (Web)</li>
<li>10.3.1.1 (Non-web document)</li>
<li>11.3.1.1.1 (Open Functionality Software)</li>
<li>11.3.1.1.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Does Not Support
</td>
<td>Web: All pages have the lang=”en” attribute in the HTML to define the language content is written in.<br><br>
Electronic Docs: We currently do not set the default language for PDF documents.
</td>
</tr>
<tr id="on-focus" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-receive-focus"><strong>3.2.1 On Focus</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.3.2.1 (Web)</li>
<li>10.3.2.1 (Non-web document)</li>
<li>11.3.2.1 (Open Functionality Software)</li>
<li>11.3.2.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: No changes in context are triggered by any control receiving focus. All changes rely on click and keypress events.</td>
</tr>
<tr id="on-input" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-unpredictable-change"><strong>3.2.2 On Input</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.3.2.2 (Web)</li>
<li>10.3.2.2 (Non-web document)</li>
<li>11.3.2.2 (Open Functionality Software)</li>
<li>11.3.2.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: Changing the setting of any user interface component does not automatically trigger a change of context. The user must manually trigger changes themselves (e.g. activating the “Apply” button after making any changes to search result filters). This ensures that the user interface responds in a predictable manner for users.</td>
</tr>
<tr id="consistent-help" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#consistent-help"><strong>3.2.6 Consistent Help</strong></a> (Level A 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
</td>
<td>Web: Supports</td>
<td>Web: Links to contact details and accessibility information can be found in the footer of the website on all pages.</td>
</tr>
<tr id="error-identification" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-identified"><strong>3.3.1 Error Identification</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.3.3.1 (Web)</li>
<li>10.3.3.1 (Non-web document)</li>
<li>11.3.3.1.1 (Open Functionality Software)</li>
<li>11.3.3.1.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Input errors are identified and communicated visually and programmatically so that users are made aware that entered data requires attention when necessary. Errors are displayed in a red box with black text, immediately next to the related input.<br><br>
For search type inputs, an error will be displayed if no terms are entered before attempting to perform a search, or if the entered information is not in the requested format.<br><br>
On forms with more inputs, errors are displayed in red text immediately below their related inputs. A summary of errors is also prepended to the form with the “alert” role, to communicate to users of assistive technology that attention is required. Error text is programmatically connected to its related inputs using “aria-describedby” attributes.<br><br>
Electronic Docs: Not applicable to PDFs.
</td>
</tr>
<tr id="labels-or-instructions" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-cues"><strong>3.3.2 Labels or Instructions</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.3.3.2 (Web)</li>
<li>10.3.3.2 (Non-web document)</li>
<li>11.3.3.2 (Open Functionality Software)</li>
<li>11.3.3.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>

<td>Web: A text label either proceeds or follows any form element. This either states the entry element required in the form or instructs the user as to how to interact with the element. Explicit relationships between elements and labels are created by utilising the <code>&lt;label&gt;</code> <code>for</code> attribute. We use semantic grouping for related form controls, by using a structure of <code>&lt;legend&gt;</code> and <code>&lt;fieldset&gt;</code> elements.<br><br>
Even if a label is visually hidden, it will still be programmatically associated with its related element so that assistive technologies can access it.<br><br>
Note: The “Article lookup” search form found in the top navigation bar of the website does provide error feedback, but the requirements for performing successful searches are not communicated ahead of time. We are working on adding instruction to the form to assist users.<br><br>
Electronic Docs: Not applicable to PDFs.
</td>
</tr>
<tr id="redundant-entry" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#redundant-entry"><strong>3.3.7 Redundant Entry</strong></a> (Level A 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
</td>
<td>Web: Supports</td>
<td>Web: There are no instances on IOPscience where a user would be required to enter the same information more than once as part of the same process.</td>
</tr>
<tr id="parsing" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-parses"><strong>4.1.1 Parsing</strong></a> (Level A)
<br><br>Also applies to:<br><br>
 WCAG 2.0 and 2.1 – Always answer ‘Supports’<br><br>
 WCAG 2.2 (obsolete and removed) - Does not apply<br><br>  
EN 301 549 Criteria
<ul>
<li>9.4.1.1 (Web)</li>
<li>10.4.1.1 (Non-web document)</li>
<li>11.4.1.1.1 (Open Functionality Software)</li>
<li>11.4.1.1.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Supports</td>
<td>For WCAG 2.0, 2.1, EN 301 549, and Revised 508 Standards, the September 2023 errata update indicates this criterion is always supported. See the <a href="https://www.w3.org/WAI/WCAG20/errata/#editorial">WCAG 2.0 Editorial Errata</a> and <a href="https://www.w3.org/WAI/WCAG21/errata/#editorial">the WCAG 2.1 Editorial Errata</a>.</td>
</tr>
<tr id="name-role-value" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-rsv"><strong>4.1.2 Name, Role, Value</strong></a> (Level A)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.4.1.2 (Web)</li>
<li>10.4.1.2 (Non-web document)</li>
<li>11.4.1.2.1 (Open Functionality Software)</li>
<li>11.4.1.2.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Partially Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: A combination of standard text, HTML attributes and ARIA attributes are used to communicate the Name, Role and Value of user interface components to assistive technology.<br><br>
Content that expands and collapses is given the <code>aria-expanded</code> attribute to communicate its current state.<br><br>
For links with the same label repeated on the same page, additional context is provided through the <code>aria-label</code> and <code>aria-labelledby</code> attributes to ensure they are unique and meaningful to users of assistive technology.<br><br>
For links that are repeated and go to the same destination, the same label and accessible name is used, so that they may be consistently identified.<br><br>
There are instances where the styles of links and buttons are interchangeable. The correct role is manually applied along with the native browser behaviour.<br><br>
Adverts are inserted in pages using iFrames. These frames are all titled “3rd party ad content”.<br><br>
Advertising banners have button controls within them that do not have a visible label or an accessible name, so their function is not clear to users of assistive technology.<br><br>
Electronic Docs: Not applicable to PDFs.
</td>
</tr>
</tbody>
</table>

### Table 2: Success Criteria, Level AA

<table>
<thead>
<tr>
<th><strong>Criteria</strong></th>
<th><strong>Conformance Level </strong></th>
<th><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr id="captions-live" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-real-time-captions"><strong>1.2.4 Captions (Live)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.2.4 (Web)</li>
<li>10.1.2.4 (Non-web document)</li>
<li>11.1.2.4 (Open Functionality Software)</li>
<li>11.1.2.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: IOPscience does not contain any live audio.<br><br>
Electronic Docs: PDFs do not include live video.
</td>
</tr>
<tr id="audio-description-prerecorded" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc-only"><strong>1.2.5 Audio Description (Prerecorded)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.2.5 (Web)</li>
<li>10.1.2.5 (Non-web document)</li>
<li>11.1.2.5 (Open Functionality Software)</li>
<li>11.1.2.5 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Does Not Support<br><br>
Electronic Docs: Supports
</td>
<td>Web: Audio descriptions tracks are not available for video content. We are reviewing our media production process to explore how we may be able to support this in the future.<br><br>
Electronic Docs: PDFs do not include video.
</td>
</tr>
<tr id="orientation" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#orientation"><strong>1.3.4 Orientation</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.3.4 (Web)</li>
<li>10.1.3.4 (Non-web document)</li>
<li>11.1.3.4 (Open Functionality Software)</li>
<li>11.1.3.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: The layout and operation of the content will adapt to the orientation of the user’s display device (e.g. portrait and landscape modes).</td>
</tr>
<tr id="identify-input-purpose" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#identify-input-purpose"><strong>1.3.5 Identify Input Purpose</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.3.5 (Web)</li>
<li>10.1.3.5 (Non-web document)</li>
<li>11.1.3.5 (Open Functionality Software)</li>
<li>11.1.3.5 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Support<br><br>
Electronic Docs: Supports
</td>
<td>Web: <code>&lt;input&gt;</code> elements are assigned a “type” attribute to help users understand what information should be entered. The HTML autocomplete attribute is assigned to appropriate form fields so that they may be populated by autofill values stored in the user’s browser.<br><br>
Electronic Docs: PDFs do not include inputs.
</td>
</tr>
<tr id="contrast-minimum" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-contrast"><strong>1.4.3 Contrast (Minimum)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.4.3 (Web)</li>
<li>10.1.4.3 (Non-web document)</li>
<li>11.1.4.3 (Open Functionality Software)</li>
<li>11.1.4.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Partially Supports<br><br>
Electronic Docs: Partially Supports
</td>
<td>Web/Electronic Docs: All text and background colour combinations in the user interface have at least a contrast ratio of 4.5:1.<br><br>
We cannot guarantee that author supplied content, such as figures, will always meet minimum contrast. Figures are accompanied with a caption to aid in the understanding of the visual information being presented.
</td>
</tr>
<tr id="resize-text" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-scale"><strong>1.4.4 Resize text</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.4.4 (Web)</li>
<li>10.1.4.4 (Non-web document)</li>
<li>11.1.4.4.1 (Open Functionality Software)</li>
<li>11.1.4.4.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: Text can be resized up to 200% without loss of content or functionality.</td>
</tr>
<tr id="images-of-text" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-text-presentation"><strong>1.4.5 Images of Text</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.4.5 (Web)</li>
<li>10.1.4.5 (Non-web document)</li>
<li>11.1.4.5.1 (Open Functionality Software)</li>
<li>11.1.4.5.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: Images of text are not used on IOPscience.<br><br>
Author supplied figures do contain images of text, but as they contain significant other visual content they are exempt, according to the <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-text-presentation.html#images-of-textdef">WCAG definition of images of text</a>.<br><br>
Text in Journal and Book cover images are also exempt under the same definition.<br><br>
IOPscience and 3rd party logos are included in the following areas:
<ul>
<li>IOPscience logo in the site navigation bar</li>
<li>Journal and partner logos on journal and article pages</li>
<li>ORCID ID logos next to author names on article pages</li>
<li>Physics World Jobs logo at the top of the jobs board section on article pages</li>
</ul>
Logos are also exempt from meeting the criteria based on WCAG’s definition, as the visual presentation of the text is essential to the identity of the logo.
</td>
</tr>
<tr id="reflow" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#reflow"><strong>1.4.10 Reflow</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.4.10 (Web)</li>
<li>10.1.4.10 (Non-web document)</li>
<li>11.1.4.10.1 (Open Functionality Software)</li>
<li>11.1.4.10.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Web pages use a responsive layout that will adjust to the available screen space. For larger displays, such as desktops, layouts may be split into multiple columns. For smaller devices such as smartphones, layouts will collapse into a single column to make sure all information is visible on screen without the need to scroll in multiple directions simultaneously.<br><br>
Note: When logged in to MyIOPscience, the “E-mail alerts tab does not reduce in width enough to properly display all information on devices with a screen width of 320px. We are updating our stylesheets to ensure that all content wraps and is visible on screen.<br><br>
Note: On book pages, for viewports that have a width of 767px and less, the book download buttons are fixed to the bottom of the screen. At a width of 320px, the buttons become obstructed by the cookie consent button, which itself is pinned to the bottom left of the screen.<br><br>
Electronic Docs: PDFs do not support reflow, as they are static in layout by nature.
</td>
</tr>
<tr id="non-text-contrast" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#non-text-contrast"><strong>1.4.11 Non-text Contrast</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.4.11 (Web)</li>
<li>10.1.4.11 (Non-web document)</li>
<li>11.1.4.11 (Open Functionality Software)</li>
<li>11.1.4.11 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Partially Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Graphical elements such as icons have a minimum contrast of 3.1:1.<br><br>
Underline used to identify the hover state of links have a minimum contrast of 3.1:1 with background colours.<br><br>
Focused links receive a block background colour that is at least 3.1:1 contrast with both the link text and the surrounding background.<br><br>
Some third-party logos (e.g. ORCID ID) do not meet the minimum contrast. <a href="https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html#essential-exception">Logos are exempt</a>, as changing the colour to meet sufficient contrast may mean they are no longer identifiable.<br><br>
We cannot guarantee that colours used in all figures supplied by authors meet contrast requirements, but we have updated our author guidance to inform and encourage adoption of the requirement in data visualisation.
</td>
</tr>
<tr id="text-spacing" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#text-spacing"><strong>1.4.12 Text Spacing</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.4.12 (Web)</li>
<li>10.1.4.12 (Non-web document)</li>
<li>11.1.4.12 (Open Functionality Software)</li>
<li>11.1.4.12 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: When testing pages against the following criteria, the majority did not experience any loss of content or functionality:
<ul>
<li>Line height (line spacing) to at least 1.5 times the font size;</li>
<li>Spacing following paragraphs to at least 2 times the font size;</li>
<li>Letter spacing (tracking) to at least 0.12 times the font size;</li>
<li>Word spacing to at least 0.16 times the font size.</li>
</ul>
Note: On the Home page, the headings of the news feeds overlap the “RSS feed” links. We are updating our stylesheets to fix this.<br><br>
Electronic Docs: No requirement for PDF documents as they use a fixed content layout.
</td>
</tr>
<tr id="content-on-hover-or-focus" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#content-on-hover-or-focus"><strong>1.4.13 Content on Hover or Focus</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.1.4.13 (Web)</li>
<li>10.1.4.13 (Non-web document)</li>
<li>11.1.4.13 (Open Functionality Software)</li>
<li>11.1.4.13 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Tooltips can be accessed and dismissed via mouse and/or keyboard input.<br><br>
Electronic Docs: Our PDF documents do not include any content that is revealed on hover or focus.
</td>
</tr>
<tr id="multiple-ways" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-mult-loc"><strong>2.4.5 Multiple Ways</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.4.5 (Web)</li>
<li>10.2.4.5 (Non-web document) – Does not apply</li>
<li>11.2.4.5 (Open Functionality Software) – Does not apply</li>
<li>11.2.4.5 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs) – Does not apply to non-web docs</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Core content, including journal articles and book chapters can be accessed through the Journals and Books home pages, and the site wide search functionality.<br><br>
Journal alerts can be accessed in the “My IOPscience” dashboard under the “E-mail alerts” tab, or through links on Journal home and article pages.
</td>
</tr>
<tr id="headings-and-labels" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-descriptive"><strong>2.4.6 Headings and Labels</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.4.6  (Web)</li>
<li>10.2.4.6 (Non-web document)</li>
<li>11.2.4.6 (Open Functionality Software)</li>
<li>11.2.4.6 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/ Electronic Docs: All headings and labels are descriptive of their related content.</td>
</tr>
<tr id="focus-visible" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-visible"><strong>2.4.7 Focus Visible</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.2.4.7 (Web)</li>
<li>10.2.4.7 (Non-web document)</li>
<li>11.2.4.7 (Open Functionality Software)</li>
<li>11.2.4.7 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Partially Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Most interactive elements have a suitable focus indicator.<br><br>
There are different styles of focus indicator depending on the element type:
<ul>
<li>Links – Red (#cc0000) background with white (#ffffff) text</li>
<li>Footer links – White (#ffffff) background with dark grey (#333333) text</li>
<li>Linked images – Red (#cc0000) and white (#ffffff) outline</li>
<li>Buttons – Red (#cc0000) background with white (#ffffff) square brackets wrapping the button text.</li>
<li>Site wide navigation menu items – Red (#cc0000) background with a white (#ffffff) bottom border.</li>
</ul>
<strong>Known issues</strong><br>
Some ad banners do not display a focus indicator when focused.<br><br>
Electronic Docs: Focus in PDF documents uses default system styles.
</td>
</tr>
<tr id="focus-not-obscured-minimum" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum"><strong>2.4.11 Focus Not Obscured (Minimum)</strong></a> (Level AA 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
<td>Web: Supports</td>
<td>Web: The focus indicator is always visible.</td>
</tr>
<tr id="dragging-movements" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#dragging-movements"><strong>2.5.7 Dragging Movements</strong></a> (Level AA 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
<td>Web: Does Not Support</td>
<td>Web: Interactive figures in Journal and Books content rely on dragging movements to interact with them, however dragging is not required to understand them. Figures are initially presented as a static image, and the interactive versions can be turned on and off by the user.</td>
</tr>
<tr id="target-size-minimum" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#target-size-minimum"><strong>2.5.8 Target Size (Minimum)</strong></a> (Level AA 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
<td>Web: Supports</td>
<td>Web: IOPscience uses targets with minimum dimensions of 24 by 24 CSS pixels. Undersized targets are accommodated with extra space around them, so that other targets are at least a distance of 24 CSS pixels away.</td>
</tr>
<tr id="language-of-parts" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#meaning-other-lang-id"><strong>3.1.2 Language of Parts</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.3.1.2 (Web)</li>
<li>10.3.1.2 (Non-web document)</li>
<li>11.3.1.2 (Open Functionality Software) – Does not apply</li>
<li>11.3.1.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Does Not Support
</td>
<td>Web: If any page content changes from the default language of the page, this is expressed programmatically using the HTML <code>lang</code> attribute with a suitable value on the containing element.<br><br>
Electronic Docs: As we do not currently tag PDF documents, any change in language from the default for the document is not communicated.
</td>
</tr>
<tr id="consistent-navigation" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-locations"><strong>3.2.3 Consistent Navigation</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.3.2.3 (Web)</li>
<li>10.3.2.3 (Non-web document) – Does not apply</li>
<li>11.3.2.3 (Open Functionality Software) – Does not apply</li>
<li>11.3.2.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs) – Does not apply to non-web docs</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: The website header and footer navigation menus are the same across all pages.<br><br>
On pages that support search and/or filter functionality, filters are positioned on the left and content results on the right. <br><br>
On pages with pagination, controls are positioned immediately below content on the right side.<br><br>
A “skip to content” link is provided at the top of each page.<br><br>
</td>
</tr>
<tr id="consistent-identification" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-functionality"><strong>3.2.4 Consistent Identification</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.3.2.4 (Web)</li>
<li>10.3.2.4 (Non-web document) – Does not apply</li>
<li>11.3.2.4 (Open Functionality Software) – Does not apply</li>
<li>11.3.2.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs) – Does not apply to non-web docs</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>We use a consistent style for user interface components with functionality to help the user understand the functionality when appearing across multiple pages.<br><br>
User interface components that are repeated across multiple pages have consistent labelling and styling.<br><br>
Icons are used to identify controls for downloading electronic documents (e.g. PDF, Kindle, EPUB)<br><br>
Components with specific scripted functionality (e.g. collapsible sections) are identified with the same icon.
</td>
</tr>
<tr id="error-suggestion" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-suggestions"><strong>3.3.3 Error Suggestion</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.3.3.3 (Web)</li>
<li>10.3.3.3 (Non-web document)</li>
<li>11.3.3.3 (Open Functionality Software)</li>
<li>11.3.3.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: If an error is identified, it is described and a solution for correction is offered.<br><br>
When errors are detected, the conditions triggering the error and suggestions for correction are provided.<br><br>
Required form fields that are left blank will result in an error message that the field must be populated to successfully submit the form.<br><br>
Electronic Docs: Not applicable to PDFs.
</td>
</tr>
<tr id="error-prevention-legal-financial-data" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-reversible"><strong>3.3.4 Error Prevention (Legal, Financial, Data)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.3.3.4 (Web)</li>
<li>10.3.3.4 (Non-web document)</li>
<li>11.3.3.4 (Open Functionality Software)</li>
<li>11.3.3.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web/Electronic Docs: IOPscience does not have pages that included legal commitments or financial transactions.</td>
</tr>
<tr id="accessible-authentication-minimum" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#accessible-authentication-minimum"><strong>3.3.8 Accessible Authentication (Minimum)</strong></a> (Level AA 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
<td>Web: Supports</td>
<td>Web: The form fields during the login process have autocomplete enabled to allow the username and password to be populated by browsers and password managers.<br><br>
The form fields also allow copy/paste functionality to avoid retyping entire usernames and passwords.
</td>
</tr>
<tr id="status-messages" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#status-messages"><strong>4.1.3 Status Messages</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
EN 301 549 Criteria
<ul>
<li>9.4.1.3 (Web)</li>
<li>10.4.1.3 (Non-web document)</li>
<li>11.4.1.3 (Open Functionality Software)</li>
<li>11.4.1.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
Revised Section 508 - does not apply
</td>
<td>Web: Supports<br><br>
Electronic Docs: Supports
</td>
<td>Web: Status messages are presented for both success and failure states.<br><br>
Note: Some status and error message containers are injected dynamically into the page. For more robust screen reader support, these containers should be present on page load instead. We are working on making this change in the user interface.<br><br>
Some status messages currently are assigned the role “alert” when it would be more appropriate to use “status” instead. We are working on updating this.<br><br>
Electronic Docs: Not applicable to PDFs.
</td>
</tr>
</tbody>
</table>

### Table 3: Success Criteria, Level AAA

Notes: This product has not been evaluated for WCAG 2.x Level AAA conformance.

## Revised Section 508 Report

### Chapter 3: [Functional Performance Criteria](https://www.access-board.gov/ict/#chapter-3-functional-performance-criteria) (FPC)

<table>
<thead>
<tr>
<th scope="col"><strong>Criteria</strong></th>
<th scope="col"><strong>Conformance Level</strong></th>
<th scope="col"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>302.1 Without Vision</td>
<td>Supports</td>
<td>The IOPscience user interface is constructed using semantic HTML and ARIA attributes where applicable, to help provide support for a variety of assistive technologies such as screen readers.</td>
</tr>
<tr>
<td>302.2 With Limited Vision</td>
<td>Supports</td>
<td>The website supports the use of assistive technology and provides for content to be magnified, and colour and contrast adjusted.</td>
</tr>
<tr>
<td>302.3 Without Perception of Color</td>
<td>Supports</td>
<td>We avoid using colour alone to convey information.</td>
</tr>
<tr>
<td>302.4 Without Hearing</td>
<td>Supports</td>
<td>Hearing alone is not necessary to navigate the core content of the website.  Videos have closed captions.</td>
</tr>
<tr>
<td>302.5 With Limited Hearing</td>
<td>Supports</td>
<td></td>
</tr>
<tr>
<td>302.6 Without Speech</td>
<td>Supports</td>
<td>Speech input is not required.</td>
</tr>
<tr>
<td>302.7 With Limited Manipulation</td>
<td>Supports</td>
<td>The user interface is designed to support a variety of input methods. For touch navigation, on devices that support it, elements are designed to be large enough to not require very precise movements.</td>
</tr>
<tr>
<td>302.8 With Limited Reach and Strength</td>
<td>Not Applicable</td>
<td></td>
</tr>
<tr>
<td>302.9 With Limited Language, Cognitive, and Learning Abilities</td>
<td>Partially Supports</td>
<td>Content is presented in a clean and logical layout, with plenty of space to avoid overloading of information on screen.  Due to the nature of the content, many abbreviations and acronyms are present within it.</td>
</tr>
</tbody>
</table>

### Chapter 4: [Hardware](https://www.access-board.gov/ict/#chapter-4-hardware)

Notes: This product is a web software application and is not subject to the requirements of this chapter.

### Chapter 5: [Software](https://www.access-board.gov/ict/#chapter-5-software)

<table>
<thead>
<tr>
<th scope="col" id="chap-5-criteria"><strong>Criteria</strong></th>
<th scope="col" id="chap-5-conformance"><strong>Conformance Level</strong></th>
<th scope="col" id="chap-5-remarks"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>501.1 Scope – Incorporation of WCAG 2.x AA</td>
<td>See <a href="#wcag-2x-report">WCAG 2.x</a> section</td>
<td>See information in WCAG section</td>
</tr>
<tr>
<th scope="column" colspan="3" id="502-interop"><a href="https://www.access-board.gov/ict/#502-interoperability-assistive-technology">502 Interoperability with Assistive Technology</a></th>
</tr>
<tr>
<td headers="502-interop chap-5-criteria">502.2.1 User Control of Accessibility Features</td>
<td headers="502-interop chap-5-conformance"></td>
<td headers="502-interop chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-interop chap-5-criteria">502.2.2 No Disruption of Accessibility Features</td>
<td headers="502-interop chap-5-conformance"></td>
<td headers="502-interop chap-5-remarks"></td>
</tr>
<tr>
<th scope="column" colspan="3" id="502-services">502.3 Accessibility Services</th>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.1 Object Information</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.2 Modification of Object Information</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.3 Row, Column, and Headers</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.4 Values</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.5 Modification of Values</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.6 Label Relationships</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.7 Hierarchical Relationships</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.8 Text</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.9 Modification of Text</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.10 List of Actions</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.11 Actions on Objects</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.12 Focus Cursor</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.13 Modification of Focus Cursor</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.14 Event Notification</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.4 Platform Accessibility Features</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks"></td>
</tr>
<tr>
<th scope="column" colspan="3" id="503-apps"><a href="https://www.access-board.gov/ict/#503-applications">503 Applications</a></th>
</tr>
<tr>
<td headers="503-apps chap-5-criteria">503.2 User Preferences</td>
<td headers="503-apps chap-5-conformance"></td>
<td headers="503-apps chap-5-remarks"></td>
</tr>
<tr>
<td headers="503-apps chap-5-criteria">503.3 Alternative User Interfaces</td>
<td headers="503-apps chap-5-conformance"></td>
<td headers="503-apps chap-5-remarks"></td>
</tr>
<tr>
<th scope="column" colspan="3" id="503-usercon">503.4 User Controls for Captions and Audio Description</th>
</tr>
<tr>
<td headers="503-usercon chap-5-criteria">503.4.1 Caption Controls</td>
<td headers="503-usercon chap-5-conformance"></td>
<td headers="503-usercon chap-5-remarks"></td>
</tr>
<tr>
<td headers="503-usercon chap-5-criteria">503.4.2 Audio Description Controls</td>
<td headers="503-usercon chap-5-conformance"></td>
<td headers="503-usercon chap-5-remarks"></td>
</tr>
<tr>
<th scope="column" colspan="3" id="504-authoring"><a href="https://www.access-board.gov/ict/#504-authoring-tools">504 Authoring Tools</a></th>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.2 Content Creation or Editing (if not authoring tool, enter “not applicable”)</td>
<td headers="504-authoring chap-5-conformance">See <a href="#wcag-2x-report">WCAG 2.x</a> section</td>
<td headers="504-authoring chap-5-remarks">See information in WCAG section</td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.2.1 Preservation of Information Provided for Accessibility in Format Conversion</td>
<td headers="504-authoring chap-5-conformance"></td>
<td headers="504-authoring chap-5-remarks"></td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.2.2 PDF Export</td>
<td headers="504-authoring chap-5-conformance"></td>
<td headers="504-authoring chap-5-remarks"></td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.3 Prompts</td>
<td headers="504-authoring chap-5-conformance"></td>
<td headers="504-authoring chap-5-remarks"></td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.4 Templates</td>
<td headers="504-authoring chap-5-conformance"></td>
<td headers="504-authoring chap-5-remarks"></td>
</tr>
</tbody>
</table>

### Chapter 6: [Support Documentation and Services](https://www.access-board.gov/ict/#chapter-6-support-documentation-and-services)

<table>
<thead>
<tr>
<th scope="col" id="chap-6-criteria"><strong>Criteria</strong></th>
<th scope="col" id="chap-6-conformance"><strong>Conformance Level</strong></th>
<th scope="col" id="chap-6-remarks"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>601.1 Scope</td>
<td></td>
<td></td>
</tr>
<tr>
<th scope="column" colspan="3" id="602-documentation"><a href="https://www.access-board.gov/ict/#602-support-documentation">602 Support Documentation</a></th>
</tr>
<tr>
<td headers="602-documentation chap-6-criteria">602.2 Accessibility and Compatibility Features</td>
<td headers="602-documentation chap-6-conformance">Partially Supports</td>
<td headers="602-documentation chap-6-remarks">We stick to using traditional and recommended design patterns for accessible components.<br><br>
Full details about application and usage can be found in our Accessibility statement: <a href="https://iopscience.iop.org/page/accessibility">https://iopscience.iop.org/page/accessibility</a>.     <br><br>
Support provided via email at <a href="mailto:customerservices@ioppublishing.org">customerservices@ioppublishing.org</a>. 
</td>
</tr>
<tr>
<td headers="602-documentation chap-6-criteria">602.3 Electronic Support Documentation</td>
<td headers="602-documentation chap-6-conformance">See <a href="#wcag-2x-report">WCAG 2.x</a> section</td>
<td headers="602-documentation chap-6-remarks">See information in WCAG 2.x section</td>
</tr>
<tr>
<td headers="602-documentation chap-6-criteria">602.4 Alternate Formats for Non-Electronic Support Documentation</td>
<td headers="602-documentation chap-6-conformance">Supports</td>
<td headers="602-documentation chap-6-remarks">Support provided via email at <a href="mailto:customerservices@ioppublishing.org">customerservices@ioppublishing.org</a></td>
</tr>
<tr>
<th scope="column" colspan="3" id="603-services"><a href="https://www.access-board.gov/ict/#603-support-services">603 Support Services</a></th>
</tr>
<tr>
<td headers="603-services chap-6-criteria">603.2 Information on Accessibility and Compatibility Features</td>
<td headers="603-services chap-6-conformance">Supports</td>
<td headers="603-services chap-6-remarks">Full details about application and usage can be found in our Accessibility statement: <a href="https://iopscience.iop.org/page/accessibility">https://iopscience.iop.org/page/accessibility</a><br><br>
Support provided via email at <a href="mailto:customerservices@ioppublishing.org">customerservices@ioppublishing.org</a>.
</td>
</tr>
<tr>
<tr>
<td headers="603-services chap-6-criteria">603.3 Accommodation of Communication Needs</td>
<td headers="603-services chap-6-conformance">Supports</td>
<td headers="603-services chap-6-remarks"></td>
</tr>
</tbody>
</table>

## EN 301 549 Report

### Clause 4: [4.2 Functional Performance Statements](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=20) (FPS)

<table>
<thead>
<tr>
<th scope="col"><strong>Criteria</strong></th>
<th scope="col"><strong>Conformance Level</strong></th>
<th scope="col"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>4.2.1 Usage without vision</td>
<td>Supports</td>
<td>The IOPscience user interface is constructed using semantic HTML and ARIA attributes where applicable, to help provide support for a variety of assistive technologies such as screen readers.</td>
</tr>
<tr>
<td>4.2.2 Usage with limited vision</td>
<td>Supports</td>
<td>The website supports the use of assistive technology and provides for content to be magnified, and colour and contrast adjusted.</td>
</tr>
<tr>
<td>4.2.3 Usage without Perception of Color</td>
<td>Supports</td>
<td>We avoid using colour alone to convey information.</td>
</tr>
<tr>
<td>4.2.4 Usage without hearing</td>
<td>Supports</td>
<td>Hearing alone is not necessary to navigate the core content of the website.  Videos have closed captions.</td>
</tr>
<tr>
<td>4.2.5 Usage with limited hearing</td>
<td>Supports</td>
<td>Hearing alone is not necessary to navigate the core content of the website.  Videos have closed captions.</td>
</tr>
<tr>
<td>4.2.6 Usage without vocal capability</td>
<td>Supports</td>
<td>Speech input is not required.</td>
</tr>
<tr>
<td>4.2.7 Usage with limited manipulation or strength</td>
<td>Supports</td>
<td>The user interface is designed to support a variety of input methods. For touch navigation, on devices that support it, elements are designed to be large enough to not require very precise movements.</td>
</tr>
<tr>
<td>4.2.8 Usage with limited reach</td>
<td>Not Applicable</td>
<td></td>
</tr>
<tr>
<td>4.2.9 Minimize photosensitive seizure triggers</td>
<td>Supports</td>
<td>We do not display any content with a high flashing or flicker rate.</td>
</tr>
<tr>
<td>4.2.10 Usage with limited cognition</td>
<td>Partially Supports</td>
<td>Content is presented in a clean and logical layout, with plenty of space to avoid overloading of information on screen.  Due to the nature of the content, many abbreviations and acronyms are present within it.</td>
</tr>
<tr>
<td>4.2.11 Privacy</td>
<td></td>
<td></td>
</tr>
</tbody>
</table>

### Clause [5: Generic Requirements](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=23)

Notes: This product supports standard web assistive technologies and is therefore not subject to the Closed Functionality criteria described in this chapter.

### Clause [6: ICT with Two-Way Voice Communication](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=30)

Notes: This product does not offer two-way voice communication and is therefore not subject to the requirements of this chapter.

### Clause [7: ICT with Video Capabilities](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=35)

Notes:

<table>
<thead>
<tr>
<th scope="col" id="chap-7-criteria"><strong>Criteria</strong></th>
<th scope="col" id="chap-7-conformance"><strong>Conformance Level</strong></th>
<th scope="col" id="chap-7-remarks"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<th scope="column" colspan="3" id="7-caption">7.1 Caption processing technology</th>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.1 Captioning playback</td>
<td headers="7-caption chap-7-conformance">Supports</td>
<td headers="7-caption chap-7-remarks"></td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.2 Captioning synchronization</td>
<td headers="7-caption chap-7-conformance">Supports</td>
<td headers="7-caption chap-7-remarks"></td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.3 Preservation of captioning</td>
<td headers="7-caption chap-7-conformance">Supports</td>
<td headers="7-caption chap-7-remarks"></td>
</tr>
<tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.4 Captions characteristics</td>
<td headers="7-caption chap-7-conformance">Supports</td>
<td headers="7-caption chap-7-remarks"></td>
</tr>
<tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.5 Spoken subtitles</td>
<td headers="7-caption chap-7-conformance">Does Not Support</td>
<td headers="7-caption chap-7-remarks"></td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.2.1 Audio description playback</td>
<td headers="7-caption chap-7-conformance">Does Not Support</td>
<td headers="7-caption chap-7-remarks"></td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.2.2 Audio description synchronization</td>
<td headers="7-caption chap-7-conformance">Does Not Support</td>
<td headers="7-caption chap-7-remarks"></td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.2.3 Preservation of audio description</td>
<td headers="7-caption chap-7-conformance">Does Not Support</td>
<td headers="7-caption chap-7-remarks"></td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.3 User controls for captions and audio description</td>
<td headers="7-caption chap-7-conformance">Supports</td>
<td headers="7-caption chap-7-remarks"></td>
</tr>
</tbody>
</table>                                  

### Clause [8: Hardware](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=37)

Notes: This product is a web software application and is not subject to the requirements of this chapter.

### Clause [9: Web](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=45) <i>(See [WCAG 2.x section](#wcag-2x-report))</i>

Notes:

### Clause [10: Non-web Documents](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=52)

Notes: This product does not include non-web documents and is therefore not subject to the requirements of this chapter.

### Clause [11: Software](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=64)

Notes: This section has been removed. IOPscience does not provide software.

### Clause [12: Documentation and Support Services](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=84)

Notes:

<table>
<thead>
<tr>
<th scope="col" id="chap-12-criteria"><strong>Criteria</strong></th>
<th scope="col" id="chap-12-conformance"><strong>Conformance Level</strong></th>
<th scope="col" id="chap-12-remarks"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<th scope="column" colspan="3" id="12-1-documentation">12.1 Product documentation</th>
</tr>
<tr>
<td headers="12-1-documentation chap-12-criteria">12.1.1 Accessibility and compatibility features</td>
<td headers="12-1-documentation chap-12-conformance">Supports</td>
<td headers="12-1-documentation chap-12-remarks">We stick to using traditional and recommended design patterns for accessible components.<br><br>
Full details about application and usage can be found in our Accessibility statement: <a href="https://iopscience.iop.org/page/accessibility">https://iopscience.iop.org/page/accessibility</a>.     <br><br>
Support provided via email at <a href="mailto:customerservices@ioppublishing.org">customerservices@ioppublishing.org</a>. 
</td>
</tr>
<tr>
<td headers="12-1-documentation chap-12-criteria">12.1.2 Accessible documentation</td>
<td headers="12-1-documentation chap-12-conformance">See <a href="#wcag-2x-report">WCAG 2.x</a> section</td>
<td headers="12-1-documentation chap-12-remarks">See information in WCAG 2.x section</td>
</tr>
<tr>
<th scope="column" colspan="3" id="12-2-support">12.2 Support Services</th>
</tr>
<tr>
<td headers="12-2-support chap-12-criteria">12.2.2 Information on accessibility and compatibility features</td>
<td headers="12-2-support chap-12-conformance">Supports</td>
<td headers="12-2-support chap-12-remarks">Any additional support may be requested by contacting <a href="mailto:customerservices@ioppublishing.org">customerservices@ioppublishing.org</a></td>
</tr>
<tr>
<td headers="12-2-support chap-12-criteria">12.2.3 Effective communication</td>
<td headers="12-2-support chap-12-conformance">Supports</td>
<td headers="12-2-support chap-12-remarks"></td>
</tr>
<tr>
<td headers="12-2-support chap-12-criteria">12.2.4 Accessible documentation</td>
<td headers="12-2-support chap-12-conformance">See <a href="#wcag-2x-report">WCAG 2.x</a> section</td>
<td headers="12-2-support chap-12-remarks">See information in WCAG 2.x section</td>
</tr>
</tbody>
</table>

### Clause [13: ICT Providing Relay or Emergency Service Access](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=86)

Notes: This product does not provide any relay services, or access for Emergency Services.
