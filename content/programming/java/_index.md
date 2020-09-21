---
description: "Java is a set of computer software and specifications developed by James Gosling at Sun Microsystems"
title: Java
weight: 1
---

Learning road map for Java

## Basics

### Classes
- Classes
  - final class
  - static class
- Abstract classes
  - Abstract methods
- Interfaces
  - default methods
  - private methods in interface
- Enums
- Inheritance
- `this` and `super`
- Anonymous class
  - Anonymous method

### Access modifiers
- public
- protected
- private
- package private

### Flow control
#### Loops
- For loop
  - For-each loop
  - For each with var
- While loop
- Do-while loop
- `continue` keyword

#### Conditional statements
- if statement
  - else if
  - else
- switch
  - break
  - switch statement with fallthrough
  - default

### Primitive data types
- String
- int, long
- boolean
- double, float
- char, byte
- Boxing and unboxing
  - Autoboxing
  - Experiment with performance cost

### Collections
- Fluent in HashMap and HashSet

## Intermediate
### Classes intermediate
- Order of initialization in inheritance
- Polymorphism
- Generics
  - Subtypes
- Super type token
- Enums
  - Methods in enums
  - Usage of JVM-guaranteed singularity
- Use of sealed classes
- Use of records
- Pattern matching

### Understanding and using Object concepts
- Correct implementation of
  - `hashCode` and `equals`
- Understanding use of `hashCode` and `equals` in maps/sets
  - and `compareTo`

- Use of classes where equality by `equals` doesn't mean equality by `compareTo`
  - eg. `BigDecimal`, find out more classes like BigDecimal yourself

### Collections
- Fluency in HashSet, TreeSet, IdentitySet, LinkedHashSet, EnumSet
- Fluency in HashMap, TreeMap, IdentityMap, LinkedHashMap, EnumMap
  - Use of 3rd party libraries with concept of MultiMap (`Key` -> `Value[]`)

### Flow control
- Fluency in Iterators
#### Loops
- Labeled loop

### Functional concepts
- Stream
- Function
  - BiFunction
- Supplier
- Consumer
  - BiConsumer
- Lambda
- Predicate

### Modules
- requires
  - requires transitive
- exports
  - exports... to
- uses, provides... with
- open, opens, opens... to

### Concurrency
- `violate` keyword
- `synchronized` keyword
- locks
- atomic
- deadlock
- ThreadLocal
- Executor
- Future
  - CompletableFuture
    - `supplyAsync`
    - `thenApply`
    - `allOf`
    - `anyOf`
    - `thenApplyAsync`
    - `handle`
    - `exceptionally`
    - `get`
- Knowledge where to apply ParallelStream

## Expert
### Classes intermediate
- Order of initialization in inheritance
  - with use of static fields
  - with use of inner static blocks

### Collections
- Fluency in Queue [[1]](https://docs.oracle.com/javase/tutorial/collections/implementations/queue.html)
- Fluency in Deque [[1]](https://docs.oracle.com/javase/tutorial/collections/implementations/deque.html)

### Performance
#### Optimization
- JMH
- VisualVM
- garbage collection logs

#### Performance tuning
- Identifying and fixing hot spots
  - Object caching?
  - Efficient use of `Stream` and `InputStream`
- GC-tuning