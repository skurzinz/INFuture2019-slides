## Event-based Modelling of a Major Historical Government Source: Ministerratsprotokolle 1848–1918

@snap[south span-100 text-06]
Wladimir Fischer-Nebmaier, Stephan Kurz,
Austrian Academy of Sciences
@snapend
---

## What and why

- Scholarly Print Edition > Digital Scholarly Edition
- Historical documents (https://oesta.gv.at/)
- Long-term project of AAS
- Mapping the past to understand the present

---

## Methods

![IMAGE](assets/img/mrpactivitydiagram.gv.png)

---

## Methods

- .docx for transcription
- TEI XML ~standard markup
  - auxiliary entity data
  - LOD connection

---

## Tools/stack

- eXist-db
- Zotero/bibsonomy
- APIS

---

## Deployment ecosystem

![IMAGE](assets/img/mrpdeploymentdiagram.gv.png)


---

## Published Tools and Sources

- https://hw.oeaw.ac.at/ministerrat/
- http://mrptestapp.acdh-dev.oeaw.ac.at/
- https://github.com/skurzinz/mrptestapp/
- https://github.com/skurzinz/mrptestdata/
- https://github.com/skurzinz/mrpbiblio/
- https://gitpitch.com/skurzinz/INFuture2019-slides/

---

## Go use it

liberate some more history data.

@snap[south span-100 text]
feedback and/or contribution is always welcome.
@snapend

---

@snap[south span-100 text-white]
Snap Layouts let you create custom slide designs directly within your markdown.
@snapend

---?color=linear-gradient(90deg, #5384AD 65%, white 35%)
@title[Add A Little Imagination]

@snap[north-west h4-white]
#### And start presenting...
@snapend

@snap[west span-55]
@ul[list-spaced-bullets text-white text-09]
- You will be amazed
- What you can achieve
- *With a little imagination...*
- And **GitPitch Markdown**
@ulend
@snapend

@snap[east span-45]
@img[shadow](assets/img/conference.png)
@snapend

---

@snap[north-east span-100 text-pink text-06]
Let your code do the talking!
@snapend

```sql zoom-18
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id
FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");
```

@snap[south span-100 text-gray text-08]
@[1-5](You can step-and-ZOOM into fenced-code blocks, source files, and Github GIST.)
@[6,7, zoom-13](Using GitPitch live code presenting with optional annotations.)
@[8-9, zoom-12](This means no more switching between your slide deck and IDE on stage.)
@snapend


---?image=assets/img/presenter.jpg

@snap[north span-100 h2-white]
## Now It's Your Turn
@snapend


@snapend
