
### Upcoming (in order):
- [x] Code optimization so it doesn't take 1 second per row.
- [x] Proper Date Handling.
- [ ] Putting the Proper Date Handling to good use.
- [ ] Unifying the Organizer script and the Exporting script, so that stuff makes more sense and you only need to press two buttons rather than 6.
- [ ] More automation:
  - [ ] Getting assignments from G-Classroom and putting them into the sheet.
  - [ ] Adding and removing deadlines as reminders in the calendar.
  - [ ] Adding meetings as events in the calendar.

### Versions: (new to old)

0.7.x Dates!
- 0.7.0 Dates now work! And quite a few changes to make that happen, and for no issues with the Exporter to occur.
----
0.6.x Big Optimizations.
- 0.6.3 more optimizations sprinkled around, and began work on compatibility with the Exporter.
- 0.6.1 Made the clasic ss constant, and a few other small in-code modifications and optimizations. <br>
Now the program is twice as fast and worth the effort of opening the app script. <br>
Also, the test.txt file will no longer be updated into github, as it has no real use here.
- 0.6.0 Optimized the format get/set and added proper defaults that auto-assign the status.
----
0.5.x Small optimizations.
- 0.5.3 Changed setHomeworkFormat to setRowFormat, and made the optimization variables into global const, as they should be.
- 0.5.2 Now the setHomeworkFormat does NOT call "getCellFormat" every time it's used.
- 0.5.1 Backup of a working v2 of the setHomeworkFormat function.
- 0.5.0 Modified dataFrom (Cell, Row, and Column) functions so they're less messy. This seems to also slightly speed them up, but I'm not certain of this.
----
0.4.0 ALPHA IS ON!
- Now it modifies TP without any hiccups!
- It also uses variables instead of calling entire functions multiple times to get the same number. 
----
0.3.x Sheet format not as shitty.
- 0.3.1 Decided to change the columns into automatic-ish variables, so I don't have to bother remembering what 10, 9, 5, 7, etc stand for. Also finished experimenting with dates.
- 0.3.0 Began experimenting with date and decided to leave it for later.
----
0.2.x Modifies exams!
- 0.2.2: Step 3: after having the way to get and set format, I made the function that checks the status and changes format accordingly.
- 0.2.1: Step 2 of the previous; I found different methods to record its format, but no single-functions that does so. I created them myself.
- 0.2.0: I found the way to set a cell's background, and began experimenting with it.
(bad news, forgot to save the back-up)
----
0.1 Start of the project.
- Focused on creating and learning ways to interact with the sheet, as it was new territory for me, I went for understanding the basic scopes first.
