This is currently a work in progress - feel free to alter or add definitions as necessary.

term | definition
-----|-----------
bikeshed | An important discussion about some non-fundamental part of the language (such as syntax or the libraries). [*See also*](http://www.catb.org/jargon/html/B/bikeshedding.html)
borrowed pointer |
bors |
box |
closure |
crate |
FFI | See _foreign function interface_.
foreign function interface |
heap allocation | A dynamic allocation performed either by `~` or `@`, which call to `malloc` in the default runtime (which is a statically-linked `jemalloc`)
inline |
lifetime |
macro |
managed pointer |
monomorphise | The act of generating specialized versions of generic constructs at compile time to improve run time performance. Perhaps best known from the MLton compiler: ["Whole-Program Compilation in MLton"](http://mlton.org/References.attachments/060916-mlton.pdf) Also see Niko Matsakis's answer on [Stackoverflow](http://stackoverflow.com/a/14198060) (the other answer is incorrect).
owned pointer |
raw pointer | 
rustdoc | The Rust documentation generator.
rustc | The Rust source code compiler.
rusti | The Rust interactive environment.
rustpkg | The official package manager for Rust programs and libraries.
sigil | A character placed in front of a type, identifier or literal. In the context of Rust, this usually refers to the pointer symbols: `&`, `~`, `@`, and `*`.
stack allocation | 
syntax extension |
task | Rust's fundamental unit of computation. Similar to a thread.
trait | Sort of like an interface. Identical (or nearly identical) to [Haskell's typeclasses](http://en.wikipedia.org/wiki/Type_class). Used for generics and dynamic dispatch.