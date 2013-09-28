ProtoSketch.css
===
*a stylesheet for giving your semantic html prototypes a sketched look*

What is it and how do I use it?
---
ProtoSketch is a simple stylesheet that transforms the look of your plain html markup into a sketch-like prototype.

You can use it in early prototyping phases of your project to highlight the structure of the elements on your page without specifying a distinct visal style.

To use it you need to nothing more than **drop in the stylesheet to your project and start coding** you own html and layout css. ProtoSketch's stylesheet automatically highlights the elements in your document by their implied semantic structure:

    <link href="folder/to/proto-sketch.css" rel="stylesheet" />
    
For your prototype you will most likely want to include your own styles for layouting the elements as well as coding some interactivity.

**ProtoSketch is not indended for use in any kind of production sense**. It is an additional tool for developers and UI/UX designers that allows you to style your html based prototypes. As such, there is no particular focus on browser backwards compability. You'll get the best outcome using latest versions of browsers supporting CSS3.
    
So what gets highlighted:
---
* Top level semantic and layout elements, like: `body`, `article`, `section`, `nav`, `header`, `footer`, `aside`
* forms and form elements like `form`, `fieldset`, `legend`, `label`, `input`
* other meaningful elements like `button`, `a`, `address`, `ul`, `ol`, `li` and typographic elements like `h1-6`, `em`, `strong`, `p`, `small`
* `img` and `video` (given you leave the src attribute or child tag empty) will display without content but with an icon only

Last but not least:
---
ProtoSketch was built with the idea in mind that you write up your prototype's html structure **without having to think about how to style it visually** for your demo, but still give it a visual structure that is understandable and highlights the different type of content blocks and elements. This relies to a big part on the use of semantic html elements and the creator's view on how they should be highlighted.

Contributing:
---
If you feel that this tool could be refined, please don't hesitate to modify the code or comment in the issues section. If you plan on contributing code please honor the use of the `less` css precompiler. 
And what next?
---
* I'd love to make variations or different themes for this stylesheet
* Some way to manually include or exclude certain tags might be a useful feature

**Changelog:**
v0.0.1 - 29.09.2013 - Initial release

**License:**
You can use, modify or distribute this code in any way you seem fit, as long as the original credit notice at the top is retained. No warranties.



