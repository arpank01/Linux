# VIm Commands (:

`:w` =save changes ie write 

`:q` =quit

`i`= insert mode 

`a`= also insert mode but characters appear  at the right of the cursor 

`o`= creates a new line the enters the insert mode 

`capital a / shift + a`= enters insert mode from the end of the line

`capital i / shift + i` = enters insert mode from the starting of the line 

`capital o / shift + o` = enters at a new line above the current line 

`esc` = gets out of the insert mode 

`vi (text file)` = in terminal it opens an existing file or creates a new file then opens it

`:set number` = Line numbering 



## //in normal mode 

`k` = goes up / works as upper arrow key  

`j` = goes down / works as lower arrow key

`h = left key` 

`l = right key`

## ~numbers can also be binded with key bindings such as k goes 1 up but 3k goes 3 lines up , h moves by 1 character but 3h moves by 3 character 

`:set relativenumber` = sets line numbering in such a way that current line is the first  line and other lines are numbered relative to that

### /in relative number mode it is easier to navigate using numbers + key bindings(h,j,k,l) as only the relative numbers are given 

`:set mouse=a`  = activate the mouse features in vim

`:set tabstop=4`

`:set shiftwidth=4`

`:set colorschemes + tab` = set color schemes according to your choice 

`:set autoindent `




## //in terminal 
 
`vi ~/.vimrc =opens the vim configuration file`  

you can write aall the settings here so that it sets the vim permanently to those settings , you just dont have to give ':' before everything , the rest is all the same like add " set number , set relativenumber " etc



## //code execution 
for basic cpp file running do 

`$sudo apt install g++`

`$sudo apt install build-essential `

then . . .

do create a file with vim using `$vi {filename}`

then compile it by 

`$g++ {filename}.cpp -o {filename}`

and then run it by `./{filename}`
