debugging assistant for rapid iteration

## why this exists

i needed something that just works without reading 50 pages of docs.

## install

```bash
npm i craft-app
```

## use it

```js
import craftapp from 'craft-app'

craftapp({ input: 'data.json' })
```

## tech

runs on sveltx, probably buggy

## limitations

- sometimes slow on large files
- probably breaks on weird input
- not production ready

scratching my own itch
