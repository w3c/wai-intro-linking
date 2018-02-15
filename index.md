---
title: Referencing and Linking to WAI Guidelines and Technical Documents
permalink: /standards/linking/
redirect_from: /
layout: default
github:
  repository: w3c/wai-intro-linking
  branch: gh-pages
---
<div id="contents">
  <h2>Page Contents</h2>
  <ul>
    <li><a href="#overview">Linking to Overview Pages</a></li>
    <li><a href="#trs">Referencing Guidelines and Other Technical Specifications</a></li>
    <li><a href="#wcag">Example: Linking to WCAG</a></li>
    <li><a href="#notes">Linking to Techniques and Other "Notes"</a></li>
    <li><a href="#waiaria">Referencing WAI-ARIA versus just ARIA</a></li>
  </ul>
</div>

<!-- <h2><a name="intro" id="intro"></a>Introduction</h2> -->

<p>This page provides general guidance on references and links, along with <a href="#wcag"> WCAG links</a> for policies, tools support, and others. If you have additional questions, you can contact WAI directly at <a href="mailto:wai@w3.org">wai@w3.org</a>.</p>
<p>For a complete list of WAI documents, see the <a href="http://www.w3.org/WAI/sitemap">WAI Site Map</a> or the <a href="http://www.w3.org/WAI/Resources/">WAI Resources annotated list</a>.</p>
<h2><a name="overview" id="overview"></a>Linking to Overview Pages</h2>
<p>In many cases, it is best to link to  the Overview page instead of the technical specification because <strong>the Overview page provides an introduction, links to related documents, and the status of revisions in progress</strong>. Overview pages include:</p>
<ul>
  <li>Authoring Tool Accessibility Guidelines <strong>(ATAG) Overview</strong> <a href="http://www.w3.org/WAI/intro/atag">http://www.w3.org/WAI/intro/atag</a></li>
  <li>Evaluation and Report Language <strong>(EARL) Overview</strong> <a href="http://www.w3.org/WAI/intro/earl">http://www.w3.org/WAI/intro/earl</a></li>
  <li>User Agent Accessibility Guidelines <strong>(UAAG) Overview</strong> <a href="http://www.w3.org/WAI/intro/uaag">http://www.w3.org/WAI/intro/uaag</a></li>
  <li>Web Content Accessibility Guidelines <strong>(WCAG) Overview</strong> <a href="http://www.w3.org/WAI/intro/wcag">http://www.w3.org/WAI/intro/wcag</a></li>
  <li><strong>WAI-ARIA Overview </strong>for Accessible Rich Internet Applications <a href="http://www.w3.org/WAI/intro/aria">http://www.w3.org/WAI/intro/aria</a></li>
</ul>
<h2><a name="trs" id="trs"></a>Referencing Guidelines and Other Technical Specifications</h2>
<p>WAI's technical specifications (WCAG, WAI-ARIA, and the others listed above)  use a "shortname" in the URI (the Web address); for example, "WCAG" and "ATAG" are  shortnames. Specific versions are indicated with a number. Without a number, you get the latest version.</p>
<h3>Latest completed version</h3>
<p>To refer to and link to the latest completed version that is the recommended Web Standard ("W3C Recommendation"), <strong>do not include a number</strong>, for example:</p>
<ul>
  <li>Authoring Tool Accessibility Guidelines (ATAG) <a href="http://www.w3.org/TR/ATAG/">http://www.w3.org/TR/ATAG/</a></li>
  <li>User Agent Accessibility Guidelines (UAAG) <a href="http://www.w3.org/TR/UAAG/">http://www.w3.org/TR/UAAG/</a></li>
  <li>Web Content Accessibility Guidelines (WCAG)  <a href="http://www.w3.org/TR/WCAG/">http://www.w3.org/TR/WCAG/</a></li>
  <li>Accessible Rich Internet Applications (WAI-ARIA) <a href="http://www.w3.org/TR/wai-aria/">http://www.w3.org/TR/wai-aria/</a></li>
</ul>
<p><strong>Note:</strong></p>
<ul>
  <li><strong>Links: </strong>The content at these links will change when new versions are published. New versions will  usually  change the fragments (also called targets and anchors, e.g., "#focus-area").</li>
  <li><strong>References:</strong> When policies do not include a number, they can be interpreted to reference the latest version.</li>
  <li>Before the first version is published, the draft is at the URI without a number, e.g., as is the case with /wai-aria/ through at least mid-2009.</li>
</ul>
<h3>Specific  version</h3>
<p>We recommend that you reference the latest version <em>without</em> a number as explained above, unless there is a  reason to reference a specific version. To link to a specific version of a technical specification, include the version number, for example:</p>
<ul>
  <li>Authoring Tool Accessibility Guidelines (ATAG) 1.0 <a href="http://www.w3.org/TR/ATAG10/">http://www.w3.org/TR/ATAG10/</a></li>
  <li>User Agent Accessibility Guidelines (UAAG) 1.0 <a href="http://www.w3.org/TR/UAAG10/">http://www.w3.org/TR/UAAG10/</a></li>
  <li>Web Content Accessibility Guidelines (WCAG) 1.0 <a href="http://www.w3.org/TR/WCAG10/">http://www.w3.org/TR/WCAG10/</a></li>
  <li>Web Content Accessibility Guidelines (WCAG) 2.0 <a href="http://www.w3.org/TR/WCAG20/">http://www.w3.org/TR/WCAG20/</a></li>
</ul>
<h3>Links to the technical specification <em>and</em> the Overview page</h3>
<p>Even when referencing the technical specification, it is usually good to include a link to the Overview page as well, for example:</p>
<ul>
  <li><a href="http://www.w3.org/TR/WCAG20">Web Content Accessibility Guidelines (WCAG) 2.0</a>, <a href="http://www.w3.org/WAI/intro/wcag">WCAG Overview</a></li>
