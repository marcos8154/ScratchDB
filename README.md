# ScratchDB
A simple database system maded from scratch

This is a project where we propose to develop a simple database system, according to traditional concepts and study articles found on the internet.

To your surprise: this project is not written in C or C++, but C#!

The objective, in addition to learning about the functioning of low-level data systems, is to accumulate knowledge about algorithms, programming logic and fast I/O in files by brushing bits and bytes.

(considerations) There is no intention here of creating software that surpasses traditional/commercial databases.
And even though this project becomes highly functional in the future, you MUST NOT use it in a production environment or coupled with real commercial software. Use this for study and fun only!

## Tools used

It was developed on Windows OS using the Visual Studio IDE.
If you are from another language or stack (like Java, CPP, Rust etc), abstract the concepts and re-do the code in your language. The important thing is to absorb the theory.
Use Chat-GPT to provide you with the equivalent code in your language.

## Roadmap
1 - file control layer: we will create a file from an array of bytes; Define header regions and data pages; <br>
2 - layout for defining table schemas and data types (located in the header); <br>
3 - data insertion routine; <br>
4 - data obtaining routine (rustic method, not yet the definitive "select" routine); <br>
5 - data update routine; <br>
6 - data deletion routine; <br>
7 - data select routine; <br>
8 - simple SQL command interpreter <br>
9 - a program for managing the database <br>

So far we already have a lot of work to do;
When we complete this, we will expand to more features:
- Network (multi-users)
- Transactions
- Backup-Restore
