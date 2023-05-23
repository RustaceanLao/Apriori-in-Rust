# Apriori-in-Rust
A simple Rust Implementation of Apriori Algorithm for finding Frequent sets and Association Rules

- minimal support and minimal confidence are set in main.rc 
  - larger the minimal support, less the frequent sets and association rules
  - larger the minimal confidence, frequent sets the same, less association rules
- all functions are stored in lib.rc
- Running 'cargo run' directly to get results
- the results will be written in file: associationRule_minSupprot_minConfidence.txt
- Running 'cargo doc --open' for documentation creation and view documentation for implementation details
