---
title: 'Home'
---

<!-- vim: syntax=html -->

<h1 style="text-align:center">IPM - Group 23
</h1>


<p style="text-align:center"><b>Lab class:</b> p3 </p>

<h3 style="text-align:center">Team members</h3>

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


<div class="image-container">
    <figure class="image-box" onclick="document.getElementById('dialog-AF').showModal()">
        <img src="../IPM3/foto-AF.png"" alt="Photo of Alexandre" width="200" height="90">
        <figcaption>Alexandre Fernandes<br>- 58239 -</figcaption>
    </figure>
    <figure class="image-box" onclick="document.getElementById('dialog-AR').showModal()">
        <img src="../IPM3/foto-AR.jpeg" alt="Photo of André" width="200" height="90">
        <figcaption>André Ribeiro<br>- 59835 -</figcaption>
    </figure>
    <figure class="image-box" onclick="document.getElementById('dialog-GG').showModal()">
        <img src="../IPM3/foto-GG.jpeg" alt="Photo of Gonçalo" width="200" height="90">
        <figcaption>Gonçalo Gingeira<br>- 60355 -</figcaption>
    </figure>
    <figure class="image-box" onclick="document.getElementById('dialog-GF').showModal()">
        <img src="../IPM3/foto-GF.png" alt="Photo of Guilherme" width="200" height="90">
        <figcaption>Guilherme Figueira<br>- 60288 -</figcaption>
    </figure>
</div>

<dialog id="dialog-GF">
    <h4 style="text-align:center"> Guilherme Figueira
    </h4>
    <ul>
        <li><b>Student number:</b> 60288 </li>
        <li><b>Email:</b> <a href="mailto:gr.figueira@campus.fct.unl.pt">gr.figueira@campus.fct.unl.pt</a></li>
        <li><b>Course:</b> MIEI</li>
    </ul>
    <form method="dialog">
    	<button>Close</button>
    </form>
    </dialog>

<dialog id="dialog-GG">
    <h4 style="text-align:center"> Gonçalo Gingeira 
    </h4>
    <ul>
        <li><b>Student number:</b> 60355</li>
        <li><b>Email:</b> <a href="mailto:g.gingeira@campus.fct.unl.pt">g.gingeira@campus.fct.unl.pt</a></li>
        <li><b>Course:</b> MIEI</li>
    </ul>
    <form method="dialog">
    	<button>Close</button>
    </form>
</dialog>

<dialog id="dialog-AR">
    <h4 style="text-align:center"> André Ribeiro 
    </h4>
    <ul>
        <li><b>Student number:</b> 59835 </li>
        <li><b>Email:</b> <a href="mailto:at.ribeiro@campus.fct.unl.pt">at.ribeiro@campus.fct.unl.pt</a></li>
        <li><b>Course:</b> MIEI</li>
    </ul>
    <form method="dialog">
    	<button>Close</button>
    </form>
</dialog>


<dialog id="dialog-AF">
    <h4 style="text-align:center"> Alexandre Fernandes
    </h4>
    <ul>
        <li><b>Student number:</b> 58239 </li>
        <li><b>Email:</b>  <a href="mailto:aal.fernandes@campus.fct.unl.pt">aal.fernandes@campus.fct.unl.pt</a></li>
        <li><b>Course:</b> MIEI</li>
    </ul>
    <form method="dialog">
    	<button>Close</button>
    </form>
</dialog>

</div>
