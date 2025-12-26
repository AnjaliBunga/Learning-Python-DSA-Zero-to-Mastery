# Learning Python & DSA — Zero to Mastery

This repository is a structured learning path for Python programming and data structures & algorithms (DSA). It is designed to guide you from fundamentals to advanced topics with practical, real-world mini-projects and clear GitHub practice requirements for each topic.

How to use this repository
- Follow the topics in order (1 → 40) or jump to sections you want to practice.
- For each topic, add a small project or script folder (e.g., `01_python_setup/`) containing the requested code and a short README that explains what you built and what you learned.
- Use the "GitHub Practice Requirement" field for what to implement and what to describe in that folder's README.

Repository structure suggestions
- /01_python_setup
- /02_syntax_indentation
- /03_variables_data_types
- ...
- README.md (this file)

Learning path

Fundamentals

1. Python Setup & Execution
- Subtopics: Install Python, REPL, .py files, IDE vs terminal, PATH
- Practice: Local script runner — create scripts and run them from terminal
- Common mistakes: Only using the IDE; not understanding how Python is executed
- Importance: Must-know
- GitHub practice: Add runnable example scripts and a README explaining how Python runs code and how to run your scripts

2. Syntax & Indentation
- Subtopics: Indentation rules, comments, keywords
- Practice: Fix broken scripts with indentation and syntax errors
- Common mistakes: Ignoring indentation (mixing spaces/tabs)
- Importance: Must-know
- GitHub practice: Provide before/after broken scripts and README summarizing syntax rules

3. Variables & Data Types
- Subtopics: int, float, bool, str, None
- Practice: CLI calculator handling different types
- Common mistakes: Type confusion and implicit conversions
- Importance: Must-know
- GitHub practice: Calculator code and README explaining types & usage

4. Operators
- Subtopics: arithmetic, comparison, logical, precedence
- Practice: Finance calculator that computes balances and interest
- Common mistakes: Operator precedence misunderstandings
- Importance: Must-know
- GitHub practice: Calculation examples and README about operator precedence

5. Input & Output
- Subtopics: input(), print(), f-strings
- Practice: CLI form processor that validates and prints structured output
- Common mistakes: String concatenation pitfalls, not validating input
- Importance: Must-know
- GitHub practice: CLI app and README describing I/O handling

6. Control Flow
- Subtopics: if, elif, else
- Practice: Eligibility checker (age, criteria) with clear branching
- Common mistakes: Deep nesting and duplicated logic
- Importance: Must-know
- GitHub practice: Checker program and README explaining decision logic

7. Loops
- Subtopics: for, while, break, continue
- Practice: Log analyzer that scans files and collects stats
- Common mistakes: Infinite loops and off-by-one errors
- Importance: Must-know
- GitHub practice: Analyzer and README explaining loop choices

8. Strings
- Subtopics: slicing, methods, immutability
- Practice: Password validator that enforces rules and patterns
- Common mistakes: Manual parsing instead of using string methods/regex
- Importance: Must-know
- GitHub practice: Validator code and README on string operations

9. Lists
- Subtopics: indexing, slicing, methods
- Practice: Task manager storing and modifying tasks
- Common mistakes: Modifying a list while iterating over it
- Importance: Must-know
- GitHub practice: Task app and README describing list usage patterns

10. Tuples & Sets
- Subtopics: tuple immutability, set uniqueness
- Practice: Data deduplicator that removes duplicates from datasets
- Common mistakes: Expecting sets to preserve order
- Importance: Useful
- GitHub practice: Cleaner script and README comparing tuple vs set

11. Dictionaries
- Subtopics: key-value mapping, iteration, methods
- Practice: Config loader that reads key-value pairs and provides defaults
- Common mistakes: KeyErrors from missing keys
- Importance: Must-know
- GitHub practice: Config app and README on dict design and pitfalls

12. Functions
- Subtopics: def, parameters, return, scope
- Practice: Utility library with reusable helper functions
- Common mistakes: God functions (too large) and not using modularity
- Importance: Must-know
- GitHub practice: Utils module and README describing function design and examples

Intermediate

