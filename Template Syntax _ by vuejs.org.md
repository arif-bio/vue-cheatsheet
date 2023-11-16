# Template Syntax ​

## Metadata
- Author: vuejs.org
- Category: article
- URL: https://vuejs.org/guide/essentials/template-syntax.html
## Highlights

<span>Message: {{ msg }}</span>

<span v-html="rawHtml"></span>

<div v-bind:id="dynamicId"></div>

<div :id="dynamicId"></div>

<button :disabled="isButtonDisabled">Button</button>
Note: //disabled="true"
objectOfAttrs = { id: 'container', class: 'wrapper' }

<div v-bind="objectOfAttrs"></div>

<div :id="`list-${id}`"></div>

<time :title="toTitleDate(date)" :datetime="date">
