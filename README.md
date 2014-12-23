### hubot-clj

#### Description
Packaged [hubot clojure](https://github.com/github/hubot-scripts/blob/master/src/scripts/clojure.coffee) for NPM

#### Installation
`npm install --save hubot-clj`

add `["hubot-clj"]` to your `external-scripts.json`.

#### Examples

`hubot clojure (map #(+ %1 5) [1 2 3 4 5])` -> `(6 7 8 9 10)`

`hubot clj (+ 1 2 3)` -> `6`