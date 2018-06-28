# dictionary-implementation
with open("directory/path/filename.txt") as file:
	lines=list()
	lines=lines+[line.strip() for line in file]
	print("ENTER A LETTER OR WORD TO SEARCH")
	print(lines)
	s=input()
	for i in lines:
		if((s in i)or(s.upper() in i)or(s.lower() in i)or(s.swapcase in i)):
			print(i)
