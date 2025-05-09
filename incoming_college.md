# Incoming College Students

You just got into your dream school...or maybe you didn't? 

Ok, you want to make the most out of college. And even if you're not going to where you want to go, what can you do about your situation?

## Get a good GPA

For many people, going to college is a means of gaining skills to get a job.
As I did a technical major (ECE/CS), my advice here is most pertinent for people looking for a job with hard skills.
With that in mind, the **most** important thing to focus on in college is to have a good GPA.
I already know what people are going to say, 

> but that means you didn't take enough risk

or 

> companies don't care about GPA

So in a world where we have so much data and so little time, as one of thousands of applicants to a company, what do you think they are going to do? It is unfortunate, but usually:

* Filter by school, grade, major
* Filter by GPA
* (the rest)

So sure, maybe it isn't a predictive factor of success, but it is going to be used; it's the table stakes.

And as med school people know, GPA is important for admissions to get into med school.
As people pursuing higher ed know, GPA is also important for Master's and PhD admissions.

And guess what, because people believe that GPA doesn't matter, usually when they find out it _does_, it is already too late.
So you can have a good GPA, you are setting yourself up for success at least.

### How to still take classes you like

So the corollary is, you can't just coast through easy classes, not learn anything, and come out with a 4.0 GPA that people care about. 
It has to be a GPA that also comes with tangible value. So, as the age-old secret-not-so-secret goes, you will still have to work hard.

There is no simple formula here, take classes that challenge you, but you still will be able to work to get a good grade in.

## Choosing courses

### CS

If you are a CS major, besides algorithms and data structures, I do not consider someone a serious computer scientist unless they have also taken

* Introduction to Computer Systems: Learn this before OS
  * [Bryant's Textbook](https://csapp.cs.cmu.edu/): This is the classic textbook for computer systems. 
* Operating Systems (not some baby OS class, look up the CMU one where you build an entire one from scratch)
  * A cool part about OS is you find out at lower level implementations, you have the freedom to pretty much design anything, anyway you want it  
* Compilers (ideally one where you have to create a useful language from scratch)
  * [Crafting Interpreters](https://craftinginterpreters.com/): A hands-on amazingly written book where you get to write a compiler alongside the author
  * [Dragon Textbook](https://en.wikipedia.org/wiki/Compilers:_Principles,_Techniques,_and_Tools): The classic compilers textbook
* Databases
* Distributed Systems (teaches you about how many real-world systems work)
  * [Tannenbaum's book](https://www.distributed-systems.net/index.php/books/ds4/): Free and also very well-written

And yes, these are usually hard classes, but that's the point. There is also a sort of "divide" in CS between the theorists vs the practical people. 

* Theory: Algorithms, probability theory, programming languages, compilers, functional programming
* Practical: Systems, OS, Distributed

Some essential skills

* Race conditions: You have no idea how much code exists in real life that 
* Code safety: Null pointers, code that leaks memory or accesses memory in weird spots
* Scalability: Can your code work with large inputs?
* Maintainability of code: How do you make your code modular, reusable, readable in large code bases?
* Debugging code: print debugging, using gdb, breakpoints, writing panic functions

Some essential skills you may not learn in class

* Creating a website. These days people use React and Vue, but that may change soon
* Setting up a "backend" that can take API requests 
* Setting up a database, no-sql or sql
* Training a real ML model (not just recognizing handwritten digits)
* Prompt engineering with LLMs, embeddings + building vector DB
* Cryptography. Yea sure crypto, but what I really mean is symmetric/asymmetric encryption, e.g. RSA, AES. Common attacks like DDOS, packet spoofing. Also basic "hacking" like reading through client code of websites (you'll be surprised how bad companies are at this), finding API keys, abusing endpoints that are not auth protected. There's a big rabbit hole you can go down in like professional capture the flag and computer forensics
* Code style, documentation
* Version control, e.g. `git`: Easiest way to learn this is to force yourself to use it for classes. It will help you become a better coder

Nice to haves

* Stable diffusion for image generation 

#### Classes I thought were overrated

* Parallel computing: you learn about multithreading, more race conditions, and some GPU programming. But I felt like the skills here were not very applicable unless you wrote parallel code all day in your job (even then, you are usually focusing on correctness vs some crazy performance)

### ECE

If you an ECE major, the category is a lot more broad, because you can focus more on anywhere of the hardware stack. 
But broadly

* Analog: op amps, transistors, IC design, layout, fab
* Digital: digital logic, FPGA programming, verification
* Computer Architecture: RISC-V pipeline, instruction sets
* Embedded: coding on bare metal
  * You can buy a [Raspberry Pi](https://www.raspberrypi.com/), and then buy some random embedded devices and see if you can make them work

Once you go above embedded you are entering OS land. Welcome to the CS major stack.

Some essential skills you should have

* How to read a data sheet, and figure out how to use random electronic devices
* How to debug a circuit
* How to use a Raspberry Pi and Arduino
* How to use a transistor in a circuit

Nice to haves

* Know how to wire a house
* Basic computer repairs, such as replacing a laptop battery, adding more RAM to your computer (not downloading)
