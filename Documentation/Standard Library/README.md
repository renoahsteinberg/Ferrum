# Standard Library

> For Data Structures, I/O Operations, Concurrency, Error Handling and more

1. Core Modules
```
ferrum::prelude // Automatically imported, commonly used trais, types and macros
ferrum::primitive // Definitions for primitive data types
```
2. Collections
```
ferrum::collections // Data Structures
-> Vectors (Vec<T>)
-> HashMaps (HashMap<K, V>)
-> HashSets (HashSet<T>)
-> LinkedLists (LinkedList<T>)
-> BinaryHeaps (BinaryHeap<T>)
```
3. Algorithms
4. Strings
```
ferrum::string // heap allocated data structure
&str // string slices will be immutable
```
5. I/O
```
ferrum::io
-> Streams
-> Buffers
```
6. Concurrency and Parallelism
```
ferrum::thread
ferrum::sync
```
7. Error Handling
```
ferrum::error
ferrum::result // Result<T, E> type for returning and propagating errors
ferrum::option // Option<T> 
```
8. Memory Management
```
ferrum:rc // Reference pointers for shared ownership (Rc<T>)
ferrum::arc // Atomic reference for thread-safe shared ownership (Arc<T>)
ferrum::cell + ferrum::refcell // interior mutability patterns
```
9. Macros
```
ferrum::macros // macros for println!, vec!, etc.. to simplify coding
```
10. Time and Date
```
ferrum::time
```
11. Networking
```
ferrum::net
-> TCP/UDP
-> IP Addresses and Ports
```
12. Utils
```
ferrum::env // Access to environment variables
ferrum::process // Interacting with system processes
ferrum::thread_local // thread-local storage
```
