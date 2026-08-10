<img width="468" height="25" alt="image" src="https://github.com/user-attachments/assets/d03da01c-beee-4fb1-b123-048ecbb201af" /># IOPscience Accessibility Conformance Report International Edition
(Based on VPAT® Version 2.5rev)

**Name of Product/Version**: 22.34.0  
**Report Date**: 17 July 2026  
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
</tr>
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

## WCAG 2.x Report<a id="wcag-2x-report"></a>

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

### WCAG Quick Reference
<table>
<thead>
<tr>
<th><strong>Criteria</strong></th>
<th><strong>Level</strong></th>
<th><strong>Conformance Level </strong></th>
</tr>
</thead>
<tbody>
<tr style="background-color:#F4B084;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#non-text-content"><strong>1.1.1 Non-text Content</strong></a></td>
<td>A</td>
<td>Partially Supports</td>
</tr>
<tr style="background-color:#F4B084;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#audio-only-and-video-only-prerecorded"><strong>1.2.1 Audio-only and Video-only (Prerecorded)</strong></a></td>
<td>A</td>
<td>Partially Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#captions-prerecorded"><strong>1.2.2 Captions (Prerecorded)</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#audio-description-or-media-alternative-prerecorded"><strong>1.2.3 Audio Description or Media Alternative (Prerecorded)</strong></a></td>
<td>A</td>
<td>Partially Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#captions-live"><strong>1.2.4 Captions (Live)</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#F17474;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#audio-description-prerecorded"><strong>1.2.5 Audio Description (Prerecorded)</strong></a></td>
<td>AA</td>
<td>Does Not Support</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#info-and-relationships"><strong>1.3.1 Info and Relationships</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#meaningful-sequence"><strong>1.3.2 Meaningful Sequence</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#sensory-characteristics"><strong>1.3.3 Sensory Characteristics</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#orientation"><strong>1.3.4 Orientation</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#identify-input-purpose"><strong>1.3.5 Identify Input Purpose</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#F4B084;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#use-of-color"><strong>1.4.1 Use of Color</strong></a></td>
<td>A</td>
<td>Partially Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#audio-control"><strong>1.4.2 Audio Control</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#F4B084;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#contrast-minimum"><strong>1.4.3 Contrast (Minimum)</strong></a></td>
<td>AA</td>
<td>Partially Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#resize-text"><strong>1.4.4 Resize Text</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#images-of-text"><strong>1.4.5 Images of Text</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#reflow"><strong>1.4.10 Reflow</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#F4B084;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#non-text-contrast"><strong>1.4.11 Non-text Contrast</strong></a></td>
<td>AA</td>
<td>Partially Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#text-spacing"><strong>1.4.12 Text Spacing</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#content-on-hover-or-focus"><strong>1.4.13 Content on Hover or Focus</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#keyboard"><strong>2.1.1 Keyboard</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#no-keyboard-trap"><strong>2.1.2 No Keyboard Trap</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#character-key-shortcuts"><strong>2.1.4 Character Key Shortcuts</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#timing-adjustable"><strong>2.2.1 Timing Adjustable</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#pause-stop-hide"><strong>2.2.2 Pause, Stop, Hide</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#three-flashes-or-below-threshold"><strong>2.3.1 Three Flashes or Below Threshold</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#bypass-blocks"><strong>2.4.1 Bypass Blocks</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#page-titled"><strong>2.4.2 Page Titled</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#focus-order"><strong>2.4.3 Focus Order</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#link-purpose-in-context"><strong>2.4.4 Link Purpose (In Context)</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#multiple-ways"><strong>2.4.5 Multiple Ways</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#headings-and-labels"><strong>2.4.6 Headings and Labels</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#focus-visible"><strong>2.4.7 Focus Visible</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#focus-not-obscured-minimum"><strong>2.4.11 Focus Not Obscured (Minimum)</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#pointer-gestures"><strong>2.5.1 Pointer Gestures</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#pointer-cancellation"><strong>2.5.2 Pointer Cancellation</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#label-in-name"><strong>2.5.3 Label in Name</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#motion-actuation"><strong>2.5.4 Motion Actuation</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#dragging-movements"><strong>2.5.7 Dragging Movements</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#target-size-minimum"><strong>2.5.8 Target Size (Minimum)</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#language-of-page"><strong>3.1.1 Language of Page</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#language-of-parts"><strong>3.1.2 Language of Parts</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#on-focus"><strong>3.2.1 On Focus</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#on-input"><strong>3.2.2 On Input</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#consistent-navigation"><strong>3.2.3 Consistent Navigation</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#consistent-identification"><strong>3.2.4 Consistent Identification</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#consistent-help"><strong>3.2.6 Consistent Help</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#error-identification"><strong>3.3.1 Error Identification</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#labels-or-instructions"><strong>3.3.2 Labels or Instructions</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#error-suggestion"><strong>3.3.3 Error Suggestion</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#error-prevention-legal-financial-data"><strong>3.3.4 Error Prevention (Legal, Financial, Data)</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#redundant-entry"><strong>3.3.7 Redundant Entry</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#accessible-authentication-minimum"><strong>3.3.8 Accessible Authentication (Minimum)</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#parsing"><strong>4.1.1 Parsing (Obsolete and removed)</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#name-role-value"><strong>4.1.2 Name, Role, Value</strong></a></td>
<td>A</td>
<td>Supports</td>
</tr>
<tr style="background-color:#C6E0B4;color:#000000">
<td><a style="color:#000000;text-decoration:underline" href="#status-messages"><strong>4.1.3 Status Messages</strong></a></td>
<td>AA</td>
<td>Supports</td>
</tr>
</tbody>
</table>

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
<td>Web: Partially Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>The majority of images on IOPscience have text descriptions provided through the HTML <code>alt</code> attribute.</li>
<li>Any imagery considered to be purely decorative will include an empty <code>alt</code> attribute so that assistive technology knows to ignore them.</li>
<li>If a suitable image description can already be found in the surrounding text, the image will not be highlighted to screen readers to avoid repeating the same information.</li>
</ul>
<strong>Examples of Does Not Support</strong>
<ul>
<li>For figure images, we utilise the <code>alt</code> attribute by instructing users to refer to the related caption. We acknowledge that the text in the caption may not always completely describe the image contents.</li>
</ul>
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
<td>Web: Partially Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Video abstracts are accompanied by a transcript. A link to the transcript is located immediately below the video.</li>
<li>For videos embedded with the YouTube player, a transcript is available when watching the video directly on the YouTube website.</li>
</ul>
<strong>Examples of Does Not Support</strong>
<ul>
<li>For some video abstracts, not all visual detail is recorded.</li>
<li>Some video figures which would benefit from a transcript do not have one.</li>
</ul>
<strong>Workarounds</strong>
<p>Readers may reach out to our customer services team <a href="mailto:customerservices@ioppublishing.org">customerservices@ioppublishing.org</a> to request an alternative version.</p>
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
<td>Web: Supports
</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>The majority of videos are embedded in the website using the Brightcove media player, captions may be turned on or off and their appearance customised.</li>
<li>For any videos embedded using the YouTube media player, captions may be turned on and off.</li>
<li>Captions are synchronised with audio.</li>
<li>For videos with captions, a button for turning on/off and customising captions is provided at the same level as volume control in the video player interface.</li>
</ul>
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
<td>Web: Partially Supports
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Video abstracts are accompanied by a text transcript. A link to the transcript is located immediately below the video.</li>
</ul>
<strong>Examples of Does Not Support</strong>
<ul>
<li>Videos do not have audio description</li>
</ul>
<strong>Workarounds</strong>
<p>Readers may reach out to our customer services team <a href="mailto:customerservices@ioppublishing.org">customerservices@ioppublishing.org</a> to request an alternative version.</p>
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
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Content is built using the appropriate HTML elements. For example, headings will always be markedup using heading tags.</li>
<li>ARIA attributes are used to provide increased detail to assistive technologies, such as when an accordion widget is expanded or collapsed.</li>
<li>Landmark regions are used to section pages, allowing readers to move easily from area to area.</li>
<li>A logical heading structure is used to organise information.</li>
<li>Forms are constructed using fieldsets to group related fields. All fields are explicitly labelled using <label> elements.</li>
<li>Groups of links are constructed using either unordered or ordered HTML lists, so that readers can identify how many links exist and skip over entire lists when desired.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Content is structured in a linear fashion to read from left to right, top to bottom</li>
<li>The DOM order matches the visual order so that tab focus and screen readers move in a predictable fashion.</li>
<li>The order of content is dictated by the structural markup. CSS is used to style and position elements.</li>
</ul>
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
<td>Web: Supports</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>Any inclusion of sensory characteristics in instructions will be supplementary, not crucial to the understanding of content.</li>
</ul>
</td>
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
<td>Web: Partially Supports
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Colour alone is not relied upon in understanding the website's user interface.</li>
<li>Links in bodies of text have an underline.</li>
<li>Coloured form labels also have a text cue. For example required fields in a form will contain the word "required" in their associated label.</li>
<li>Status messages have applicable roles. Error and warning messages will have the "alert" role and other messages the "status" role on top of having different colours to distinguish them.</li>
<li>The focused style of elements provides additional visual cues alongside any change in colour. For example, focused navigation menu items receive a bottom border on focus as well as a change in background colour.</li>
</ul>
<strong>Examples of Does Not Support</strong>
<ul>
<li>Some author supplied figures do rely on colour alone to distinguish data. For example, the only way to distinguish lines in a line chart is by their colour. We have updated our author guidelines to encourage the adoption of best practices around colour in data visualization. We do not mandate that figures pass WCAG guidelines.</li>
</ul>
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
<td>Web: Supports</td>
<td>There is no content on IOPscience to which this success criterion applies.</td>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>All interactivity available through a mouse input and touch is available through keyboard input.</li>
<li>Interactive figures may be manipulated using dragging movement with a mouse pointer or a finger. At the top of each figure is a keyboard accessible toolbar providing equivalent controls, such as panning, rotating and zooming.</li>
<li>Elements are marked up with the most appropriate HTML tags, ensuring their behaviour is predictable and consistent. For example, the <code>&lt;button&gt;</code> tag is used to construct buttons and is activated by either the SPACE or ENTER keys.</li>
</ul>
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
<td>Web: Supports
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>If focus is moved away from the main layer of the page, such as with popup windows, readers can exit either through a close button or using the ESCAPE key. Focus will be moved back to the element that initially triggered the popup.</li>
</ul>
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
<td>Web: Supports</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>IOPscience does not provide any single character key shortcuts. This success criterion does not apply.</li>
</ul>
</td>
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
<td>Web: Supports</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>IOPscience does not contain any time limits. This success criterion does not apply.</li>
</ul>
</td>
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
<td>Web: Supports
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>The only instances of moving content on the website are rotating ad banners, served via Google’s advertising platform. In the top-right corner of each banner is a “More information” button, indicated by 3 vertical dots. Clicking on this button presents a new view, effectively pausing any motion. The button however does not have any visual label or programmatically accessible name, so it is not exposed to assistive technology.</li>
</ul>
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
<td>Web: Supports</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>IOPscience does not contain any flashing content. This success criterion does not apply.</li>
</ul>
</td>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>A link is prepended to the main site navigation to allow readers to skip to the main content of the page.</li>
<li>Pages with content facets have a link to skip to the main content of the page.</li>
<li>Pages are split into regions using ARIA landmarks, allowing readers to move between them.</li>
<li>Pages are constructed with logical headings, allowing readers to navigate from heading to heading when using assistive technology.</li>
<li>Expandable and collapsible content, such as accordions, is collapsed by default to minimise the number of elements in the tabbing order on page load.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Pages have descriptive titles. A breadcrumb structure is used to help readers understand on which page, and which area of the site they currently are (e.g. "Issue 3 - Volume 4 - Journal of Physics: Energy - IOPscience").</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>There is a logical focus order throughout pages, following left to right, top to bottom.</li>
<li>The DOM order matches the visual order throughout pages making the focus movement predictable.</li>
<li>Dialog windows receive focus when opened. When closed, focus is returned to the element which triggered it or the top of the page.</li>
<li>"Skip" links move focus to the first focusable element within the target region.</li>
</ul>
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
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Most links provide a clear description of their destination.</li>
<li>When necessary supplementary information is provided by utilising ARIA attributes or visually hidden text.</li>
<li>Links with identical names appear on some pages, such as the search results page. In such instances <a href="https://www.w3.org/WAI/WCAG22/Techniques/html/H78">link context may be determined from the enclosing paragraph or list item</a>.</li>
</ul>
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
<td>Web: Supports
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>IOPscience contains no content that relies on multipoint or path-based gestures. This success criterion does not apply.</li>
</ul>
</td>
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
<td>Web: Supports
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Interactive elements are activated on the "Up" event. This means actions are only triggered when the user releases a mouse click or a keyboard press, enabling them to abort the action by moving the mouse or keyboard focus away from the element before releasing.</li>
</ul>
</td>
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
<td>Web: Supports
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Most elements have a matching visible label and programmatic accessible name. This means the label read aloud by screen readers will be identical to the visible label.</li>
<li>If the accessible name includes a longer description, it and the visible label will still begin the same, to ensure that people who use speech input technology can effectively activate controls. For example on the search page where a "View article" link may appear multiple times, its accessible name is expanded to "View article &lt;article title&gt;".</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>IOPscience contains no functionality operated by device motion or user motion. This success criterion does not apply.</li>
</ul>
</td>
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
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>All pages have the lang=”en” attribute in the <code>&lt;html&gt;</code> tag to establish the language content is written in.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>No changes in context are triggered by any component receiving focus. All changes rely on click and keypress events from the reader.</li>
</ul>
</td>
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
</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>Changing the setting of any user interface component does not automatically trigger a change of context. The reader must manually trigger changes themselves (e.g. activating the “Apply” button after making any changes to search result filters). This ensures that the user interface responds in a predictable manner.</li>
</ul></td>
</tr>
<tr id="consistent-help" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#consistent-help"><strong>3.2.6 Consistent Help</strong></a> (Level A 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
</td>
<td>Web: Supports</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>A link to contact details and accessibility information is included in the footer of the website on all pages.</li>
</ul>
</td>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Input errors are identified and communicated visually and programmatically so that users are made aware that entered data requires attention when necessary. Errors are displayed in a red box with black text, immediately next to the related input.</li>
<li>For search type inputs, an error will be displayed if no terms are entered before attempting to perform a search, or if the entered information is not in the requested format.</li>
<li>On forms, errors are displayed in red text immediately below their related fields. A summary of errors is also prepended to the form with the “alert” role, to communicate to users of assistive technology that attention is required. Error text is programmatically related to its associated fields using “aria-describedby” attributes.</li>
</ul>
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
<td>Web: Supports</td>

