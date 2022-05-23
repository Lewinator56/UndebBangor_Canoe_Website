# UndebBangor_Canoe_Website
backups and tutorials for updating the bangor uni canoe club website on the unioncloud system

## Code Templates 
Copy these into their appropriate sections and modify links and images where necessary.
Sections marked in [ ] should be replaced with the text as identified within them, the square brackets should be removed too.


#### Committee member card template
The image source should be obtained from uploaded images on the unioncloud system.<br>
The 'card-title' span should have its text set to the role of the individual.<br>
The [REPLACE WITH NAME] should be replaced with the name of teh individual.<br>
The mailto address should be the university email address of the individual.<br>
The text within the <a> element for the mailto should be replaced with the university email address of the individual.

A fully completed example of this can be seen in [source.html](source.html)

```html
<div class="card card-info">
  <div class="card-image">
    <img src="[REPLACE WITH IMAGE URL]" />
    <span class="card-title">[REPLACE WITH ROLE]</span>
  </div>
  <div class="card-content">
    <p>{REPLACE WITH NAME] <br />
      <a href="mailto:[RELACE WITH UNI EMAIL ADDRESS]">[REPLACE WITH UNI EMAIL ADDRESS]</a>
    </p>
  </div>
</div>
```


#### Social media link template
replace the href with the link to the social page, and replace the icon class with the appropriate icon from fontawesome icons (you can find class names on the fontawesome website) dont remove the 'center-icon' class though.
```html
<a class="button flat footer-links dark footer-text-copyright" href="https://www.instagram.com/bangorunicanoeclub/" target="_top">
  <i class="fab fa-instagram center-icon"></i>
</a>
```
