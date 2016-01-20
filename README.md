# Prerequisites

- node
- grunt, grunt-cli
- bower

# Initial setup

```
npm install
bower install
```

# Running the presentation

```
grunt serve
```

# Usage

See [https://github.com/slara/generator-reveal](https://github.com/slara/generator-reveal)

## Creating a new slide

yo reveal:slide "Slide Title" --attributes

i.e.:

yo reveal:slide "Slide Title" --markdown

will create a new file file `silde-title.md` within the folder `slides`.
The generator will also update the file `slides/list.json`.