13. Modules & Imports
- Subtopics: import styles, __name__ == '__main__'
- Practice: Modularize a project into packages and modules
- Common mistakes: Circular imports and unclear package structure
- Importance: Must-know
- GitHub practice: Modular app and README describing project structure and import patterns

14. File Handling
- Subtopics: read/write, text, CSV, JSON
- Practice: File-based report generator that reads inputs and writes reports
- Common mistakes: Not closing files or improper encoding handling
- Importance: Must-know
- GitHub practice: Reports code and README on file operations and formats

15. Exception Handling
- Subtopics: try/except, raising custom errors
- Practice: Robust parser that handles malformed inputs gracefully
- Common mistakes: Catching all exceptions blindly
- Importance: Must-know
- GitHub practice: Parser with tests and README explaining error strategy

16. Comprehensions
- Subtopics: list, dict, set comprehensions
- Practice: Data transformer that converts raw data into structured form
- Common mistakes: Overusing comprehensions and hurting readability
- Importance: Must-know
- GitHub practice: Transformer code and README explaining comprehension logic

17. Generators & Iterators
- Subtopics: yield, iter, next
- Practice: Stream processor that handles large datasets lazily
- Common mistakes: Loading entire datasets into memory
- Importance: Must-know
- GitHub practice: Stream app and README showing lazy evaluation benefits

18. Lambda & Built-ins
- Subtopics: lambda, map, filter, zip
- Practice: Data cleaner using functional tools for pipelines
- Common mistakes: Overusing lambdas making code unreadable
- Importance: Useful
- GitHub practice: Cleaner utility and README on functional tools

Advanced

19. Debugging & Logging
- Subtopics: traceback, logging levels, structured logs
- Practice: Debug a failing app and produce useful logs
- Common mistakes: Relying only on print statements
- Importance: Must-know
- GitHub practice: Logger integration and README describing debug flow

20. Type Hinting
- Subtopics: typing module, annotations, mypy basics
- Practice: Typed utilities with static checks
- Common mistakes: Ignoring types or using them inconsistently
- Importance: Must-know
- GitHub practice: Typed code and README about type hints and checks

21. Testing Basics
- Subtopics: unittest, pytest, assertions
- Practice: Write tests for existing code to ensure correctness
- Common mistakes: No tests or fragile tests
- Importance: Must-know
- GitHub practice: Tests folder and README summarizing test coverage and how to run tests

Object-Oriented Programming (OOP)

22. Classes & Objects
- Subtopics: class, object, __init__
- Practice: Inventory system with item classes and persistence
- Common mistakes: Applying Java-style patterns incorrectly in Python
- Importance: Must-know
- GitHub practice: OOP app and README on class design

23. Encapsulation
- Subtopics: private variables (convention), properties
- Practice: User profile model with validation and encapsulation
- Common mistakes: Exposing internals directly
- Importance: Must-know
- GitHub practice: Model code and README on encapsulation

24. Inheritance
- Subtopics: super(), method override
- Practice: Role system demonstrating base and derived behavior
- Common mistakes: Deep inheritance hierarchies
- Importance: Useful
- GitHub practice: Roles code and README about inheritance tradeoffs

25. Polymorphism
- Subtopics: duck typing, informal interfaces
- Practice: Payment processor supporting multiple gateways with same interface
- Common mistakes: Rigid type checks instead of duck typing
- Importance: Useful
- GitHub practice: Processor code and README on polymorphism

26. Magic Methods
- Subtopics: __str__, __len__, __eq__ and other dunder methods
- Practice: Custom data type implementing common dunder methods
- Common mistakes: Ignoring dunder methods that make objects ergonomic
- Importance: Useful
- GitHub practice: Custom class and README explaining dunder usage

27. Composition
- Subtopics: has-a relationship vs is-a
- Practice: Plugin system or composed services
- Common mistakes: Overusing inheritance where composition is better
- Importance: Must-know
- GitHub practice: Plugin system and README on composition patterns

Data Structures & Algorithms (DSA)

28. Arrays (Lists)
- Subtopics: indexing, traversal, complexity analysis
- Practice: Data analyzer that processes and summarizes arrays
- Common mistakes: Ignoring time complexity of operations
- Importance: Must-know
- GitHub practice: Array operations and README with complexity notes

