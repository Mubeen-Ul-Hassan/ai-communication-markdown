# Lists
You can organize lists into ordered and unordered lists.

## Ordered List
Ordered list are done with number followed by period. The numbers don’t have to be in numerical order, but the will list start with the number one.

Markdown | HTML | Rendered Output
:-- | :-- | :--
`1. Mubeen`<br>`2. Umar` | `<ol>`<br>`  <li>Mubeen</li>`<br>`  <li>Umar</li>`<br>`</ol>` | 1. Mubeen<br>2. Umar
`1. Mubeen`<br>`1. Umar` | `<ol>`<br>`  <li>Mubeen</li>`<br>`  <li>Umar</li>`<br>`</ol>` | 1. Mubeen<br>2. Umar
`1. Software Engineering`<br>`2. Data Science`<br>`   1. Machine Learning`<br>`   2. Artifical Intelligence` | `<ol>`<br>`  <li>Software Engineering</li>`<br>`  <li>Data Science</li>`<br>`  <ol>`<br>`    <li>Machine Learning</li>`<br>`    <li>Artifical Intelligence</li>`<br>`  <ol>`<br>`</ol>` | <ol><li>Software Engineering</li><li>Data Science</li><ol type="1"><li>Machine Learning</li><li>Artifical Intelligence</li></ol></ol> 

## Unordered List
To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.

Markdown | HTML | Rendered Output
:-- | :-- | :--
`- Mubeen`<br>`- Umar` | `<ul>`<br>`   <li>Mubeen</li>`<br>`   <li> Umar</li>`<br>`</ul>` | <ul><li>Mubeen</li><li>Umar</li></ul>
`* Software Engineering`<br>`* Data Science`<br>`   * Machine Learning `<br>`   * Artifical Intelligence` | `<ul>`<br>`  <li>Software Engineering</li>`<br>`  <li>Data Science</li>`<br>`  <ul>`<br>`    <li>Machine Learning</li>`<br>`    <li>Artifical Intelligence</li>`<br>`  <ul>`<br>`</ul>` | <ul><li>Software Engineering</li><li>Data Science</li><ul><li>Machine Learning</li><li>Artifical Intelligence</li></ul></ul>
