You want to contribute to Rust? Frankly, you've made an excellent decision. Rust is developed by a small and inclusive community that take's *very kindly* to strangers. You're going to have a good time.

The way most people seem to get involved is by simply trying to write Rust code. Inevitably you will hit a bug or missing feature, at which point you may feel compelled to write a patch. Before you sit down to write

Another way to get involved is to look through the [issue tracker](http://github.com/mozilla/rust/issues) for issues labeled with "E-easy", "I-enhancement", "I-wishlist", and/or "A-an-interesting-project". Unassigned bugs are always fair game. Assigned bugs that don't seem to be getting worked on actively can be fair game, but always check with the bug owner first in that case. Also see the development policy.

Outstanding bugs or feature requests in Rust often have a corresponding test in the test suite that doesn't yet pass. One good way to jump into Rust development is to look for files in the test/run-pass directory containing the string xfail-test. Those tests all correspond to bugs that need to be fixed or features that someone needs to finish.

The source is also littered with hundreds of comments marked with 'FIXME' and 'TODO'. In Rust, FIXME comments come with an issue number; sometimes these refer to issues that may be resolved easily.

For inspiration, read about how cmr started hacking the compiler. If in doubt, ask on IRC. Somebody will surely have a task that needs doing.