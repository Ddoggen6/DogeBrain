I find this characteristic of Rust interesting. Imagine that I let someone use my PC. Even if I allow them to modify certain things, that doesn't mean they become the owner of my PC. They have permission to interact with it, but ownership remains mine.

In Rust, it's similar: a variable can access or modify a value without necessarily owning it. The distinction depends on whether we're dealing with ownership, borrowing, or mutability.

- Mutability: Determines whether a binding can be modified.
    
- Ownership: Determines which variable owns a value.
    
- Borrowing: Allows access to a value without transferring ownership.
    

It's curious to me that, despite already knowing Python, C, and SQL, I'm now learning a language that makes these distinctions so explicit. I'm glad the Ddoggen of the past decided to learn C first.... that is making the job of learn this a lot more easier ;_;

[[Mutable and unmutable variables]].