# Mark Text (Modified)

This is my personal fork of [MarkText](https://github.com/marktext/marktext), with the following minor edits:

- As MarkText doesn't support custom themes & I prefer a darker theme, I've made some color changes to the `Material-dark` theme to make my own.

- I've added underline style for the `H2` heading for better readibility of long form markdown files. This change will persist on theme changes (from the Theme menu).

## Notes

- I like MarkText because of how it handles markdown editing. However, there are some bugs in the App.

- Although I was careful not to introduce any new bug because of my edits, I'm still to learn the proper architecture of MarkText, so my edits were more like swiss army knife edits than anything else. 

- I've not published any package with my edits, so if you want to use my changed version, you'll have to compile it from the source. If you are not comfortable with that sort of thing, then it's better to use the [Original MarkText](https://github.com/marktext/marktext).

## Source compilation notes

```shell
# install dependencies if not installed already
yarn install

# build the app and packages
yarn run build

# buid the app only
yarn run build:bin

# build for mac only
yarn run release:mac

# Build and run Mark Text in developer mode
yarn run dev
```

## Screenshot

> Following is a screenshot of MarkText with my changed theme:
