

### main()的两种标准形式 

-  int main(void) 无参数形式
  
-  int main(int argc, char *argv[]) 带参数形式

### main()的几种非标准形式

-  main() C90标准允许但C99不允许
-  void main() 部分编译器支持

### 两种标准形式详解

1. int main(void)
 
   不支持来自命令行的参数
 
2. int main(int argc, char *argv[])
 
   - argc
     
     argument count.
     
   - argv
   
     argument vector

   尽管约定是用argc和argv来表示，但是也可以用其它变量名来表示
