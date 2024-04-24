# Exercise: Note Taking Tool with Polymorphism and OOP Concepts

Create a Java program that simulates a note-taking tool with different types of notes: text notes, checklist notes, and date notes. Utilize polymorphism to handle different types of notes using a common interface or superclass.

1. Define a superclass or interface called Note with common properties and methods that all types of notes share. This could include properties such as title, content, and methods such as displayNoteDetails().

2. Implement subclasses or classes that implement the Note interface for different types of notes:
- TextNote: Represents a note with text content.
- ChecklistNote: Represents a note with a checklist of items.
- DateNote: Represents a note with a specific date attached to it.

3. Each subclass should have its own unique properties and methods, along with overriding or implementing methods inherited from the Note superclass or interface.

4. Implement methods to add, view, edit, and delete notes within the main program. Encapsulate note management functionality within a separate class, such as NoteManager.

5. Use object-oriented principles such as encapsulation, inheritance, and polymorphism to structure the program effectively.

6. Demonstrate polymorphism by storing different types of notes in a single collection (e.g., ArrayList) and iterating through them to display their details.

7. Implement exception handling to handle potential errors, such as invalid input or file I/O errors when saving or loading notes.
