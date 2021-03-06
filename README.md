# technology-modernization-fund
Welcome to the party!

---

## Images

Images can be uploaded into the `/images/` folder:

Any image that is in the `/images/` folder can be included in a page with one of the following shortcodes.

You'll need to provide three things:
- path + filename — this is the path within the `/images/` folder
- caption — a clear description of the image
- alt-text — a description of the image for people who cannot see it


**In-line Image**
```
{% include image.html path="contact-center/sonny.png" alt-text="this is the alt text" caption="carrot" %}
```

**Wide Image**
```
{% include image-wide.html path="contact-center/sonny.png" alt-text="this is the alt text" caption="Carrot" %}
```

## Videos

YouTube videos can be embedded in pages.

1. Copy the the `ID` of the youtube video URL
  1. Example — `https://www.youtube.com/watch?v=JcwG4iwN6Fk` the ID of this video is `JcwG4iwN6Fk`
2. Paste the `ID` into the following shortcode.

```
{% include youtube.html id="JcwG4iwN6Fk" %}
```
