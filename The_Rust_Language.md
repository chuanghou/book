# The Rust Programming Language
by Steve Klabnik and Carol Nichols, with contributions from the Rust Community

This version of the text assumes you’re using Rust 1.67.1 (released 2023-02-09) or later. See the “Installation” section of Chapter 1 to install or update Rust.

The HTML format is available online at https://doc.rust-lang.org/stable/book/ and offline with installations of Rust made with rustup; run rustup docs --book to open.

Several community translations are also available.

This text is available in paperback and ebook format from No Starch Press.

🚨 Want a more interactive learning experience? Try out a different version of the Rust Book, featuring: quizzes, highlighting, visualizations, and more: https://rust-book.cs.brown.edu

## Foreword
It wasn’t always so clear, but the Rust programming language is fundamentally about empowerment: no matter what kind of code you are writing now, Rust empowers you to reach farther, to program with confidence in a wider variety of domains than you did before.

> Rust 本质是一种关于赋能（这个赋能是中文社区的翻译，感觉这个词给带歪了）的语言。无论你在写什么类型的程序。Rust能让你在更为广泛的领域走的更远，写的更自信

Take, for example, “systems-level” work that deals with low-level details of memory management, data representation, and concurrency. Traditionally, this realm of programming is seen as **arcane**, accessible only to a select few who have devoted the necessary years learning to avoid its infamous pitfalls. And even those who practice it do so with caution, lest their code be open to **exploits**, crashes, or corruption.

> 举例来说，系统编程（主要是一些涉及底层内存细节，数据表示，并发）通常来说被视为是高深莫测的领域，只有一些浸淫多年的熟手才能在开发过程中躲避那些臭名昭嘴的漏洞。即使是一些很谨慎的实践者也唯恐代码的漏洞崩溃之类的问题。

Rust breaks down these barriers by eliminating the old pitfalls and providing a friendly, polished set of tools to help you along the way. Programmers who need to “dip down” into lower-level control can do so with Rust, without taking on the customary risk of crashes or security holes, and without having to learn the fine points of a fickle toolchain. Better yet, the language is designed to guide you naturally towards reliable code that is efficient in terms of speed and memory usage.

Programmers who are already working with low-level code can use Rust to raise their ambitions. For example, introducing parallelism in Rust is a relatively low-risk operation: the compiler will catch the classical mistakes for you. And you can tackle more aggressive optimizations in your code with the confidence that you won’t accidentally introduce crashes or vulnerabilities.

But Rust isn’t limited to low-level systems programming. It’s expressive and ergonomic enough to make CLI apps, web servers, and many other kinds of code quite pleasant to write — you’ll find simple examples of both later in the book. Working with Rust allows you to build skills that transfer from one domain to another; you can learn Rust by writing a web app, then apply those same skills to target your Raspberry Pi.

This book fully embraces the potential of Rust to empower its users. It’s a friendly and approachable text intended to help you level up not just your knowledge of Rust, but also your reach and confidence as a programmer in general. So dive in, get ready to learn—and welcome to the Rust community!

— Nicholas Matsakis and Aaron Turon