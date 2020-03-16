# Ruby Basics

## What is an “interpreted” language?

A programming language that can't run on your processor directly. It instead needs to be fed into a virtual machine that acts as a middleman. The virtual machine takes in the interpreted language's code on one side and speaks natively to the operating system and processor on the other.

The advantage of this approach is that it allows you to write your code once and execute it on many different operating systems and hardware platforms.

<br>

## What is IRB?

A Read, Evalulate, Print, Loop (REPL). Accepts instruction, executes it, and shows you the result.

<br>

## What are Objects?

Ruby is an Object-Oriented programming language. Every piece of data that we interact with inside the virtual machine is an object.

Objects hold information, called _attributes_. For example, a person object could have attributes such as height, weight, age, gender, hair color, and eye color.

<br>

## What are Methods?

Methods are actions that objects can perform. For example, a person object could have methods such as walk, run, eat, sleep, shower, meditate, wash dishes, and daydream.

<br>

## What are Classes?

Classes are abstract descriptions of a category or type of thing. They define what attributes and methods all objects of that type have.

<br>

## What are Blocks?

Blocks are a way of building up a set of instructions for use elsewhere. They usually start with the keyword _do_ and end with the keyword _end_. This form is always acceptable. For example...

```
5.times do
  puts "Hello, World!"
end
```

When a block contains just a single instruction the alternate markers { and } are often used to begin and end the block. For example...

```
5.times{ puts "Hello, World!" }
```

<br>

## What is an Array?

An array is a zero-based number-indexed list. They can grow and shrink, and there are many useful methods that can be called on them, such as sort, each, split, join, collect, first, last, and shuffle.

<br>

## What is an Iterator?



<br>

## What are hashes?

A hash is an unordered collection where data is organized into key/value pairs. For example...
```
produce = {"apples" => 3, "oranges" => 1, "carrots" => 12}
puts "There are #{produce['oranges']} oranges in the fridge."
```
The _key_ is used as the address and the _value_ is the data at that address. The key/value pairs are linked by the => symbol which is called a _rocket_.

Hashes start with a curly bracket {, have zero or more entries made up of a _key_, a rocket, and a _value_ separated by commas, then end with a closing curly bracket }.

<br>

## What is a library?



<br>

## What is a gem?



<br>
