### carbon-now-cli
---
https://github.com/mixn/carbon-now-cli

```js
const unfold = (f, seed) => {
  const go = (f, seed, acc) => {
    const res = f(seed)
    return res ? go(f, res[1], acc.concat([res[0]])) : acc
  }
  return go(f, seed, [])
}

```

```
npm i -g carbon-now-cli
yarn global add carbon-now-cli
npx carbon-now-cli <file>

carbon-now --help

carbon-now unfold.js
carbon-now unfold.js -i
carbon-now unfold.js -s 3 -e 6
carbon-now unfold.js -c
sudo apt-get install xclip
choco install nircmd
carbon-now unfold.js -s 3 -e 6 -l ~/Desktop -t example-23 -i
carbon-now unfold.js -s 3 -e 6 -i -o
carbon-now unfold.js -p <name-of-preset>
carbon-now unfold.js --config local-config.json -p dark
```

```
```


