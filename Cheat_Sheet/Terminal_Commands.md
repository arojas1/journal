## Terminal Commands

**[whoami](#whoami)**\
**[pwd](#pwd)**\
**[ls](#ls)**\
**[cd Downloads](#cd-downloads)**\
**[cd ..](#cd-)**\
**[cd ../..](#cd--1)**\
**[cd ~](#cd--2)**\
**[touch foo.txt](#touch-footxt)**\
**[echo hello](#echo-hello)**\
**[mkdir Projects](#mkdir-projects)**\
**[rm file.txt](#rm-filetxt)**\
**[mv bar.txt ~/Desktop](#mv-bartxt-desktop)**\
**[mv bar.txt ../Desktop](#mv-bartxt-desktop-1)**\
**[echo "My Cheat Sheet" > cheat_sheet.md](#echo-my-cheat-sheet--cheat_sheetmd)**\
**[cat cheat_sheet.md](#cat-cheat_sheetmd)**\
**[code cheat_sheet.md](#code-cheat_sheetmd)**\
**[cat cheat-sheet.md | sort](#cat-cheat-sheetmd--sort)**\
**[cat cheat-sheet.md | sort > sorted-cheat-sheet.md](#cat-cheat-sheetmd--sort--sorted-cheat-sheetmd)**\
**[less nypl_items.csv](#less-nypl_itemscsv)**\
**[head nypl_items.csv](#head-nypl_itemscsv)**\
**[tail nypl_items.csv](#tail-nypl_itemscsv)**\
**[cat nypl_items.csv | wc -l](#cat-nypl_itemscsv--wc--l)**\
**[cat nypl_items.csv | uniq | wc -l](#cat-nypl_itemscsv--uniq--wc--l)**\
**[cat nypl_items.csv | uniq -d](#cat-nypl_itemscsv--uniq--d)**\
**[cat nypl_items.csv | uniq > nypl_no_dupes.csv](#cat-nypl_itemscsv--uniq--nypl_no_dupescsv)**\
**[cat nypl_items.csv | grep -i "paris"](#cat-nypl_itemscsv--grep--i-paris)**\
**[cat nypl_items.csv | grep -i "paris" | wc -l](#cat-nypl_itemscsv--grep--i-paris--wc--l)**


[Back to Cheat Sheet](cheat_sheet.md)

***

#### **whoami**
- Sends back username for computer.

#### **pwd**
- Lets you know where you are located (pathname).

#### **ls**
- List all things in the directory where you are located.

#### **cd Downloads**
- Change directory to downloads directory (can be any directory).

#### **cd ..**
- Go to previous directory.

#### **cd ../..**
- Go two directories up.

#### **cd ~**
- Go to home directory.

#### **touch foo.txt**
- Touch file name (if no file available, will create file in current location).

#### **echo hello**
- Will return/print hello, can return anything typed.

#### **mkdir Projects**
- Make directory named Projects in the current location.

#### **rm file.txt**
- Remove/delete file named file.txt.

#### **mv bar.txt ~/Desktop**
- Move file named bar.txt to Desktop in home.

#### **mv bar.txt ../Desktop**
- Move file named bar.txt to the previous directory and the folder named Desktop in the previous directory.

#### **echo "My Cheat Sheet" > cheat_sheet.md**
- Create file named cheat_sheet.md with the text "My Cheat Sheet" in the file.
- Redirecting using echo puts what you want to echo into a file that you identify (.md stands for markdown).

#### **cat cheat_sheet.md**
- Concatenation/printing of contents of file.

#### **code cheat_sheet.md**
- Open the file cheat_sheet.md using VS Code.

#### **cat cheat-sheet.md | sort**
- Sorts all lines of the file cheat-sheet.md.

#### **cat cheat-sheet.md | sort > sorted-cheat-sheet.md**
- Creates a new file with the sorted lines.

#### **less nypl_items.csv**
- Give a paginated view of the data page by page.

#### **head nypl_items.csv**
- Shows the header of the file.

#### **tail nypl_items.csv**
- Shows the tail of the file.

#### **cat nypl_items.csv | wc -l**
- Counts the lines (-l) in the file.

#### **cat nypl_items.csv | uniq | wc -l**
- Counts all of the unique (no duplicate) lines in the file.

#### **cat nypl_items.csv | uniq -d**
- Prints the lines that have duplicates.

#### **cat nypl_items.csv | uniq > nypl_no_dupes.csv**
- Creates new file without the duplicates.

#### **cat nypl_items.csv | grep -i "paris"**
- Prints the lines with paris in the line (-i ignores capitalization).

#### **cat nypl_items.csv | grep -i "paris" | wc -l**
- Prints the count of lines with paris in them.


[Back to Cheat Sheet](cheat_sheet.md)