<td><strong>Examples of Supports</strong>
<ul>
<li>All form fields have an associated label immediately next to them.</li>
<li>Related form fields are grouped together using a structure of <code>&lt;legend&gt;</code> and <code>&lt;fieldset&gt;</code> elements.</li>
<li>If a form contains incomplete required fields, the reader will be alerted to the label of each field which has been omitted.</li>
<li>Instructions are included for form fields which require a specific format. </li>
</ul>
</td>
</tr>
<tr id="redundant-entry" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#redundant-entry"><strong>3.3.7 Redundant Entry</strong></a> (Level A 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
</td>
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>There are no instances on IOPscience where a user would be required to enter the same information more than once as part of the same process. This success criterion does not apply.</li>
</ul></td>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Content that expands and collapses is given the <code>aria-expanded</code> attribute to communicate its current state.</li>
<li>For links with the same label repeated on the same page, additional context is provided through the <code>aria-label</code> and <code>aria-labelledby</code> attributes to ensure they are unique and meaningful to users of assistive technology.</li>
<li>For links that are repeated and go to the same destination, the same label and accessible name is used, so that they may be consistently identified.</li>
<li>A third-party service is used to display advertising panels in pages. These are inserted via iframe and are identified by the title “3rd party ad content”.</li>
<li>Pages are broken up into regions using ARIA landmark roles. If multiple of the same landmark exist on a page, they are provided with unique labels to identify them. For example, there is a "Site" navigation in the header of each page, and a "Further resources" navigation in the footer.</li>
</ul>
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
<td>Web: Supports</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>IOPscience does not contain live audio. This success criterion does not apply.</li>
</ul>
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
<td>Web: Does Not Support</td>
<td><strong>Examples of Does Not Support</strong>
<ul>
<li>Audio descriptions tracks are not available for video content. We are reviewing our media production process to explore how we may be able to provide this in the future.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>The layout and operation of the content will adapt to the orientation of the user’s display device (e.g. portrait and landscape modes).</li>
</ul></td>
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
<td>Web: Support</td>
<td><strong>Examples of Supports</strong>
<ul>
<li><code>&lt;input&gt;</code> elements are assigned a “type” attribute to help users understand what information should be entered.</li>
<li>The HTML autocomplete attribute is assigned to appropriate form fields so that they may be populated by autofill values stored in the user’s browser.</li>
</ul>
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
<td>Web: Partially Supports
</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Text and background colour combinations that meet a minimum contrast of 4.5:1 are used to style the website.
<ul>
<li>Links are styled in red (#cc0000) and appear on white (#ffffff) and light grey (#f3f3f3) backgrounds, passing minimum contrast.</li>
<li>Status and error messages have green and red colour themes. Message text is a darker colour on top of a lighter background. These pass minimum contrast.</li>
<li>When text appears on dark grey (#333333), such as in the website footer, it is white (#ffffff) and passes minimum contrast.</li>
<li>Dark blue (#00619e) that appears on light blue (#ccddf6), such as in the website main navigation passes minimum contrast.</li>
<li>Some logotypes do not meet minimum contrast, but the WCAG guidelines describe them from being exempt from the rule, such that changing their appearance may result in a loss of identity.</li>
</ul>
</li>
</ul>
<strong>Examples of Does Not Support</strong>
<ul>
<li>We cannot guarantee that author supplied content, such as figures, will always meet minimum contrast. Figures are accompanied with a caption to aid in the understanding of the visual information being presented.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Text can be resized up to 200% without loss of content or functionality.</li>
</ul>
</td>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Images of text are not used on IOPscience.</li>
<li>Author supplied figures do contain images of text, but as they contain significant other visual content they are exempt, according to the <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-text-presentation.html#images-of-textdef">WCAG definition of images of text</a></li>
<li>Logotypes including text are exempt from meeting the criteria based on WCAG’s definition, as the visual presentation of the text is essential to the identity of the logo.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Web pages use a responsive layout that will adjust to available screen space. For larger displays, such as desktops, layouts may be split into multiple columns. For smaller devices such as smartphones, layouts will collapse into a single column.</li>
<li>Long strings of text and URLs will wrap to additional lines when required, so that the user does not need to scroll horizontally to read text.</li>
</ul>
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
<td>Web: Partially Supports</td>
<td><strong>Examples of supports</strong>
<ul>
<li>Graphical elements such as icons have a minimum contrast of 3.1:1</li>
<li>Underline used to identify the hover state of links has a minimum contrast of 3.1:1 with background colours.</li>
<li>Focused links receive a block background colour that is at least 3.1:1 contrast with both the link text and the surrounding background.</li>
<li>Some third-party logos (e.g. ORCID ID) do not meet the minimum contrast. <a href="https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html#essential-exception">Logos are exempt</a>, as changing the colour to meet sufficient contrast may mean they are no longer identifiable.</li>
</ul>
<strong>Examples of Does Not Support</strong>
<ul>
<li>We cannot guarantee that colours used in author supplied figures meet contrast requirements, but we are continually updating our author guidelines to encourage considering accommodations for accessibility in data visualisation. Figures are accompanied by a caption which also should help describe their contents.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>When testing pages against the following criteria, the majority did not experience any loss of content or functionality:
<ul>
<li>Line height (line spacing) to at least 1.5 times the font size;</li>
<li>Spacing following paragraphs to at least 2 times the font size;</li>
<li>Letter spacing (tracking) to at least 0.12 times the font size;</li>
<li>Word spacing to at least 0.16 times the font size.</li>
</ul></li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Tooltips can be revealed and dismissed via mouse or keyboard controls.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>A list of Journals and books can be found on their respective hub pages or through the site search functionality.</li>
<li>Alerts can be accessed in the “My IOPscience” dashboard under the “E-mail alerts” tab, or through links on Journal home and article pages.</li>
<li>For any alert in the My IOPscience dashboard, there is a link back to the respective journal or search results.</li>
<li>The "Download History" tab keeps a record of all full text articles that have been accessed over the last three months.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Headings and labels are concise and provide a clear description of thier related content.</li>
</ul>
</td>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<p>We use a variety of focus indicator styles to ensure focus remains visible in all scenarios. These styles are supported in high contrast modes and themes.
<ul>
<li>Links – Red (#cc0000) background with white (#ffffff) text. If a link has an underline, it is removed.</li>
<li>Footer links – White (#ffffff) background with dark grey (#333333) text</li>
<li>Linked images – Red (#cc0000) and white (#ffffff) outline</li>
<li>Buttons – Red (#cc0000) background with white (#ffffff) square brackets wrapping the button text.</li>
<li>Site wide navigation menu items – Red (#cc0000) background with a white (#ffffff) bottom border.</li>
</ul>
</td>
</tr>
<tr id="focus-not-obscured-minimum" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum"><strong>2.4.11 Focus Not Obscured (Minimum)</strong></a> (Level AA 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
</td>
<td>Web: Supports</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>If any element receives keyboard focus, it will never be obscured, even by fixed elements on the page.</li>
</ul>
</td>
</tr>
<tr id="dragging-movements" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#dragging-movements"><strong>2.5.7 Dragging Movements</strong></a> (Level AA 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
</td>
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>The only content that may utilised dragging movements on IOPscience is interactive figures. Using a mouse pointer or touch, figures may be rotated, panned and zoomed. At the top of each figure is a toolbar which provides equivalent controls which only require single pointer input, such as a mouse click or a single finger press on a touch screen.</li>
</ul>
</td>
</tr>
<tr id="target-size-minimum" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#target-size-minimum"><strong>2.5.8 Target Size (Minimum)</strong></a> (Level AA 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
</td>
<td>Web: Supports</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>IOPscience uses targets with minimum dimensions of 24 by 24 CSS pixels. Undersized targets are accommodated with extra space around them, so that other targets are at least a distance of 24 CSS pixels away. This helps to avoid unintended clicks when elements are positioned too close to one another.</li>
</ul>
</td>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>IOPscience content is primarily written in English. For any content that is written in an alternative language, it is flagged to screen readers, so that they may use the correct pronunciations. In the HTML, text written in another language has a <code>lang</code> attribute with the relevant language code.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>Header and footer navigation is the same across all pages.</li>
<li>All pages are labelled with ARIA landmarks, including the header, main content, sidebars and footer.</li>
<li>When performing a search, the chosen filters persist when results are updated.</li>
<li>The login menu in the header navigation will reflect the current logged in state across all pages.</li>
<li>For pages that have pagination, the pagination controls are always displayed at the bottom right, immediately below the item list.</li>
<li>A "Skip to content" link is included immediately before the header navigation and is revealed on keyboard focus across all pages.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>User interface components keep the same appearance and functionality across all pages.</li>
<li>Icons are used to identify controls for downloading electronic documents (e.g. PDF, Kindle, EPUB).</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>If an error is identified, it is described and a solution for correction is offered.</li>
<li>Required fields are identified with the aria-required property.</li>
<li>Fields that require a specific input format will highlight this if incorrect information is entered.</li>
<li>Alert text has the "alert" role to ensure they are communicated to assistive technology.</li>
<li>Error text is connected to its related field using the aria-describedby property.</li>
</ul>
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
<td>Web: Supports</td>
<td><strong>Examples of Supports</strong>
<ul>
<li>IOPscience does not have any pages that included legal commitments or financial transactions.</li>
</ul>
</td>
</tr>
<tr id="accessible-authentication-minimum" valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#accessible-authentication-minimum"><strong>3.3.8 Accessible Authentication (Minimum)</strong></a> (Level AA 2.2 only)
<br><br>EN 301 549 Criteria – Does not apply<br><br>
Revised Section 508 – Does not apply
</td>
<td>Web: Supports</td>
<td>
<strong>Examples of Supports</strong>
<ul>
<li>Form fields have autocomplete enabled to allow existing credentials to be automatically populated.</li>
<li>Form fields allow copy/paste functionality to avoid retyping entire usernames and passwords.</li>
</ul>
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
<td>Web: Supports</td>
<td>Web: <br><br>

<strong>Examples of Supports</strong>
<ul>
<li>Status messages are displayed for all success and error feedback.</li>
<li>Status messages use role=status.</li>
<li>Error messages use role=alert.</li>
</ul>
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
<td>The user interface is designed to support a variety of input methods. For touch navigation, on devices that support it, elements are designed to be large enough to not require very precise movements. For any content that utilises dragging movements, single pointer controls are also present to provide equivalent controls.</td>
</tr>
<tr id="508_302-8">
<td>302.8 With Limited Reach and Strength</td>
<td>Supports</td>
<td></td>
</tr>
<tr>
<td>302.9 With Limited Language, Cognitive, and Learning Abilities</td>
<td>Supports</td>
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
<td headers="502-interop chap-5-conformance">Not Applicable</td>
<td headers="502-interop chap-5-remarks">IOPscience is not Platform Software as defined by Section 508. See <a href="https://www.access-board.gov/ict/#E103.4">E103.4 Defined Terms</a>.</td>
</tr>
<tr>
<td headers="502-interop chap-5-criteria">502.2.2 No Disruption of Accessibility Features</td>
<td headers="502-interop chap-5-conformance">Not Applicable</td>
<td headers="502-interop chap-5-remarks">IOPscience is a website, compatible with a variety of operating system and browser accessibility features and preferences.</td>
</tr>
<tr>
<th scope="column" colspan="3" id="502-services">502.3 Accessibility Services</th>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.1 Object Information</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">See <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.2 Modification of Object Information</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">See <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a></td>
</tr>
<tr id="502-3-3">
<td headers="502-services chap-5-criteria">502.3.3 Row, Column, and Headers</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">Tables are marked up using HTML <code>&lt;table&gt;</code> elements using a traditional structure of rows and columns. When applicable, table headers <code>&lt;thead&gt;</code> are included to display row and column titles.</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.4 Values</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">See <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.5 Modification of Values</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">See <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a></td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.6 Label Relationships</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">See <a href="#headings-and-labels">WCAG 2.4.6 Headings and Labels</a> and <a href="#labels-or-instructions">WCAG 3.3.2 Labels or Instructions</a>.</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.7 Hierarchical Relationships</td>
<td headers="502-services chap-5-conformance"></td>
<td headers="502-services chap-5-remarks">See <a href="#info-and-relationships">WCAG 1.3.1 Info and Relationships</a>.</td>
</tr>
<tr id="502-3-8">
<td headers="502-services chap-5-criteria">502.3.8 Text</td>
<td headers="502-services chap-5-conformance">Partially Supports</td>
<td headers="502-services chap-5-remarks">Text is presented as HTML plain text. Images have alternative text, though in a small number of cases it is not adequate to describe the visual content. See <a href="#non-text-content">WCAG 1.1.1 Non-text Content</a>.
</td>
</tr>
<tr id="502-3-9">
<td headers="502-services chap-5-criteria">502.3.9 Modification of Text</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">IOPscience uses standard HTML for elements which may receive user input and can be set programmatically through assistive technology.</td>
</tr>
<tr id="502-3-10">
<td headers="502-services chap-5-criteria">502.3.10 List of Actions</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">Pages are marked up using standard HTML and when applicable, supplemented with ARIA attributes to communicate to assistive technology element roles, actions and behaviours.</td>
</tr>
<tr id="502-3-11">
<td headers="502-services chap-5-criteria">502.3.11 Actions on Objects</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">All actions and behaviours associated with HTML elements are available to assistive technologies. See <a href="#keyboard">WCAG 2.1.1 Keyboard</a> and <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a>.</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.12 Focus Cursor</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">See <a href="#focus-visible">WCAG 2.4.7 Focus Visible</a>.</td>
</tr>
<tr id="502-3-13">
<td headers="502-services chap-5-criteria">502.3.13 Modification of Focus Cursor</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">Focus styles may be overridden by user operating system and browser preferences.</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.14 Event Notification</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">See <a href="#error-identification">WCAG 3.3.1 Error Identification</a> and <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a>.</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.4 Platform Accessibility Features</td>
<td headers="502-services chap-5-conformance">Not Applicable</td>
<td headers="502-services chap-5-remarks">IOPscience is not Platform Software as defined by Section 508. See <a href="https://www.access-board.gov/ict/#E103.4">E103.4 Defined Terms</a>.</td>
</tr>
<tr>
<th scope="column" colspan="3" id="503-apps"><a href="https://www.access-board.gov/ict/#503-applications">503 Applications</a></th>
</tr>
<tr id="503-2">
<td headers="503-apps chap-5-criteria">503.2 User Preferences</td>
<td headers="503-apps chap-5-conformance">Supports</td>
<td headers="503-apps chap-5-remarks">User preferences set at the operating system, assistive technology or browser level may be used to override default styles.</td>
</tr>
<tr>
<td headers="503-apps chap-5-criteria">503.3 Alternative User Interfaces</td>
<td headers="503-apps chap-5-conformance">Not Applicable</td>
<td headers="503-apps chap-5-remarks">IOPscience does not provide any alternative user interface that functions as assistive technology.</td>
</tr>
<tr>
<th scope="column" colspan="3" id="503-usercon">503.4 User Controls for Captions and Audio Description</th>
</tr>
<tr>
<td headers="503-usercon chap-5-criteria">503.4.1 Caption Controls</td>
<td headers="503-usercon chap-5-conformance">Supports</td>
<td headers="503-usercon chap-5-remarks">See <a href="#captions-prerecorded">WCAG 1.2.2 Captions (Prerecorded).</td>
</tr>
<tr>
<td headers="503-usercon chap-5-criteria">503.4.2 Audio Description Controls</td>
<td headers="503-usercon chap-5-conformance">Does Not Support</td>
<td headers="503-usercon chap-5-remarks">Videos on IOPscience do not include audio description.</td>
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
<td headers="504-authoring chap-5-conformance">Not Applicable</td>
<td headers="504-authoring chap-5-remarks">IOPscience is not an authoring tool.</td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.2.2 PDF Export</td>
<td headers="504-authoring chap-5-conformance">Not Applicable</td>
<td headers="504-authoring chap-5-remarks">IOPscience is not an authoring tool.</td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.3 Prompts</td>
<td headers="504-authoring chap-5-conformance">Not Applicable</td>
<td headers="504-authoring chap-5-remarks">IOPscience is not an authoring tool.</td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.4 Templates</td>
<td headers="504-authoring chap-5-conformance">Not Applicable</td>
<td headers="504-authoring chap-5-remarks">IOPscience is not an authoring tool.</td>
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
<td headers="602-documentation chap-6-conformance">Supports</td>
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
<td>Pages may be magnified without a loss of information or requiring to horizontally scroll. The website is compatible with high contrast themes, if users wish to use an alternative colour palette. All colour combinations are designed to meet a minimum contrast of 4.5:1, according to the WCAG guidelines.</td>
</tr>
<tr>
<td>4.2.3 Usage without Perception of Color</td>
<td>Supports</td>
<td>We avoid using colour alone to convey information. When required links will have an underline to help identify them amongst other text. Functional components, such as accordions, are accompanied by icons to communicate they are interactive and their current state.</td>
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
<td>4.2.6 Usage with no or limited vocal capability</td>
<td>Supports</td>
<td>Speech input is not required.</td>
</tr>
<tr>
<td>4.2.7 Usage with limited manipulation or strength</td>
<td>Supports</td>
<td>The user interface is designed to support a variety of input methods. For touch navigation, on devices that support it, elements are designed to be large enough to not require very precise movements. For any content that utilises dragging movements, single pointer controls are also present to provide equivalent controls.</td>
</tr>
<tr>
<td>4.2.8 Usage with limited reach</td>
<td>Supports</td>
<td>See Revised Section 508 Report <a href="#508_302-8">302.8 With Limited Reach and Strength</a></td>
</tr>
<tr>
<td>4.2.9 Minimize photosensitive seizure triggers</td>
<td>Supports</td>
<td>We do not display any content with a high flashing or flicker rate.</td>
</tr>
<tr>
<td>4.2.10 Usage with limited cognition, language or learning</td>
<td>Supports</td>
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
<td headers="7-caption chap-7-remarks">See <a href="#captions-prerecorded">WCAG 1.2.2 Captions (Prerecorded)</a>.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.2 Captioning synchronization</td>
<td headers="7-caption chap-7-conformance">Supports</td>
<td headers="7-caption chap-7-remarks">See <a href="#captions-prerecorded">WCAG 1.2.2 Captions (Prerecorded)</a>.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.3 Preservation of captioning</td>
<td headers="7-caption chap-7-conformance">Supports</td>
<td headers="7-caption chap-7-remarks">The default appearance for captions is white text on a black background, positioned bottom-center of the window.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.4 Captions characteristics</td>
<td headers="7-caption chap-7-conformance">Supports</td>
<td headers="7-caption chap-7-remarks">See <a href="#captions-prerecorded">WCAG 1.2.2 Captions (Prerecorded)</a>.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.5 Spoken subtitles</td>
<td headers="7-caption chap-7-conformance">Partially Supports</td>
<td headers="7-caption chap-7-remarks">Videos do not include an audio track with spoken subtitles. For videos that have an accompanying text transcript, this can be download for conversion into audio.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.2.1 Audio description playback</td>
<td headers="7-caption chap-7-conformance">Does Not Support</td>
<td headers="7-caption chap-7-remarks">Videos do not have audio description.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.2.2 Audio description synchronization</td>
<td headers="7-caption chap-7-conformance">Does Not Support</td>
<td headers="7-caption chap-7-remarks">Videos do not have audio description.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.2.3 Preservation of audio description</td>
<td headers="7-caption chap-7-conformance">Does Not Support</td>
<td headers="7-caption chap-7-remarks">Videos do not have audio description.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.3 User controls for captions and audio description</td>
<td headers="7-caption chap-7-conformance">Supports</td>
<td headers="7-caption chap-7-remarks">For caption controls, see <a href="#captions-prerecorded">WCAG 1.2.2 Captions (Prerecorded)</a>. Videos do not have audio description controls.</td>
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

Notes:

<table>
<thead>
<tr>
<th scope="col" id="user-content-chap-11-criteria"><strong>Criteria</strong></th>
<th scope="col" id="user-content-chap-11-conformance"><strong>Conformance Level</strong></th>
<th scope="col" id="user-content-chap-11-remarks"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
 <tr>
 <th scope="column" colspan="3" id="user-content-11-gen">11.0 General (informative)</th>
 </tr>
<tr>
<td headers="11-gen chap-11-criteria">11.1.1 through 11.4.1.3</td>
<td headers="11-gen chap-11-conformance">See WCAG 2.x Section</td>
<td headers="11-gen chap-11-remarks">See information in [WCAG section](#wcag-22-report).</td>
</tr>
<tr>
<th scope="column" colspan="3" id="user-content-11-interop">11.5 Interoperability with assistive technology</th>
</tr>
<tr>
<th scope="column" colspan="3" id="user-content-11-closed">11.5.1 Closed functionality (informative)</th>
</tr>
<tr>
<th scope="column" colspan="3" id="user-content-11-a11y-serv">11.5.2.1 Accessibility services</th>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.1 Platform accessibility service support for software that provides a user interface</td>
<td headers="11-a11y-serv chap-11-conformance">See 11.5.2.5 through 11.5.2.17</td>
<td headers="11-ally-serv chap-11-remarks">See information in 11.5.2.5 through 11.5.2.17</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.2 Platform accessibility service support for assistive technologies</td>
<td headers="11-a11y-serv chap-11-conformance">See 11.5.2.5 through 11.5.2.17</td>
<td headers="11-ally-serv chap-11-remarks">See information in 11.5.2.5 through 11.5.2.17</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.3 Use of accessibility services</td>
<td headers="11-a11y-serv chap-11-conformance">See information in 11.5.2.5 through 11.5.2.17</td>
<td headers="11-ally-serv chap-11-remarks">See information in 11.5.2.5 through 11.5.2.17</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.4 Assistive technology</td>
<td headers="11-a11y-serv chap-11-conformance">Not Applicable</td>
<td headers="11-ally-serv chap-11-remarks">IOPscience is not an Assistive Technology.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.5 Object information</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a></td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.6 Row, column, and headers</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#502-3-3">Section 508 502.3.3</a></td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.7 Values</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a>.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.8 Label relationships</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#headings-and-labels">WCAG 2.4.6 Headings and Labels</a> and <a href="#labels-or-instructions">WCAG 3.3.2 Labels or Instructions</a>.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.9 Parent-child relationships</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#info-and-relationships">WCAG 1.3.1 Info and Relationships</a>.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.10 Text</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#502-3-8">Section 508 502.3.8</a>.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.11 List of available actions</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#502-3-10">Section 508 502.3.10</a>.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.12 Execution of available actions</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#502-3-11">Section 508 502.3.11</a>.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.13 Tracking of focus and selection attributes</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#focus-visible">WCAG 2.4.7 Focus Visible</a>.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.14 Modification of focus and selection attributes</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#502-3-13">Section 508 502.3.13</a>.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.15 Change notification</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#error-identification">WCAG 3.3.1 Error Identification</a> and <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a>.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.16 Modifications of states and properties</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a>.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.17 Modifications of values and text</td>
<td headers="11-a11y-serv chap-11-conformance">Supports</td>
<td headers="11-ally-serv chap-11-remarks">See <a href="#name-role-value">WCAG 4.1.2 Name, Role, Value</a> and <a href="#502-3-9">Section 508 502.3.9</a>.</td>
</tr>
<tr>
<th scope="column" colspan="3" id="user-content-11-doc-a11y">11.6 Documented accessibility usage</th>
</tr>
<tr>
<td headers="11-doc-a11y chap-11-criteria">11.6.1 User control of accessibility features</td>
<td headers="11-doc-a11y chap-11-conformance">Not Applicable</td>
<td headers="11-doc-a11y chap-11-remarks">IOPscience is not platform software as defined by EN 301 549, 3.1 Terms.</td>
</tr>
<tr>
<td headers="11-doc-a11y chap-11-criteria">11.6.2 No disruption of accessibility features</td>
<td headers="11-doc-a11y chap-11-conformance">Not Applicable</td>
<td headers="11-doc-a11y chap-11-remarks">IOPscience is not platform software as defined by EN 301 549, 3.1 Terms. </td>
</tr>
<tr>
<td headers="11-doc-a11y chap-11-criteria">11.7 User preferences</td>
<td headers="11-doc-a11y chap-11-conformance">Supports</td>
<td headers="11-doc-a11y chap-11-remarks">The pages of this product use standard HTML and CSS attributes that may be overridden in user-supplied style sheets.</td>
</tr>
<tr>
<th scope="column" colspan="3" id="user-content-11-authoring">11.8 Authoring tools</th>
</tr>
<tr>
<th scope="column" colspan="3" id="user-content-11-content-tech">11.8.1 Content technology</th>
</tr>
<tr>
<td headers="11-content-tech chap-11-criteria">11.8.2 Accessible content creation</td>
<td headers="11-content-tech chap-11-conformance">Not Applicable</td>
<td headers="11-content-tech chap-11-remarks">IOPscience is not an authoring tool.</td>
</tr>
<tr>
<td headers="11-content-tech chap-11-criteria">11.8.3 Preservation of accessibility information in transformations</td>
<td headers="11-content-tech chap-11-conformance">Not Applicable</td>
<td headers="11-content-tech chap-11-remarks">IOPscience is not an authoring tool.</td>
</tr>
<tr>
<td headers="11-content-tech chap-11-criteria">11.8.4 Repair assistance</td>
<td headers="11-content-tech chap-11-conformance">Not Applicable</td>
<td headers="11-content-tech chap-11-remarks">IOPscience is not an authoring tool.</td>
</tr>
<tr>
<td headers="11-content-tech chap-11-criteria">11.8.5 Templates</td>
<td headers="11-content-tech chap-11-conformance">Not Applicable</td>
<td headers="11-content-tech chap-11-remarks">IOPscience is not an authoring tool.</td>
</tr>
</tbody>
</table>

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
