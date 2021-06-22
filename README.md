# table-
Create a program which print the table of a number . table of and table up to will be entered by user
table_of=input('table of = ')
upto = input('upto = ')
for i in range(1, len(upto)):
   print(table_of, '*', i, '=', table_of*i)
