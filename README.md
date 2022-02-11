# cakebear

### Overview
I have been thinking about overcoming the barrier for allowing more diverse candidates to get into the development field much faster. Though JavaScript / Type Script is more & more popular in back-end development & is the first / easiet language to learn, it is not as perfomant as Go or Rust & doesn't help the developer naturally learn the lower-level development techniques. Rust & Go also have a very steep larning curve & are getting more & more popular due to their perfoamnce. They also pay more generally. 

My first attempt at decreasing the barrier of entry for more diverse candidaets is to take an easy-to-learn / much more widely known language like TypeScript & create a way to compile it down to a singel executable & get it close to or as performant as Go or Rust. This will allow companies to adopt this language as a way to get more diverse candidates with less experience & knowledge without sacrificing performance or ease of deployment.

### cakebear as a language
* cakebear is not a new language per se but rather allows developers to write in TypeScript &amp; then compiles that code down to a single executable.
* Performance should be close to or as good as Go & Rust
* Fully support & keep up with TypeScript
* Add additional typing on top of TypeScript for more precise compiling & coding
  * base64 type out of the box rather than just a string
   * e.g. `const base64Input: base64 = "some base64 string"` `const base64Input: string = "some base64 string"`
  * More number & float typing fr more precise numering 

### Princeples of cakebear
* always still support any type that exists in TypeScript so you can always write in plain TypeScript without issue. 
* Depricate our own custom types if TypeScript comes out with a corresponding type
 * e.g. We will take out our custom `base64` type if TypeScript adds it as a type 
* Be as performant as possible without sacrificing accessibility
* Follow the package management of Go or Rust by requiring approval by the cakebear org (currently know as the cakebear cave as a placeholder) before being added to the platform
* Avoid the bloat of NPM
* Have an officially supported web framework
 * Top 2 titles right now for framework are `frosting` & `honey`
