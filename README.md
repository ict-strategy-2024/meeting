# ICT 2024 STRATEGY MEETING


* * *
### Download

### What's in the download?


```
root/
├── index.html
├── css/
│   ├── base.css
│   └── colors.css
│   └── svg-icons.css (optional)
├── js/
│   ├── webslides.js
│   └── svg-icons.js (optional)
└── demos/
└── images/
```

## Features

- Navigation (horizontal and vertical sliding): remote presenters, touchpad, keyboard shortcuts, and swipe.
- Slide counter.
- Permalinks: go to a specific slide.
- Autoslide.
- Click to nav.
- Simple CSS alignments. Put content wherever you want (vertical centering...)
- 40+ components: background images/videos, quotes, cards, covers...
- Flexible blocks with auto-fill and equal height.
- Fonts: Roboto, Maitree (Serif), and San Francisco.
- Vertical rhythm (use multiples of 8).

## Markup

- Code is clean and scalable. It uses intuitive markup with popular naming conventions. There's no need to overuse classes or nesting.
- Each parent `<section>` in the `#webslides` element is an individual slide.

```html
<article id="webslides">
    <section>
        <h1>Slide 1</h1>
    </section>
    <section class="bg-black aligncenter">
    <!-- .wrap = container 1200px -->
        <div class="wrap">
            <h1>Slide 2</h1>
        </div>
    </section>
</article>
```

### Vertical Sliding

```html
<article id="webslides" class="vertical">
```

### CSS Syntax (classes)

- Typography: `.text-landing`, `.text-data`, `.text-intro`...
- Background Colors: `.bg-primary`, `.bg-apple`, `.bg-blue`...
- Background Images: `.background`,`.background-center-bottom`...
- Cards: `.card-50`, `.card-40`...
- Flexible Blocks: `.flexblock.clients`, `.flexblock.metrics`...

### Extensions


### Dive In!

 
### Credits

