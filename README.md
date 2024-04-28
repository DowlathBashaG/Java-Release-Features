# Java-Release-Features

Java 9
------

Platform Module System (Project Jigsaw)

Interface Private Methods

Try-With Resources

Anonymous Classes

@SafeVarargs Annotation

Collection Factory Methods

Process API Improvement

New Version-String Scheme

JShell: The Java Shell (REPL)

Process API Improvement

Control Panel

Stream API Improvement

Java 10
-------

Local Variable Type Inference

Time-Based Release Versioning

Garbage-Collector Interface (G1)

Parallel Full GC for G1

Heap Allocation on Alternative Memory Devices

Consolidate the JDK Forest into a Single Repository

Application Class-Data Sharing

Additional Unicode Language-Tag Extensions

Root Certificates

Experimental Java-Based JIT Compiler

Thread-Local Handshakes

Remove the Native-Header Generation Tool

Java 11
-------

Top Java 11 Features You Must Know

1. New HTTP (and WebSocket) Client

2. Nested classes attributes’ visibility management

3. Epsilon: A No-Op Garbage Collector 

4. New Characters, Scripts, and Blocks

5. Java Flight Recorder

6. APis Improvements

7. Deprecations and Deletions

8. Other Enhancements 

9. Long-Term Support (LTS)

Running Java files directly: Enhancements to java launcher allowing direct execution of single-file Java source code without explicit compilation.

Improved var handling: Improved type inference for lambda expressions using var.

HTTP Client API: The introduction of a standard HTTP Client API supporting HTTP/1.1, HTTP/2, and WebSocket communication.

String Functions: New utility methods added to the String class, such as repeat(), isBlank(), strip(), lines().

New Epsilon Garbage Collector: A no-op garbage collector to test the performance of applications.

Java Flight Recorder (JFR) Event Streaming: The JFR now supports event streaming, providing more capabilities for monitoring and profiling Java applications.

Eliminating Nashorn JavaScript Engine: The removal of the Nashorn JavaScript engine and associated API, making it unavailable for further use.

TLS 1.3 Support: The implementation of TLS 1.3, improves the transport security of Java applications.


Java 12 
-------

 JDK Enhancement Proposal (or JEP) 

JEP 325 : Switch Expressions

JEP 189: Shenandoah: A Low-Pause-Time Garbage Collector (Experimental)

JEP 230: Microbenchmark Suite

JEP 334: JVM Constants API

JEP 340: One AArch64 Port, Not Two

JEP 341: Default CDS Archives

JEP 344: Abortable Mixed Collections for G1

JEP 346: Promptly Return Unused Committed Memory from G1

Java 13
-------

Text Blocks - JEP 355

New Methods in String Class for Text Blocks

Switch Expressions Enhancements - JEP 354

Reimplement the Legacy Socket API - JEP 353

Dynamic CDS Archive - JEP 350

ZGC: Uncommit Unused Memory - JEP 351

newFileSystem() Method

DOM and SAX Factories with Namespace Support

Java 14
-------

Switch Expressions (Standard) - JEP 361

Pattern Matching for instanceof (Preview) - JEP 305

Helpful NullPointerExceptions - JEP 358

Records (Preview) - JEP 359

Text Blocks (Second Preview) - JEP 368

Packaging Tool (Incubator) - JEP 343

NUMA-Aware Memory Allocation for G1 - JEP 345

JFR Event Streaming - JEP 349

Non-Volatile Mapped Byte Buffers - JEP 352

ZGC on macOS - JEP 364

ZGC on Windows - JEP 365

Foreign-Memory Access API (Incubator) - JEP 370

Java 15
-------

 JDK Enhancement Proposal (or JEP) 

JEP 378: Text Blocks (Standard)

JEP 371: Hidden Classes -

JEP 360: Sealed Classes (Preview) -

JEP 375: Pattern Matching, for instance of (Second Preview)

JEP 384: Records (Second Preview)

JEP 372: Disable the Nashorn JavaScript Engine

JEP 373: Reimplement the Legacy DatagramSocket API

JEP 374: Disable and Deprecate Biased Locking

JEP 379: A Low-Pause-Time Garbage Collector: Shenandoah

