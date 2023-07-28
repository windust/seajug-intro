# SeaJUG Meeting Introduction Template

This template uses [Reveal.js](https://github.com/hakimel/reveal.js/) to construct a meeting intro for the Chicago Java Users Group. 

## Creating an intro

We can use the [git flow model](http://nvie.com/posts/a-successful-git-branching-model/) to create feature branches and releases for each meeting.

This allows us to change only the parts that vary between meetings and leave everything else in place.

## Showing the intro

Execute the following command from shell:

```bash
python -m SimpleHTTPServer
```

or if python 3
```bash
python3 -m http.server
```

Then point your browser at [http://localhost:8000](http://localhost:8000)

## Production

The project is hosted on GitHub Pages and available at https://seajug.org/intro
or https://windust.github.io/seajug-intro/