</ul>

<div class="fullwidth">
<h2><a name="wcag" id="wcag"></a>Example: Linking to WCAG</h2>
<table border="1" cellpadding="10">
<tbody>
    <tr>
      <th scope="col">URI</th>
      <th scope="col">Use</th>
      <th scope="col">Document   linked to:</th>
      <th scope="col">Will the content at this   URI change?</th>
    </tr>
    <tr>
      <th scope="row"><a href="http://www.w3.org/WAI/intro/wcag">www.w3.org/<strong>WAI/intro/wcag</strong></a></th>
      <td>For most links about WCAG</td>
      <td>WCAG Overview</td>
      <td><strong>Yes, content will be updated with new versions,</strong> but the fragments/targets/anchors will mostly remain stable</td>
    </tr>
    <tr>
      <th scope="row"><a href="http://www.w3.org/TR/WCAG/">www.w3.org/TR/<strong>WCAG</strong>/</a></th>
      <td>For links to the latest version of the WCAG technical specification</td>
      <td>The latest version of WCAG</td>
      <td><strong>Yes, content will change when there are new versions, and fragments/targets/anchors may also change</strong></td>
    </tr>

    <tr>
      <th scope="row"><a href="http://www.w3.org/TR/WCAG20/">www.w3.org/TR/<strong>WCAG20</strong>/</a></th>
      <td>For links specifically to Version <strong>2.0</strong> of the WCAG technical
      specification, and not subsequent versions</td>
      <td>WCAG Version <strong>2.0</strong></td>
      <td>No</td>
    </tr>
    <tr>
      <th scope="row"><a href="http://www.w3.org/TR/WCAG10/">www.w3.org/TR/<strong>WCAG10</strong>/</a></th>
      <td>For links specifically to Version <strong>1.0</strong> of the WCAG technical
      specification, and not  subsequent versions</td>
      <td>WCAG Version <strong>1.0</strong></td>
      <td>No</td>
    </tr>
    <tr>
      <th scope="row">www.w3.org/TR/WAI-WEBCONTENT</th>
      <td>Deprecated. We prefer that for WCAG 1.0 you use www.w3.org/TR/WCAG10/</td>
      <td>Deprecated link to WCAG Version 1.0</td>
      <td>No</td>
    </tr>
  </tbody>
</table>
</div>
<!-- end main -->
<p><strong>For more formal guidance on referring to WCAG, see <a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/appendixA.html">Appendix A How to refer to WCAG 2.0 from other documents</a>.</strong></p>
<h2><a name="notes" id="notes"></a>Linking to Techniques and Other "Notes"</h2>
<p>While the technical specifications listed above will not change once they are completed, the  supporting  material that is advisory may be updated. WAI supporting technical material, called "W3C Working Group Notes", includes:</p>
<ul>
  <li>Techniques for ATAG <a href="http://www.w3.org/TR/ATAG-TECHS/">http://www.w3.org/TR/ATAG-TECHS/</a></li>
  <li>Techniques for UAAG <a href="http://www.w3.org/TR/UAAG-TECHS/">http://www.w3.org/TR/UAAG-TECHS/</a></li>
  <li>Techniques for WCAG <a href="http://www.w3.org/TR/WCAG-TECHS/">http://www.w3.org/TR/WCAG-TECHS/</a></li>
  <li>Understanding WCAG <a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/">http://www.w3.org/TR/UNDERSTANDING-WCAG20/</a></li>
  <li>WAI-ARIA Primer <a href="http://www.w3.org/TR/wai-aria-primer/">http://www.w3.org/TR/wai-aria-primer/</a><br clear="none" />
    WAI-ARIA Best Practices <a href="http://www.w3.org/TR/wai-aria-practices/">http://www.w3.org/TR/wai-aria-practices/</a><br clear="none" />
    WAI-ARIA Roadmap <a href="http://www.w3.org/TR/wai-aria-roadmap/">http://www.w3.org/TR/wai-aria-roadmap/</a><br clear="none" />
    WAI-ARIA User Agent Implementation Guide <a href="http://www.w3.org/TR/wai-aria-implementation/">http://www.w3.org/TR/wai-aria-implementation/</a></li>
</ul>
<p><strong>The content at these URIs will change when the Notes are updated.</strong> In most cases, you should not include numbers in these links, so that your links provide the latest information and best practices.</p>
<h3>Stable "dated URIs"</h3>
<p>In rare cases where you want to link to specific information in a Technique or other Note, not the latest information, use the dated URI that is listed at the top of the main Web page under "This version:". For example:</p>
<blockquote>The <code>&lt;a href="http://www.w3.org/TR/2008/NOTE-WCAG20-TECHS-20081211/"&gt;</code>Techniques for WCAG 2.0 published 11 December 2008<code>&lt;/a&gt;</code> states that "The WCAG WG encourages submission of such techniques so they can be considered for inclusion in this document...".</blockquote>
<h2><a name="waiaria" id="waiaria"></a>Referencing WAI-ARIA versus just ARIA</h2>
<p>"WAI-ARIA" is the abbreviation for the Accessible Rich Internet Applications documents. In order to avoid confusion,  <strong>please use "WAI-ARIA" (instead of just "ARIA"), at least in titles, headings, and on first reference in documentation.</strong></p>
<h2>Additional Information</h2>
<p>If you have additional questions, you can contact WAI directly at <a href="mailto:wai@w3.org">wai@w3.org</a>.</p>
<p>Related information is provided in <a href="http://www.w3.org/2005/05/tr-versions">Version Management in W3C Technical Reports (W3C-member-only link)</a>.<br>
</p>