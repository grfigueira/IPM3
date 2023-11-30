---
title: 'Project'
---

## Feast - Your cooking companion

![logo](../logo.png)

<br>

---

### Reports

#### [Stage 1: Project Proposal](../G_23_stage1.pdf)

#### [Stage 2: User and Task analysis](../G_23_stage2.pdf)

#### [Stage 3: 1st Prototype](../G_23_stage3.pdf)

#### [Stage 4: Computational Prototype](../G_23_stage4.pdf)

<h4><a href="#" onclick="document.getElementById('stage5-dialog').showModal(); return false;">Stage 5: Heuristic Evaluation</a></h4>

#### [Stage 6: Evaluation results and presentation](../G_23_stage6.pdf)

---

### Description 

**FEAST** is an app that aims to solve all the problems related to the searching and sharing of recipes for users of all skill levels in what comes to cooking experience.

Great importance is given to the filtering in the search of recipes with customization of the user's experience with features that want to take special attention to allergies, intolerances, and availability of ingredients.

<style>

    article, fieldset, dialog {
  border: 1px solid var(--border);
  padding: 1rem;
  border-radius: var(--standard-border-radius);
  margin-bottom: 1rem;
}

.image-container {
    display: flex; /* Display the figures in a row */
    justify-content: space-between; /* Space evenly between figures */
}

.image-box {
    flex: 1;
    text-align: center;
    margin-right: 30px;
    transition: transform 0.2s; /* Add a transition for the transform property */
    cursor: pointer;
}

.image-box:hover {
    transform: scale(1.1); /* Increase the size by 10% on hover */
}

/* Remove the margin-right from the last image-box to avoid extra space */
.image-box:last-child {
    margin-right: 0;
}

li, ul, a {
  outline: none;
  -moz-outline-style: none;

}
figure {
    flex: 1; /* Each figure takes up an equal portion of the container */
    text-align: center; /* Center align contents */
    margin-right: 30px;
}

figure:last-child {
    margin-right: 0;
}

:root,
::backdrop {
  /* Set sans-serif & mono fonts */
  --sans-font: -apple-system, BlinkMacSystemFont, "Avenir Next", Avenir,
    "Nimbus Sans L", Roboto, "Noto Sans", "Segoe UI", Arial, Helvetica,
    "Helvetica Neue", sans-serif;
  --mono-font: Consolas, Menlo, Monaco, "Andale Mono", "Ubuntu Mono", monospace;
  --standard-border-radius: 5px;

  /* Default (light) theme */
  --bg: #fff;
  --accent-bg: #f5f7ff;
  --text: #212121;
  --text-light: #585858;
  --border: #898EA4;
  --accent: #0d47a1;
  --code: #d81b60;
  --preformatted: #444;
  --marked: #ffdd33;
  --disabled: #efefef;
}

@media (prefers-color-scheme: dark) {
  :root,
  ::backdrop {
    color-scheme: dark;
    --bg: #212121;
    --accent-bg: #2b2b2b;
    --text: #dcdcdc;
    --text-light: #ababab;
    --accent: #ffb300;
    --code: #f06292;
    --preformatted: #ccc;
    --disabled: #111;
  }
  /* Add a bit of transparency so light media isn't so glaring in dark mode */
  img,
  video {
    opacity: 0.8;
  }
}

article, fieldset, dialog {
  border: 1px solid var(--border);
  padding: 1rem;
  border-radius: var(--standard-border-radius);
  margin-bottom: 1rem;
}

dialog {
  max-width: 40rem;
  margin: auto;
}

dialog::backdrop {
  background-color: var(--bg);
  opacity: 0.8;
}

@media only screen and (max-width: 720px) {
  dialog {
    max-width: 100%;
    margin: auto 1em;
  }
}

</style>

<dialog id="stage5-dialog">
    <form method="dialog">
        <h5><a href="#" onclick="window.location.href = '../G_23_stage5_sent.pdf' ">Sent evaluation</a></h5>
        <h5><a href="#" onclick="window.location.href = '../G_23_stage5_ours.pdf' ">Received evaluation</a></h5>
    	<button>Close</button>
    </form>
</dialog>