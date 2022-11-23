# Translating tutorial

This tutorial is divided in 2 parts, which is divided in how many files you have to touch.
### Translationdata.json
To translate this website you will have to follow these instructions
1. Open [translationdata.json](./translationdata.json)
2. Copy the english translation(from lines 2 to 27 without the comma ",")
3. Add a comma to the end of the last translation(to this: "}")
4. Paste what you have copied
5. Translate everything, the title should be the acronym of a the language<br>


Doubts? see the Translationdata.json example at the bottom of this page
### Settings.html
1. Open [settings.html](./settings.html)
2. In about line 19, you will find a select html element <br> then one line before. Copy the previous elemente, and change how you write it. And the value change it to the title(acronym) that you put in the [translationdata.json](./translationdata.json)






# Translationdata.json example
**THIS IS AN EXAMPLE** <br>
The end of your file should look likes this:

```
"previous language acronym":{
        [translation]
},<br>
"language translating acronym":{
        [translation]
    }<br>
}
```

# Still with doubts?
See the video tutorial [here](https://www.youtube.com/watch?v=X0S9CvgGs6E)