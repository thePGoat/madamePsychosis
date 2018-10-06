# Madame Psychosis
This is a repo that will track my development over time. **I am an anonymous Rust dev**. You can check out the list of open source [Projects](projects/schedule.md) that I'm working on...reach out at thePGoat <at> protonmail.ch to get involved in my work.
  
[Excerpts From: Rust Types for Solid Safety](https://web.stanford.edu/class/cs140e/notes/lec2/paper.pdf)
> "Ideally, we would like a practical language that gives programmers direct control over memory and aliasing while also offering race and memory safety guarantees".

> Rusty Types maintain several key invariants that lead to memory and race safety. To start, every storage location is guaranteed to have either: (a) 1 mutable reference and 0 immutable references to it, or (b) 0 mutable references and n immutable references to it. This invariant directly prevents races as it prohibits concurrent writers and readers to a single memory location. By itself, however, this invariant is not enough to guarantee memory safety, especially in the presence of moveable objects. For instance, since a given variable becomes unusable after its object has been moved, the storage locations associated with that variable may be reused or freed. As a result, any references to that variable will be dangling and invalid after a move. To prevent this, Rusty Types also ensure that each object has a unique binding, the owner, and that references to an object or its contents are created transitively through its owner. The type system guarantees that an object’s owner does not change (the result of a move) while references areoutstanding. Conversely, the type system allows change ofownership when there are no outstanding references.Together, these invariants ensure that no references areleft dangling or pointing to invalid memory.

Why Rust? Here's a few reasons: <br>
* [fireflowers](https://brson.github.io/fireflowers/)
* [Why Rust?](https://medium.com/paritytech/why-rust-846fd3320d3f)


