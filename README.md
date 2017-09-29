# shell-commands
some tips
shell中使用变量，首次定义时只输入变量名，如 i=15
  再次引用时补加$号，如$i
  添加其他字符时将变量名括起，如${i}_year，输出为15_year
  shell引用awk，而awk反引用shell变量时，用双重引号，如 print "'$i'\n"
  
