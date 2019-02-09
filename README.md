Fork from https://github.com/stovmascript/ionic-version and updated for ionic-4 usage.

### Install

```bash
npm i ionic-4-version --save -dev
```

### Example hook to `npm version` in inpackage.json

```
...
"scripts": {
	...
	"version": "ionic-version --skip-tag && conventional-changelog -i CHANGELOG.md -s && git add CHANGELOG.md"
}
...
```

### Many thanks to original ionic-version author.
