 # DRUMS in SPACE :rocket:

![Screenshot](../img/drums.png?raw=true?style=centerme)

## Lessons Learned

Some stuff learned from this first [JS30](https://javascript30.com/) challenge JavaScript Drum Kit:

* Nice to learn vanilla JS functionality:)
* DOM **Elements** vs **Attributes**: accessed differently in code. 

This is were I was stuck for a bit:

```javascript
 function playSound(e){
    //audio is an element so you just use 'audio' to access it
    const audio = document.querySelector(`audio[data-key="${e.keyCode}"]`);
    //key is an attribute that is why you use '.key' to access it 
    const key = document.querySelector(`.key[data-key="${e.keyCode}"]`);   
```
 
Other stuff learned:

* Making awesome md files. Learn best practices and Markdown formatting at [Github's Markdown site.](https://guides.github.com/features/mastering-markdown/)
* Adding a favicon to your website. I used a premade one from [here.](https://www.favicon-generator.org/)

Some useful resources that were used in this challenge:

* Difference betweeen DOM elements and attributes [w3schools.](https://www.w3schools.com/xml/xml_dtd_el_vs_attr.asp)
