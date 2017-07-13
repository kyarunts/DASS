# DASS
Dramatically awesome style sheets

<h3>Setup</h3>
<ol>
  <li>Copy the files into any directory you would like to</li>
  <li>Import the <em>_imports.scss</em> file at the top of your .scss file</li>
</ol>

<h3>Variables configuration</h3>
<ol>
  <li>Set your breakpoints in the <em>_variables.scss</em> file - inside the <strong>$mapBreakpoints</strong></li>
  <li>Add your variables in the <em>_variables.scss</em> file - inside the <strong>$mapVariables</strong></li>
</ol>

<h3>Usage</h3>
<ol>
  <li>In your .scss file write the following:<br/><code>@include _(<em>css-rule</em>, <em>rule-value</em>)</code></li>
  <li>Write the following for including mixins:<br/><code>@include breakpoint(<em>breakpoint-name</em>) {
    @include _(<em>css-rule</em>, <em>rule-value</em>);
  }</code></li>
</ol>
