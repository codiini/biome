---
"@biomejs/biome": patch
---

Fixed [#6003](https://github.com/biomejs/biome/issues/6003). `noUselessUndefinedInitialization` no longer reports exported variables initialized to `undefined`. In frameworks like Svelte, exported variables with `undefined` initialization are used to declare optional props.
