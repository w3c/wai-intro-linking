---
title: Referencing and Linking to WAI Guidelines and Technical Documents
permalink: /standards/linking/
redirect_from: /
layout: default
github:
  repository: w3c/wai-intro-linking
  branch: gh-pages
---
<p>[@@ summary box]</p>
<p>This page provides general guidance on how to reference and link to guidelines and other technical documents. It suggests that you include a link to the overview page. It describes when to include a version number or &quot;dated URI&quot;, and when not to.</p>
<p>[@@ end summary box] </p>
<div>
  <h2>Page Contents</h2>
  <ul>
    <li><a href="#overview">Linking to Overview Pages</a></li>
    <li><a href="#trs">Referencing Guidelines and Other Technical Specifications</a></li>
    <li><a href="#wcag">Example: Linking to WCAG</a></li>
    <li><a href="#notes">Linking to Techniques and Other "Notes"</a></li>
    <li><a href="#waiaria">Referencing WAI-ARIA versus just ARIA</a></li>
  </ul>
</div>
<h2><a name="overview" id="overview"></a>Linking to Overview Pages</h2>
<p>In most cases, it is best to link to  the Overview page instead of the technical specification because <strong>the Overview page provides an introduction, links to related documents, and the status of revisions in progress</strong>. Overview pages include:</p>
<ul>
  <li>Web Content Accessibility Guidelines <strong>(WCAG) Overview</strong> <a href="http://www.w3.org/WAI/intro/wcag">http://www.w3.org/WAI/intro/wcag</a></li>
  <li>Authoring Tool Accessibility Guidelines <strong>(ATAG) Overview</strong> <a href="http://www.w3.org/WAI/intro/atag">http://www.w3.org/WAI/intro/atag</a></li>
  <li>User Agent Accessibility Guidelines <strong>(UAAG) Overview</strong> <a href="http://www.w3.org/WAI/intro/uaag">http://www.w3.org/WAI/intro/uaag</a></li>
  <li>Evaluation and Report Language <strong>(EARL) Overview</strong> <a href="http://www.w3.org/WAI/intro/earl">http://www.w3.org/WAI/intro/earl</a></li>
  <li><strong>WAI-ARIA Overview </strong>for Accessible Rich Internet Applications <a href="http://www.w3.org/WAI/intro/aria">http://www.w3.org/WAI/intro/aria</a></li>
</ul>
<h2><a name="trs" id="trs"></a>Referencing Guidelines and Other Technical Specifications</h2>
<p>WAI's technical specifications (WCAG, WAI-ARIA, and the others listed above)  use a "shortname" in the URI (the Web address); for example, "WCAG" and "ATAG" are  shortnames. Specific versions are indicated with a number in the URL. Without a number, you get the latest version.</p>
<h3>Latest completed version</h3>
<p>To link to the latest completed version, <strong>do not include a number</strong>. For example:</p>
<ul>
  <li>Web Content Accessibility Guidelines (WCAG) <a href="http://www.w3.org/TR/WCAG/">http://www.w3.org/TR/WCAG/</a></li>
  <li>Authoring Tool Accessibility Guidelines (ATAG) <a href="http://www.w3.org/TR/ATAG/">http://www.w3.org/TR/ATAG/</a></li>
  <li>User Agent Accessibility Guidelines (UAAG) <a href="http://www.w3.org/TR/UAAG/">http://www.w3.org/TR/UAAG/</a></li>
  <li>Accessible Rich Internet Applications (WAI-ARIA) <a href="http://www.w3.org/TR/wai-aria/">http://www.w3.org/TR/wai-aria/</a></li>
</ul>
<p><strong>Note:</strong></p>
<ul>
  <li><strong>Links: </strong>The content at these links will change when new versions are published. New versions will  often  change the internal links (called <dfn>fragments</dfn>, <dfn>targets</dfn>, or <dfn>anchors</dfn>, e.g., "#focus-area").</li>
  <li><strong>References:</strong> When policies do not include a version number, they can be interpreted to reference the latest version.</li>
