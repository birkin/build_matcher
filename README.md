### Goals

- process a directory of marc-records, and populate an sqlite database of old-Sierra-bibs, and new-Alma-MMSIDs.
- learn about writing to sqlite.
- experiment with async coding.


### Next

- review previous work, and online info, for how main.rs can call code from other files.
    - resource: <https://doc.rust-lang.org/book/ch07-00-managing-growing-projects-with-packages-crates-and-modules.html>
    - code: the_book chapter 7; restaurant code
- review previous marc work for async flow.
    - check out `marc_experimentation_stuff/code/exp08_async/`
- √ review the state of logging, and implement something.


### Questions

- can't remember why I don't have to 'import' tokio via a `use tokio`.
- can't remember the difference between the `extern crate chrono;` kind of reference/import, and the `use chrono::{DateTime, Local};` kind.

---
