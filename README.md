# \<papyrus-details\>

Expandable/collapsible summary and details with animation

[![Build status](https://travis-ci.org/AqoviaElements/papyrus-details.svg?branch=master)](https://travis-ci.org/AqoviaElements/papyrus-detailsT)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/AqoviaElements/papyrus-details)

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="papyrus-details.html">
	<link rel="import" href="./demo/container-with-lang-choice.html">
    <style>
      papyrus-details { font-family: Roboto; background-color: #ddd; padding: 1em; border-radius: 4px; } 
      summary { font-size: 120%; font-weight: bold; }
    </style>
	<container-with-lang-choice lang="en" available-languages-expr="Object.getOwnPropertyNames(PapyrusDetails.resources)">
      <next-code-block></next-code-block>
	</container-with-lang-choice>
  </template>
</custom-element-demo>
```
-->
```html
<papyrus-details>
  <summary>What is this component for?</summary>
  <p>Use this component for presenting
    <ul>
      <li>hidden information</li>
      <li>questions and answers</li>
      <li>summaries and details</li>
      <li>images, tables or figures</li>
      <li>any drill-down information</li>
  </ul></p>
</papyrus-details>
```
