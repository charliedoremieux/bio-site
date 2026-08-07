```bio-meta
{
    "name": "Charlie Doremieux",
    "title": "Charlie Doremieux | Curriculum Vitae",
    "description": "Charlie Doremieux curriculum vitae.",
    "url": "https://charliedoremieux.github.io/bio-site/",
    "assets": "https://charliedoremieux.github.io/bio-site/assets",
    "date-created": "2020-04-21",
    "repo": "https://charliedoremieux.github.io/bio-site/",
    "tilecolor": "#f2f2f2"
}
```

# Charlie Doremieux

<figure class="gl-page-background gl-float-right gl-image-box" style="text-align: center;"><img src="assets/images/hero-image.jpg" alt="A photo of J. Doe" width="160" height="160" style="max-width: 160px;" /></figure>

I’m a second-year Ph.D. student in Philosophy at [Rutgers University](https://philosophy.rutgers.edu/). Presently, I am interested in Philosophy of Language and Metaphysics.

Prior to joining Rutgers, I studied Applied Mathematics and Philosophy from [The University of Colorado, Boulder](https://www.colorado.edu/).

I can be reached at <span id="_eml" class="gl-eml">charlie dot doremieux at rutgers dot edu</span>.

```bio-remove
Below we use a simple mechanism to mitigate email address reaping.
Change the encoding for your own email address.
```bio-remove
Below we use a simple mechanism to mitigate email address reaping.
Change the encoding for your own email address.
```

<!--[bio][protect]
<script type="application/javascript">
window.setTimeout(function ()
{
var addr = [115,111,109,101,111,110,101,64,101,120,97,109,112,108,101,46,99,111,109];
addr = String.fromCharCode.apply(String, addr);
var eml = document.getElementById('_eml');
eml.innerHTML = '<a href="mailto:' + addr + '">' + addr + '</a>';
eml.removeAttribute('class');
}, 600);
</script>
[bio]-->

## Building Blocks

```blog-bib

@comment
{
Use #bibitem_Venue_Key to refer to "Venue:Key".

It is possible to have multiple BibTeX blocks, which will be rendered independently. For example, you might want to have one block for each of "Publications", "Pre-prints", and "Manuscripts".

To support more information links (e.g., add "slides" or "pdf" links),
see "builder/marked.0.3.6/bibtex-service.js" line 109.
}

@online{GitHub:BibTeXTS,
  author = {Ji Luo},
  title = {{B}ib{T}e{X}-{TS}:
    General-Purpose Format-Preserving {{\BibTeX}} Parser
    in {T}ype{S}cript ({J}ava{S}cript)},

  biosite_url = {https://github.com/GeeLaw/bibtex-ts},
  biosite_venue = {GitHub},
  biosite_slides = {#},
}

@online{GitHub:Marked,
  author = {Christopher Jeffrey and others},
  title = {Marked: A {M}arkdown Parser and Compiler Built for Speed},

  biosite_url = {https://github.com/markedjs/marked},
  biosite_venue = {GitHub},
  biosite_demo = {https://marked.js.org/demo/},
}

@online{GitHub:KaTeX,
  author = {Khan Academy and others},
  title = "{{\KaTeX}}: Fast Math Typesetting for the Web",

  biosite_url = {https://github.com/KaTeX/KaTeX},
  biosite_venue = {GitHub},
  biosite_demo = {https://katex.org/},
}

```

## Accessibility Examples

```blog-bib
@misc{Example1,
  author = {First Author and Second Author},
  title = {Title without Equation}
}

@misc{Example2,
  author = {Author One and Author Two and Author Three},
  title = {Title with Equation $e^{i\pi}+1=0$}
}

@misc{Example3,
  author = {Sole Author},
  title = {Title with Annotated Equation $e^{i\pi}+1=0$},
  biosite_arialabel = {Title with Annotated Equation e to the i times pi plus one equals zero}
}

@misc{Example4,
  author = {Alice and Bob and Eve and Mallory and others},
  title = {Link without Equation},
  biosite_url = {#}
}

@misc{Example5,
  author = {Sailor{ }Moon and Tuxedo{ }Mask},
  title = {Link with Equation $e^{i\pi}+1=0$},
  biosite_url = {#}
}

@misc{Example6,
  author = {Youma and Cardian and Droid and Daimon and Lemures and Phage},
  title = {Link with Annotated Equation $e^{i\pi}+1=0$},
  biosite_url = {#},
  biosite_arialabel = {Link with Annotated Equation e to the i times pi plus one equals zero}
}
```
