# Rust Programming Base Template for new Rust Application code

[YouTube Video](https://www.youtube.com/watch?v=oxx7MmN4Ib0&list=PL7r-PXl6ZPcCIOFaL7nVHXZvBmHNhrh_Q)

https://github.com/0atman/noboilerplate/blob/main/scripts/37-functional-rust.md

Replace "my-app" Project wide with the new Project name and also rename the corresponding Folder.

## Adding a lib

1. Run `cargo new --lib <lib_name>`
2. Add it as a dependency for your Workspace `<lib_name> = { path = "<lib_name>" }`
3. Include it like any other Workspace dependency