29. Strings (DSA view)
- Subtopics: pattern matching, frequency analysis
- Practice: Text analyzer for finding common patterns and frequency
- Common mistakes: Repeated scans instead of efficient algorithms
- Importance: Must-know
- GitHub practice: Analyzer and README showing algorithm choices

30. Recursion
- Subtopics: base case, call stack, recursion depth
- Practice: File system traversal or tree-based problem using recursion
- Common mistakes: Missing base case or deep recursion without tail optimization
- Importance: Must-know
- GitHub practice: Traversal code and README explaining recursion flow

31. Linked Lists
- Subtopics: singly linked list, traversal, insertion
- Practice: History manager that stores changes using a linked list
- Common mistakes: Pointer/reference confusion
- Importance: Must-know
- GitHub practice: Linked list implementation and README describing structure

32. Stacks
- Subtopics: LIFO, push/pop
- Practice: Undo system for an editor or app
- Common mistakes: Using Python lists naively without understanding performance
- Importance: Must-know
- GitHub practice: Stack impl and README explaining use-cases

33. Queues
- Subtopics: FIFO, collections.deque
- Practice: Task scheduler using a queue for job dispatch
- Common mistakes: Inefficient pops from front of a list
- Importance: Must-know
- GitHub practice: Queue impl and README about performance

34. Hashing
- Subtopics: hash maps, handling collisions
- Practice: Simple cache system with hashing basics
- Common mistakes: Poor key choices leading to collisions
- Importance: Must-know
- GitHub practice: Cache code and README explaining hashing tradeoffs

35. Searching
- Subtopics: linear search, binary search and their complexities
- Practice: Lookup tool that supports both naive and binary searches
- Common mistakes: Misusing binary search on unsorted data
- Importance: Must-know
- GitHub practice: Search algorithms and README analyzing complexity

36. Sorting
- Subtopics: bubble, merge, quick; stability and tradeoffs
- Practice: Ranking system that sorts items by metrics and explains tradeoffs
- Common mistakes: Reinventing built-in sort without understanding costs
- Importance: Must-know
- GitHub practice: Sorting implementations and README detailing tradeoffs

37. Trees (Basics)
- Subtopics: binary tree, traversal (inorder, preorder, postorder)
- Practice: Folder structure model that mirrors filesystem hierarchies
- Common mistakes: Confusing trees and graphs
- Importance: Useful
- GitHub practice: Tree code and README on traversal techniques

38. Graphs (Basics)
- Subtopics: adjacency list, BFS, DFS
- Practice: Dependency resolver that detects cycles and orders tasks
- Common mistakes: Ignoring cycles and wrong traversal choices
- Importance: Useful
- GitHub practice: Graph tools and README explaining traversal and cycle detection

39. Complexity Analysis
- Subtopics: Big-O, time vs space tradeoffs
- Practice: Analyze past solutions and annotate their complexity
- Common mistakes: Guessing complexity without measurement
- Importance: Must-know
- GitHub practice: Annotated code and README with complexity analysis

40. Problem Solving Patterns
- Subtopics: two pointers, sliding window, hashing patterns
- Practice: Solve 10 real interview-style problems using the patterns
- Common mistakes: Random brute-force solutions instead of pattern identification
- Importance: Must-know
- GitHub practice: Solutions folder with problem explanations and README mapping patterns to solutions

Contributing & GitHub practice
- For each topic create a folder named with a two-digit prefix and a short slug (e.g., `01-python-setup`).
- Inside each folder include:
	- code/ : runnable code or module
	- README.md : short explanation of what you built, why, and what to run
	- tests/ (optional but recommended): small tests demonstrating correctness
- Commit messages: keep them clear and reference the topic number (e.g., "Add CLI calculator for 03-variables").

Next steps (recommended)
- Start by adding the first 5 topics with simple code and READMEs.
- Add basic tests for the functions you implement.
- Open a PR with small changes and request feedback.

License
- Add a license file if you plan to publish this repo publicly (MIT is a common choice).

Enjoy learning — work consistently and build the projects to reinforce each concept.
