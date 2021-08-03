# Widgets

# Sample Config

```json
[
  {
    "id": "",
    "type": "title",
    "props": {
      "title": "Divine UK",
      "subTitle": "Everyday at 6pm GMT",
      "size": "h1"
    }
  },
  {
    "id": "",
    "type": "event",
    "props": {
      "title": "Redefining Love in our Culture",
      "link": "Xp0DAETI7b8",
      "type": "youtube",
      "time": "2021-02-13T11:00:00+00:00"
    }
  },
  {
    "id": "",
    "type": "youtubeLink",
    "props": {
      "title": "Redefining Love in our Culture",
      "id": "Xp0DAETI7b8"
    }
  },
  {
    "id": "",
    "type": "imageLink",
    "props": {
      "title": "Weekly Intercession",
      "link": "https://us02web.zoom.us/j/84217167077?pwd=aWkyR0JLWXkyN2ZTVkRoWVo0SlJwQT09",
      "imageURL": "https://img.youtube.com/vi/Ih-Hm2UBOdI/mqdefault.jpg"
    }
  },
  {
    "id": "",
    "type": "textLink",
    "props": {
      "title": "Newsletter",
      "link": "https://divineuk.org/newsletter",
      "size": "h1"
    }
  }
]
```

## Title

```json
    {
      "id": "",
      "type": "title",
      "props": {
        "text": "Divine UK",
        "size": "h1",
        "align": "center",
        "color": "primary"
      }
    }
```
#### Properties

 - text
 - size - h1, h2, h3, h4
 - align - left, center, right
 - colour - primary, secondary, tertiary

## Image

    {
      "id": "",
      "type": "image",
      "props": {
        "src": "url",
        "aspect_ratio": "1.3",
        "link": "divineuk://",
        "alt_text": ""
      }
    }
#### Properties

 - src - Source url
 - aspect_ratio - 4/3; 16/10 etc.
 - link - Fir the future, when we want to link to another page in the app
 - alt_text - For accessibility

## Carousel

     {
      "id": "",
      "type": "carousel",
      "props": {
        "aspect_ratio": "1.3",
        "images": [
          {
            "src": "url",
            "alt_text": ""
          }
        ]
      }
    }
#### Properties

 - aspect_ratio - 4/3; 16/10 etc.
 - images - array of images
 - 
