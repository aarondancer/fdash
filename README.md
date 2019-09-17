# fdash

A faster, leaner drop-in replacement for lodash.

## Project goals
1. Near 100% lodash compatibility. Validated by porting lodash's tests. 
2. Increased performance. Validated by benchmarks.
3. Decreased bundle size. Validated by comparing bundle sizes for each package.
4. Leverage modern JS features. Ship ES modules, use built-in language features when available / more performant.
5. Statically typed. 100% written in TypeScript. Distributed as JS w/ type definitions.
6. Maintain IE11 compatibility without compromising the above goals. Achieved through polyfills, babel plugins, and/or IE11 specific versions of packages. 

### Out-of-scope
* Flow type definitions
* IE8-10 compatibility
* Underscore drop-in replacement compatibility
* lodash-fp compatibility (for the time being)

## Milestones

Each minor release until v1 will add approximately 10 lodash functions.

### 0.1.0
- get
- set
- pick
- omit
- isEqual
- isPlainObject
- cloneDeep
- uniq
- includes

### 0.2.0 (tentative)
- is_ (string, number, array, etc)
- flatten
- flattenDeep
- forEach
- forEachRight
- map
- reduce
- reducceRight
- filter
- intersection
- intersectionBy
- intersectionWith

### 0.3.0 (tentative)
- throttle
- debounce
- merge
- mergeWith
- groupBy
- orderBy
- sortBy
- every
- find
- findLast