</ul>
<h3>Specific  version</h3>
<p>We recommend that you reference the latest version <em>without</em> a number as explained above, unless there is a  reason to reference a specific version. To link to a specific version, include the version number, for example:</p>
<ul>
  <li>Authoring Tool Accessibility Guidelines (ATAG) 2.0 <a href="http://www.w3.org/TR/ATAG20/">http://www.w3.org/TR/ATAG20/</a></li>
  <li>User Agent Accessibility Guidelines (UAAG) 2.0 <a href="http://www.w3.org/TR/UAAG20/">http://www.w3.org/TR/UAAG20/</a></li>
  <li>Web Content Accessibility Guidelines (WCAG) 2.0 <a href="http://www.w3.org/TR/WCAG20/">http://www.w3.org/TR/WCAG20/</a></li>
  <li> Accessible Rich Internet Applications (<abbr title="Accessible Rich Internet Applications">WAI-ARIA</abbr>) 1.1 <a href="https://www.w3.org/TR/wai-aria-1.1/">https://www.w3.org/TR/wai-aria-1.1/</a> </li>
</ul>
<h3>Links to the technical specification <em>and</em> the Overview page</h3>
<p>Even when linking to the standard, it is usually good to include a link to the Overview page as well. For example:</p>
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
        <td>For links to the latest version of the WCAG standard</td>
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
    </tbody>
  </table>
</div>
<!-- end main -->
<p><strong>For more formal guidance on referring to WCAG, see <a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/appendixA.html">Appendix A How to refer to WCAG 2.0 from other documents</a>.</strong></p>
<h2><a name="notes" id="notes"></a>Linking to Techniques, Understanding Documents, and Other "Notes"</h2>
<p>While the standards listed above will not change once they are completed, most of the the  supporting  material that is advisory will be updated. Supporting technical material is usually published as "W3C Working Group Notes". This includes:</p>
<ul>
  <li>Techniques for WCAG <a href="http://www.w3.org/TR/WCAG-TECHS/">http://www.w3.org/TR/WCAG-TECHS/</a></li>
  <li>Understanding WCAG <a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/">http://www.w3.org/TR/UNDERSTANDING-WCAG/</a></li>
  <li> <abbr title="Accessible Rich Internet Applications">WAI-ARIA</abbr> Authoring Practices 1.1 <a href="https://www.w3.org/TR/wai-aria-practices-1.1/">https://www.w3.org/TR/wai-aria-practices-1.1/</a></li>
</ul>
<p><strong>The content at these URIs will change when they are updated.</strong> In most cases, you should not include numbers in these links, so that your links provide the latest information and best practices.</p>
<h3>Stable "dated URIs"</h3>
<p>In rare cases when you want to link to specific information in a Technique or other Note, <strong>and not the latest information</strong>, use the &quot;dated URI&quot; that is listed at the top of the main web page under "This version:". For example:</p>
<blockquote>The <code>&lt;a href="http://www.w3.org/TR/2008/NOTE-WCAG20-TECHS-20081211/"&gt;</code>Techniques for WCAG 2.0 published 11 December 2008<code>&lt;/a&gt;</code> states that "The WCAG WG encourages submission of such techniques so they can be considered for inclusion in this document...".</blockquote>
<h2><a name="waiaria" id="waiaria"></a>Referencing WAI-ARIA versus just ARIA</h2>
<p>"WAI-ARIA" is the formal abbreviation for the Accessible Rich Internet Applications documents. It is now acceptable to use just &quot;ARIA&quot; in informal references<strong>.</strong></p>
<h2>Additional Information</h2>
<p>If you have additional questions, you can contact WAI directly at <a href="mailto:wai@w3.org">wai@w3.org</a>.</p>
<p>Related information is provided in <a href="http://www.w3.org/2005/05/tr-versions">Version Management in W3C Technical Reports (W3C-member-only link)</a>.</p>