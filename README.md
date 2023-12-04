# MinigrepInRust
Playing around with Rust and blazing through the official Rust Book. 
This repo holds the work package 12 - An I/O Project: Building a Command Line Program, where we build a simple grep program to search for a key word in a file.

## Example

An example of this simple code with an environment variable (```IGNORE_CASE=1```) looks like this:

```console
IGNORE_CASE=1 cargo run -- to poem.txt
Finished dev [unoptimized + debuginfo] target(s) in 0.02s
Running `target/debug/minigrep to poem.txt`
Searching for to in file poem.txt
Are you nobody, too?
How dreary to be somebody!
To tell your name the livelong day
To an admiring bog!
```