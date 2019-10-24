# practicalcloud.github.io
Practical Cloud main site

## TODO
* add service worker for cache & offline terrain safety
* add traced svg inlined (but it will only show on 3G :D)
* more SEO stuff?
* test using https://github.com/Munter/subfont to get (possibly) more font performance


## Show

Show Torfinn how easy grid is (remove header tag first), e.g.

```css
    @media (min-width: 800px) {
      main {
        max-width: 30em;
        display: grid;
        grid-template-areas:
          "logo logo"
          "header contact";
        align-items: center;
      }
      .logo {
        grid-area: logo;
        justify-self: center;
      }
      h1 {
        grid-area: header;
      }
      .contact {
        grid-area: contact;
      }
    }
```