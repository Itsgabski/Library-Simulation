Library Management Simulation

This is a C# console application that simulates a small library system. It uses object-oriented programming concepts such as inheritance, polymorphism, interfaces, operator overloading, and collections.

The program allows members to borrow and return different types of items, including books, comics, and magazines. Each item type has its own rules for calculating fines when overdue.

Main features:

LibraryItem (abstract base class) defines shared properties like ID, title, author, publication date, duration, borrow time, and genre.

Book, Comic, and Magazine classes inherit from LibraryItem and override the IsItemDue method to calculate overdue fines.

Book fine: 7 Gel per day

Comic fine: 5 Gel per day

Magazine fine: 3 Gel per day

Magazine also includes a Frequency property (daily, weekly, monthly) and implements IEquatable to compare magazines by frequency.

The Member class allows users to borrow and return items using overloaded + and - operators.

Members can view borrowed items and check their membership status using an indexer (Active/Inactive).

The Library class manages all library items and provides methods to add, borrow, and return items.

The SortBookByGenre class implements IComparer to sort books by their genre.

Other key points:

Uses ArrayList, List, and Dictionary collections.

Includes try-catch-finally for error handling.

Demonstrates abstraction, inheritance, polymorphism, encapsulation, and interface usage.

When running the program, it:

Creates books, magazines, and comics.

Checks for overdue items and prints fines.

Displays books before and after sorting by genre.

Compares magazine frequencies.

Creates library members, allows them to borrow and return items, and shows membership status.

This simulation demonstrates how a small library system might operate using OOP principles in C#.
