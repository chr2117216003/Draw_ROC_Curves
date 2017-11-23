# Draw_ROC_Curves
### This is a python file which is used for drawing ROC curves
-f : assign file name
-t : assign file type
-r : when draw picture, it means the row number
-c : when draw picture, it means the column number
-i : the input file and the type is csv
-l : 1 means Print "A-Z" in the upper left corner, others are False. Default false
for example:
>python chr-ROC.py -f filename -t pdf -r 2 -c 1 -i NFC.csv,NFC.csv -l 1
where filename is the output file' name ande pdf means the 'pdf' type. After Combination, the full name is filename.pdf. It will be saved in local directory. Of course, file path can be included in  filename. Such as filename can be assgned as "C:/Program Files/filename".