JEP 383: Foreign-Memory Access API (Second Incubator) -

JEP 381: Remove the Solaris and SPARC Ports

JEP 385: Deprecate RMI Activation for Removal

Java 16
-------

 JDK Enhancement Proposal (or JEP) 
 
1. JEP 338: Vector API (Incubator)

2. JEP 347: Enable C++14 Language Features

3. JEP 357: Migrate from Mercurial to Git

4. JEP 369: Migrate to GitHub

5. JEP 376: ZGC: Concurrent Thread-Stack Processing

6. JEP 380: Unix-Domain Socket Channels

7. JEP 386: Alpine Linux Port

8. JEP 387: Elastic Metaspace

9. JEP 388: Windows/AArch64 Port

10. JEP 389: Foreign Linker API (Incubator)

11. JEP 390: Warnings for Value-Based Classes

12. JEP 392: Packaging Tool

13. JEP 393: Foreign-Memory Access API (Third Incubator)

14. JEP 394: Pattern Matching for instanceof

15. JEP 395: Records

16. JEP 396: Strongly Encapsulate JDK Internals by Default

17. JEP 397: Sealed Classes (Second Preview)


Java 17
-------

1. JEP 306: Restore Always-Strict Floating-Point Semantics

2. JEP 356: Enhanced Pseudo-Random Number Generators

3. JEP 382: New macOS Rendering Pipeline

4. JEP 391: macOS/AArch64 Port

5. JEP 398: Deprecate the Applet API for Removal

6. JEP 403: Strongly Encapsulate JDK Internals

7. JEP 406: Pattern Matching for switch (Preview)

7.1 if…else chain

7.2 Pattern matching and null

7.3 Refining patterns in switch

8. JEP 407: Remove RMI Activation

9. JEP 409: Sealed Classes

10. JEP 410: Remove the Experimental AOT and JIT Compiler

11. JEP 411: Deprecate the Security Manager for Removal

12. JEP 412: Foreign Function & Memory API (Incubator)

13. JEP 414: Vector API (Second incubator)

14. JEP 415: Context-Specific Deserialization Filters


Java 18
-------

1. JEP 400: UTF-8 by Default

2. JEP 408: Simple Web Server

3. JEP 413: Code Snippets in Java API Documentation

4. JEP 416: Reimplement Core Reflection with Method Handles

5. JEP 417: Vector API (Third Incubator)

6. JEP 418: Internet-Address Resolution SPI

7. JEP 419: Foreign Function & Memory API (Second Incubator)

8. JEP 420: Pattern Matching for switch (Second Preview)

8.1. Dominance checking of the same type.

8.2 Exhaustiveness of switch expressions and statements

9. JEP 421: Deprecate Finalization for Removal


Java 19
-------

1. JEP 405: Record Patterns (Preview)

1.1 Normal Record Patterns Example

1.2 Record Nested Patterns Example

2. JEP 422: Linux/RISC-V Port

3. JEP 424: Foreign Function & Memory API (Preview)

4. JEP 425: Virtual Threads (Preview)

5. JEP 426: Vector API (Fourth Incubator)

6. JEP 427: Pattern Matching for switch (Third Preview)

7. JEP 428: Structured Concurrency (Incubator)

Java 20
-------

Virtual Threads as Preview Feature

Vector API Proposal

Structured Concurrency

Scoped Values

Foreign Function and Memory API

Record Patterns

Pattern Matching for Switch Statements and Expressions


Java 21
------

String Templates

Sequenced Collections

Pattern Matching for switch and Record Patterns

Virtual Threads

Java 22
-------

Unnamed Variables & Patterns (JEP 456)

Example#1: Enhanced For Loop

Example#2: Try-Catch Block

Example#3: Lambda Parameters

Example#4: Unnamed Patterns in a Switch Expression

Launch Multi-File Source-Code Programs (JEP 458)

Statements Before super(…) or this(…) [Preview, JEP 447]

Stream Gatherers (Preview, JEP 461)

What is a Stream Gatherer?

Why we need Stream Gatherer?

What are the benefits of Stream Gatherers?

Foreign Function & Memory API (JEP 454)

Class-File API (Preview, JEP 457)


