# [Presentation] Memory Management in Unsafe Rust

These are the slides to a talk I gave to my coworkers at [MaidSafe](maidsafe.net). It was meant to be a broad overview of Rust unsafe code and FFI design, and includes the motivations as well as the background concepts necessary to understand the design of the FFI API I implemented for [parsec](https://github.com/maidsafe/parsec). I wanted it to be grokkable to beginners but still useful to experts -- I hope I succeeded in that rather lofty goal :)

The presentation file is `unsafe-rust.html`. It was generated from the source file `unsafe-rust.org` using Emacs and [`org-reveal`](https://github.com/yjwen/org-reveal).

You can view it on [my blog](https://www.bytedude.com/files/unsafe-rust.html). Note that Netlify doesn't want to serve it as an s5 presentation, so if you care to view it in slide format you'll have to download this repository and view it locally.

I have a brief post about this presentation [here](https://www.bytedude.com/memory-management-in-unsafe-rust/).
