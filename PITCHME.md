---?image=assets/image/jeremy-bishop.jpg

# AeronNetLab Development

### Results so far

---

## Disclaimer

---

## DEMO!

---

## NUMBERS

- Code Presenting |
- Repo Source, Static Blocks, GIST |
- Custom CSS Styling |
- Slideshow Background Image |
- Slide-specific Background Images |
- Custom Logo, TOC, and Footnotes |

---

## Architecture

---

## Results 

- Team-Building |

---

## Team

- Maria+ (+R) |
- Tigran+ |
- Alexey =>+ (+R) |
- Max ? |

---?image=assets/image/octavian-rosca.jpg

## Risks

- Gitlab
- No CI
- Student Diplomas (+R -D)
- Me
  - TL
    - Tasks setting
    - Code Review
  - DevOps
  - Backend Dev
  - PM (Godnik) 

---

# What to do NEXT?

options

- VALUE? |
- Innopolis |
- Business |
- Logic |
- Parallelization

---

## 1. Mandatory Technical Tasks

Need to be done
First half of january (including holidays)

- Fix Bugs |
- Experiments |
- TDD |
- Refactoring |
- Retrospective |
- Workflow Adjustment |

---

## 2. Finish pipeline

Valuable for us

- Export (suitable format) |
- Import |
  - SpaceNet
  - Grab California Fires |
  - etc.
- Improvements
  - GeoServer speed

---

## X. Fluorish

How to make it unique and valuable?

- Smart Tools |
  - MagicWand |
  - Supervisely, LabelMe |
  - Look at GIS tools and technics |
- Join external markup & tiles |
  - Get OSM, edit it and apply

---

<img class="progressiveMedia-image js-progressiveMedia-image" data-src="https://cdn-images-1.medium.com/max/2000/1*nQO-Xa0L298tSBmjsGyRIA.gif" src="https://cdn-images-1.medium.com/max/2000/1*nQO-Xa0L298tSBmjsGyRIA.gif">

- Wow effect for Demo |
- Research |

---

## X. Multi-user

Many boring tasks

- Authentication |
- Authorization |
- Assesment |
- Monitoring |
- AdminUI ? |

---

## X. Change Detection Manual Markup Tool

---

## X. Non-Manual Markup Works

- MOZ
- GeoTrellis
  - Potsdam Example 
- BigData platform


---?code=src/go/server.go&lang=golang&title=Golang File

@[1,3-6](Present code found within any repo source file.)
@[8-18](Without ever leaving your slideshow.)
@[19-28](Using GitPitch code-presenting with (optional) annotations.)

---?image=assets/image/john-reign-abarintos.jpg

@title[JavaScript Block]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---?gist=onetapbeyond/494e0fecaf0d6a2aa2acadfb8eb9d6e8&lang=scala&title=Scala GIST

@[23](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](And code-presenting works seamlessly for GIST too, both online and offline.)

---?image=assets/image/kyle-gregory-devaras.jpg

## Template Help

- [Code Presenting](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Repo Source](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides), [Static Blocks](https://github.com/gitpitch/gitpitch/wiki/Code-Slides), [GIST](https://github.com/gitpitch/gitpitch/wiki/GIST-Slides) 
- [Custom CSS Styling](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Slideshow Background Image](https://github.com/gitpitch/gitpitch/wiki/Background-Setting)
- [Slide-specific Background Images](https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting), [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents), and [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---?image=assets/image/gitpitch-audience.jpg

### Template Versions

- #### [Base Template  @fa[external-link gp-download]](https://gitpitch.com/gitpitch/templates/space)
- #### [Code Maximized @fa[external-link gp-download]](https://gitpitch.com/gitpitch/templates/space?p=codemax)
- #### [Speaker Notes @fa[external-link gp-download]](https://gitpitch.com/gitpitch/templates/space?p=speaker)

---?image=assets/image/kyle-gregory-devaras.jpg

### Questions?

<br>

@fa[twitter gp-contact](@gitpitch)

@fa[github gp-contact](gitpitch)

@fa[medium gp-contact](@gitpitch)

---?image=assets/image/gitpitch-audience.jpg

@title[Download this Template!]

### Get your presentation started!
### [Download this template @fa[external-link gp-download]](https://gitpitch.com/template/download/space)

