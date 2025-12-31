# lab
Epsilon-NFA Elimination Program
📋 Epsilon-NFA Elimination Program
What it does:
This C program removes epsilon (ε) transitions from a Non-deterministic Finite Automaton (NFA) and produces an equivalent NFA without ε-transitions. This is an essential step in automata theory before converting an NFA to a DFA.
Key Features:

✅ Interactive Input: User-friendly interface for entering states, symbols, and transitions
✅ Epsilon-Closure Calculation: Automatically computes ε-closure for each state using reachability algorithm
✅ Transition Reconstruction: Generates new transitions by eliminating all epsilon paths
✅ Final State Detection: Identifies which states become final after epsilon removal
✅ Clear Output Display: Shows the resulting automaton in standard mathematical notation (δ function)
✅ Modular Design: Organized into 5 separate functions for easy understanding and maintenance
✅ Support for Multiple Transitions: Handles non-deterministic transitions (multiple next states for same input)

Use Cases:
Perfect for computer science students learning automata theory, compiler design courses, or anyone working with regular expressions and finite state machines.
