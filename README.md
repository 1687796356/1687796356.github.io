一、单项选择题（20道小题，共20分） 
1、在每一个C程序中都必须包含有这样一个函数，该函数名为(  A   )。（1分） 
A、main B、MAIN 
C、name D、function 
15、若有定义语句：char s[10]="123\n\0\12370";，则strlen(s)的值是(  A   )。（1分） 
A、8 B、6 
C、5 D、4 
2、以下程序段，结果（A)。 main(){int a=5,b=0,c=0;if(a=b+c)  printf("***\n");else printf("$$$\n");}
A、有语法错不能通过编译	B、不确定
C、***	D、$$$
5、若有说明语句:char c='\72';则变量c(   A )。（1分）
A、包含1个字符	B、包含2个字符
C、包含3个字符	D、说明不合法,c的值不确定
6、设int a=5,b=9,c=15;，表达式(a+b)/c||(a<b)&&(a%b)的值为(   A  )。（1分）
A、0	B、2
C、1	D、-1
16、以下对结构体变量stul中成员num的非法引用是(  B  )。 struct  Student {int age;int num;}stu1,*p;p=&stu1;（1分）
A、p->num	B、(*p).num
C、stu1.num	D、Student.num
20、如果要以只读方式打开一个已存在的二进制文件，应使用的打开方式是（   C  ）。（1分）
A、r	B、r+
C、rb	D、w
5、若有定义语句：int x=10;，则表达式x-=x+x的值为(  B  )。
A、-20	B、-10
C、0	D、10
13、若有说明：int a[][3]={1,2,3,4,5,6};，则a数组第一维的大小是（  A   )。
A、2	B、3
C、4	D、无确定值
14、在以下定义中，正确的说明语句为( D    )。
A、int a[n]; 	B、int a[3,4]; 
C、int a[ ][ ]; 	D、int *a[10];
15、有定义char string[20];，选择正确的语句，使得string的内容为"I am student!"( D    )。
A、scanf("%s",string);	B、scanf("%c",&string);
C、scanf("%s",&string);	D、gets(string);
20、若fp已正确定义并指向某个文件，当未遇到该文件结束标志时函数feof(fp)的值为( C   )。
A、-1	B、1
C、0	D、一个非 0值
3、逻辑运算符两侧运算对象的数据类型( D   )。
A、只能是0或1	B、只能是0或非0正数
C、只能是整型或字符型数据	D、可以是任何合法类型的数据
8、已知int i=0;while (i=1){...}则以下叙述正确的是(  A  )
A、循环体执行0次	B、循环体执行1次
C、无限循环	D、循环体执行次数不确定
17、若有定义int a[9],*p=a;，则p+5表示(  B  )。
A、数组元素a[5]的值	B、数组元素a[5]的地址
C、数组元素a[6]的地址	D、数组元素a[0]的值加上5
19、有以下语句int a[10]={0,1,2,3,4,5,6,7,8,9},*p=a;，则对a数组元素的引用不正确的是( D    )其中0≤i≤9。
A、a[p-a]	B、*(&a[i])
C、p[i]	D、*(*(a+i))
1、以下关于算法的描述不正确的是(  A   )。
A、任何一个问题，它的实现算法是唯一的	
B、描述算法常用的表达工具有流程图、N-S图、PAD图、伪码等
C、算法的最终实现是计算机程序	
D、正确性和清晰易懂性是一个好算法的基本条件
4、若定义int x=-16,y=-12,z;，则语句z=x<=y;运行后z的值是（  B  ）。
A、true	B、1
C、false	D、0
6、sizeof(float)的结果是(   B  )。
A、-个双精度型数值	B、-个整型数值
C、-个字符型数值	D、-个任意类型的数值
11、在C语言中，数组名作为函数调用的实参传递给形参的是(   A  )。
A、数组的首地址	B、数组的第一个元素的值
C、数组的全部元素的值	D、数据的长度
16、若有以下定义，则下列叙述错误的是（ D )。 struct person{int num;char name[10];}student;
A、num、name都是结构体变量student的成员	B、student是结构体类型名
C、struct是定义结构体类型的关键字	D、struct person是用户定义的结构体类型名
20、fseek函数的正确调用形式是( B  )。
A、fseek(文件指针,起始点,位移量)	B、fseek(文件指针,位移量,起始点)
C、fseek(位移量,起始点,文件指针)	D、fseek(起始点,位移量,文件指针)
一、单项选择题（20道小题，共20分）
1、以下选项中不属于C语言标识符的是(  C  )。
A、用户标识符	B、关键字
C、常量	D、预定义标识符
2、若给定条件表达式(M)?a++:a--;则与表达式M等价的是（  C  ）。
A、M==0	B、M==1
C、M!=0	D、M!=1
4、以下程序，当输入数据为25 13 10时，正确的输出结果为(  A  )。 main(){int  x,y,z;scanf("%d%d%d",&x,&y,&z);printf("x+y+z=%d\n",x+y+z);}
A、x+y+z=48	B、x+y+z=35
C、48 	D、不确定值
5、若x、i、j和k都是int型变量，则计算表达式x=(i=4,j=16,k=32)后，x的值为（   C  ）。
6、A、4	B、16
C、32	D、52
6、C语言的基本类型包括（ B   ）。
A、整型、实型、数组	B、整型、实型、字符型
C、整型、字符型、结构体	D、整型、实型、字符串型
10、下列关于函数的定义中，错误的是(  A  )。
A、函数的定义可以嵌套	B、函数定义时可以不给出函数值的类型
C、函数定义时可以省略存储类型	D、函数可定义为内部函数
2、对于整型变量a，赋值语句a=(a%3==0?1:0);与（  D   ）语句不等价。
A、if(a%3==0)a=1;else a=0;	B、if(a%3!=0)a=0;else a=1;
C、if(a%3)a=0;else a=1;	D、if(a%3)a=1;else a=0;
4、若已定义float x;要从键盘输入数据36.583给变量x，则正确的输入格式是（ B   ）。
A、scanf("%2.3f",&x);	B、scanf("%6.3f",&x);
C、scanf("%f",&x);	D、scanf("%lf",&x);
5、在C语言中,要求操作数必须是整型的运算符是( D    )。
A、++	B、-
C、/	D、%
6、设变量a是int型，f是float型，i是double型，则表达式10+'a'+i*f值的数据类型( C   )。A、int 	B、float
C、double	D、不确定
10、在函数的定义格式中，下列可以省略的部分是(  B  )。
A、函数名 	B、函数体
C、函数类型 	D、函数参数
16、在声明一个结构体类型变量时系统分配给它的存储空间是(   C  )。
A、该结构体变量中第一个成员所需存储空间	B、该结构体变量中最后一个成员所需存储空间
C、该结构体变量中所有成员所需存储空间的总和	D、结构体体变量中长度最长的成员所需存储空间
20、函数调用语句：fseek(fp,-10L,2);的含义是（  A  ）。
A、将文件位置指针从文件末尾处向文件头的方向移动10个字节	B、将文件位置指针从当前位置向文件头的方向移动10个字节
C、将文件位置指针从当前位置向文件末尾的方向移动10个字节	D、将文件位置指针移动到距离文件头10个字节处
1、以下叙述中错误的是( B    )。
A、算法正确的程序最终一定会结束	B、算法正确的程序可以有0个输入
C、算法正确的程序可以有0个输出	D、算法正确的程序对于相同的输入一定有相同的结果
2以下程序段的运行结果是（A）。 int a=0,b=2,c;switch(a){case 0:c=b++;case 1:switch(b){ case 1:c++;break;case 2:c*=b;break;default:c+=b;}break; default:c--;} printf("%d\n",c);
A、5	B、4
C、6	D、不确定
3、以下选项中，当x为大于1的奇数时，值为0的表达式是（  B  )。
A、x%2==0	B、x%2!=0
C、x%2==1	D、x/2
4、getchar()函数的功能是从终端输入（ C   ）。
A、一个整型变量值	B、一个实型变量值
C、一个字符     	D、多个字符
6、设char ch='c';，则表达式ch+1的值是（ D   ）。
A、97	B、98
C、99	D、100
8、设有程序段int k=10;while(k=0) k=k-1;，则下面描述中正确的是（   C   )。
A、while循环执行10次	B、循环是无限循环
C、循环体语句一次也不执行	D、循环体语句执行一次
9、若有以下函数首部int fun(double x[10],int *n)，则下面针对此函数的函数声明语句正确的是(  C  )。
A、int fun(double,int );	B、int fun(double *x,int n);
C、int fun(double *,int *);	D、int fun(double x,int *n);
15、下列描述中不正确的是(  C   )。
A、字符型数组中可以存放字符串 	B、可以对字符型数组进行整体输入、输出 
C、可以对整型数组进行整体输入、输出 	D、不能在赋值语句中通过赋值运算符"="对字符型数组进行整体赋值
16、对于结构体定义,不正确的叙述是( C   )。
A、结构体变量可以像普通变量一样进行各种运算	B、同类型的结构体变量可以相互赋值
C、在定义结构体变量时可以对变量赋初始值	D、可以不指定结构体类型名而直接定义结构体类型变量
18、设有定义：int x=0,*p;，紧接着的赋值语句正确的是( C   )。
A、*p=&x;	B、p=&x;
C、p=x;	D、*p=x;
20、若以"a+"方式打开一个已存在的文件，则以下叙述正确的是(  A  )。
A、文件打开时，原有文件内容不被删除，位置指针移到文件末尾，可作添加和读操作	B、文件打开时，原有文件内容不被删除，位置指针移到文件开头，可作重写和读操作
C、文件打开时，原有文件内容被删除，只可作写操作	D、以上各种说法皆不正确
1、以下叙述中正确的是(  C  )。
A、 C语言比其他语言高级
B、 C语言可以不用编译就能被计算机识别执行 
C， C语言以接近英语国家的自然语言和数学语言作为语言的表达形式	
D、 C语言出现的最晚，具有其他语言的一切优点
2、以下说法正确的是(  C   )。
 A、C语言程序总是从第一个函数开始执行
 B、在C语言程序中，要调用函数必须在main()函数中定义
 C、C语言程序总是从main()函数开始执行
 D、C语言程序中的main()函数必须放在程序的开始部分
3、下列可用于C语言用户标识符的一组是(  B  )。
A、  void   define  WORD       
B、  a3_b3   _123   Car 
C、  For abc      case       
D、  2a    DO    sizeof
4、设int a=3,b=4,c=5;表达式(a+b)>c&&b==c的值是(  C  ) 。
 A、2           B、-1         C、0           D、1
5、以下关于循环体的描述中，(  C   )是错误的。      
A、 循环体中可以出现break语句     
B、 循环体中还可以出现循环语句  
C、 循环体中不能出现continue语句   
D、 循环体中可以出现switch语句
6、While(x)中的x相当于( D  )。
 A、x==0         B、x==1 C、x!=1         D、x!=0
7、以下关于switch语句和break描述中 , (  A  ) 是正确的。
 A、在switch语句中,可以根据需要使用或不使用break语句	
 B、switch语句中必须用break语句
C、break语句只能用于switch语句
 D、break语句是switch语句必须的一部分
8、以下对C语言函数的有关描述中，正确的是(  B  )。
 A、在C中，调用函数时，只能把实参的值传送给形参，形参的值不能传送给实参 
 B、C函数既可以嵌套调用又可以递归调用  
C、函数必须有返回值，否则不能使用函数 
 D、C程序中有调用关系的所有函数必须放在同一个源程序文件中、
9、在下面的函数声明中，存在着语法错误的是(  D  )。
 A、int  BF(int  x , int  y);      
B、void  BC(int  a , int); 
C、void  BD(int , int);          
D、void  BE(int , int=5)
10、在调用函数时，如果实参是简单变量，它与对应形参之间的数据传递方式是( B )。
 A、地址传递                           B、单向值传递 
C、由实参传给形参，再由形参传回实参   D、传递方式由用户指定
11、一个程序源文件中全局变量作用范围为(  D   )。
 A、本文件的全部范围             B、本程序的全部范围 C、本函数的全部范围             D、从定义该变量位置开始至文件结束
12、若有以下语句：static char x[ ]="12345"；static char y[ ]={'1'，'2'，'3'，'4'，'5'}；则正确的说法是(  B   )。
 A、 x数组和y数组的长度相同          B、 x数组的长度大于y数组的长度 C、 x数组的长度小于y数组的长度      D、 x数组与y数组等价
13、在C++语言中，定义数组后，使用数组元素时，数组下标可以是(  C   )。
 A、 整型常量                    B、 整型表达式 
C、 整型常量或整型表达式        D、 任何类型的表达式
14、在下面的一维数组定义中，哪一个(  A  )有语法错误。
 A、int  a[ ];                   B、int  a[ ]={1,2,3}; 
C、int  a[5];                  D、int  a[10]={0};
15、在声明语句const char *ps;中，ps表示(  C  )。  
 A、 指向字符串的指针           B、 指向字符串的const型指针  
 C、 指向const型字符串的指针    D、 指向const型字符串的const型指针
 16、若有语句： int x[]={1,2,3,4,5}; int *ptr; ptr=x; 则(  C  ) 是对数组元素x[1]的正确引用。
 A、ptr+1          B、*ptr+1     
 C、*(ptr+1)        D、*ptr++
17、在int k=8，*p=&k中，*p的值是(  C  )。 
 A、 指针变量p的地址值        B、 变量k的地址值   C、 8                         D、 无意义
18、设int x=5,y=9,z=15，表达式(x+y)/z||(x<y)&&(x%y) && (!X) 的值为(  A  )。
 A、0    B、2    C、1      D、-1
19、若变量c为char类型，能正确判断出c为大写字母的表达式是(  C  ) 。  
A、'a'<=c<='z'              B、(c>='a')||(c<='z')   
C、(c>='A')&&(c<='Z')        D、('a'<=c)and('z'>=c)        
20、以下 (  C  )是不正确的描述。
 A、while循环先判断表达式,后执行循环体语句
 B、do-while循环先执行循环语句,后判断表达式
C、while，do-while 循环效果完全一样,不会出现不一致情况	
 D、for循环可以用while语句代替
21、下列关于函数的参数的描述中，错误的是(  D  )。
 A、 C语言函数的参数可以是多个
 B、 C语言函数参数可以0个 C、 
C语言函数的形参可以是指针或引用
 D、 C语言函数的形参与实参类型要求一致不是必需的。
22、以下叙述中不正确的是(  D   ) 。               
 A、  预处理命令都必须以#号开始
 B、  在程序中凡是以#号开始的语句行都是预处理命令行
 C、  宏替换不占用运行时间，只占编译时间
 D、  在以下定义是正确的：#define PI 3.1415926;
23、以下能正确定义一维数组的选项是(  B  )。
A、 int  a[5]={0,1,2,3,4,5};         B、 char  a[]={'0','1','2','3','4','5','\0'}; C、 char  a={'A','B','C'};           D、 int   a[5]="0123";
24、下面程序段char *p="abcdefgh"; p+=3; printf("%d\n",strlen(strcpy(p,"ABCD")));的运行结果是(  C  )。
 A、 8     B、 12    C、 4       D、 7
25、由C/C++源程序文件编译而成的目标文件的缺省扩展名为(  C   )。 
 A、 cpp   B、 exe    C、 Obj    D、 lik 
26、下列语句哪个是正确的(  B   )。
 A、int a="a";       B、char c=105;      C、char c="abc";    D、char c="\n";
27、如执行以下语句,for (I=1;I<=100;I++){sum=sum+I;}循环结束后I值是(  C  )。
 A、100     B、99        C、101        D、102
28、下面有关for循环的正确描述是(  D  )。      
 A、  for循环只能用于循环次数己经确定的情况 
 B、  for循环是先执行循环体语句，后判定表达式  
C、  在for循环中，不能用break语句跳出循环体 
 D、  for循环体语句中，可以包含多条语句，但要用花括号括起来 
29、在C/C++中，函数原型不能标识(  A  )。 
 A、函数的功能              B、函数的返回类型
 C、函数参数的个数          D、函数参数类型
30、C语言中数组下标的下限是(  B  )。 
 A、1         B、0     C、视具体情况       D、无固定下限
31、下列描述中不正确的是(  C   )。  
 A、字符型数组中可以存放字符串 
 B、可以对字符型数组进行整体输入、输出  
C、可以对整型数组进行整体输入、输出 
 D、不能在赋值语句中通过赋值运算符"="对字符型数组进行整体赋值
32、在以下定义中，正确的说明语句为(  D  )。 ）
 A、int a['a'];      B、int a[3,4];      C、int a[ ][ ];      D、int *a[10];
33、在声明语句int *fun();中，fun表示(  B  )。   
 A、 一个用于指向函数的指针变量
 B、 一个返回值为指针型的函数名   
C、 一个用于指向一维数组的行指针
 D、 一个用于指向int型数据的指针变量
 34、若有语句：char *line[5];，以下叙述中正确的是(  A  )。 
 A、  定义line是一个数组，每个数组元素是一个基类型为char为指针变量	 
B、  定义line是一个指针变量，该变量可以指向一个长度为5的字符型数组
 C、  定义line是一个指针数组，语句中的*号称为间址运算符	
 D、  定义line是一个指向字符型函数的指针
35、for(int x=0; x <=5;x+=2){...}语句执行循环的次数是(  A  )。   
 A、3     B、4     C、5         D、6 
36、执行以下语句,for (I=10;I>=0;I--,I--){sum=sum+I;}循环结束sum和I的值分别是( D )。
 A、32  0     B、30  0     C、28  1     D、30  2
37、函数调用语句fun(a1,f(a,b),3+x);中fun函数的参数个数是(  C  ) 。 
 A、 1      B、 2       C、 3        D、 4
38、设有数组定义：char array[]＝"China";，则数组array所占的空间为(  C  ) 。 
 A、  4个字节      B、  5个字节      C、  6个字节      D、  7个字节
39、程序段char str[]="ABC"; *p=str; printf("%d\n",*(p+2));的运行结果是(  A  )。 
 A、 67       B、 0     C、 字符'C'的地址       D、 字符'C'
40、下述关于break语句的描述中，(  C  )是不正确的。  
 A、 break语句可用于循环体内，它将退出该重循环 	
 B、 break语句可用于switch语句中，它将退出switch语句 
 C、 break语句可用于if体内，它将退出if语句 
 D、 break语句在一个循环体内可以出现多次
41、在C语言程序中，当while语句构成的循环中的条件为(  A  )时，结束循环。  
 A、0      B、1      C、true        D、非0
42、有一个int型变量，在程序中频繁调用，最好把它定义为(  A  )。 
 A、 register      B、 auto     C、 extern       D、 static 
43、以下不能对二维数组a进行正确初始化的语句是(  C   )。 
 A、 int a[2][3]={0};                 B、 int a[][3]={{1,2},{0}}; C、 int a[2][3]={{1,2},{3,4},{5,6}};      D、 int a[][3]={1,2,3,4,5,6};
44、对于声明语句int *p[10]; 下列(  B  )描述是正确的。  
 A、 p是指向数组中第10个元素的指针  
 B、 p是具有10个元素的指针数组，每个元素是一个int型指针  
 C、 p是指向数组的指针  
 D、 p[10]表示数组的第10个元素
 45、对于指针的运算，下列说法(  C  )是错误的  
 A、 可以用一个空指针赋值给某个指针
 B、 一个指针可以加上一个整数   C、 两个指针可以进行加法运算  
 D、 两个指针在一定条件下，可以进行相等或不相等的运算 
46、一个函数无返回值时，应选择下列的说明符是(  C  )。 
 A、 static     B、 extern       C、 void      D、 无说明符
47、在C语言中，若对函数类型未加显式说明，则函数的隐含类型是(  C  )类型。  
 A、void      B、double     C、int       D、char
48、以下定义语句中，错误的是(  D   )。  
 A、int a[]={1,2};           B、char *a[3];  C、char s[10]="test";       D、int n=5,a[n];
49、下面程序int a[10]={1,2,3,4,5,6,7,8,9,10},*p=a;printf("%d\n",*(p+2));的输出结果是( A  )。 
 A、 3         B、 4      C、 1         D、 2
50、C语言中合法的字符常量是(  C   )。 
 A、"ABC"       B、"$"       C、'\n'         D、95
51．在下面的一维数组定义中，哪一个( A )有语法错误。 
 A．int  a[ ];                   B．int  a[ ]={1,2,3};C．int  a[5];                  D．int  a[10]={0};
52．若有以下程序段：
   int a=1,b=2,c;
   c=1.0/b*a;
   则执行后，c中的值是（ A   ）。
  A．0             B．0.5              C．1                D．2
53．有以下语句
      typedef struct  S 
      {    int g;
 char h; 
}T
以下叙述中正确的是  (B )       。
  A．可用S定义结构体变量                  B．可用T定义结构体变量
  C．S是struct类型的变量                   D．T是struct S类型的变量
54．下面错误的叙述是（  D  ）。
  A．在某源程序不同函数中可以使用相同名字的变量
  B．函数中的形式参数是局部变量
  C．在函数内定义的变量只在本函数范围内有效
  D．在函数内的复合语句中定义的变量在本函数范围内有效
55．函数调用语句function((exp1,exp2), 18)中含有的实参个数为（C    ）。
 A．0             B．1                C．2            D．3

56、已知int t=0；while (t=1){...}则以下叙述正确的是(  B   )。
 A、 循环控制表达式的值为0       B、 循环控制表达式的值为1 
C、 循环控制表达式不合法         D、 以上说法都不对
57、下列关于函数值的说法中,正确的是(  B  )         。 
 A、 定义函数时,函数名前必须指明类型,否则该函数值没有类型	
 B、 定义函数时,若未指明函数的类型,则该函数值的类型为 int
 C、 函数值的类型只能是数值类型,如int、float等
 D、 定义函数时的函数体的最后必须有return语句,返回函数值
58、若有定义：int a[2][3];则对a数组的第i行第j列(假调i,j已正确说明并赋值)元素值的正确引用为(  A  )。 
 A、 *(*(a+i)+j)     B、 (a+i)[j]    C、 *(a+i+j)      D、 *(a+i)+j
59、下面函数调用语句func((exp1,exp2),(exp3,exp4,exp5));中func函数有实参的个数为(  B  )。
 A、 1      B、 2        C、 4      D、 5
60、若有定义int a[9],*p=a；则p+5表示(  B   )。
 A、 数组元素a[5]的值     B、 数组元素a[5]的地址 C、 数组元素a[6]的地址   D、 数组元素a[0]的值加上5
61、函数swap(int x, int y)可实现对x和y值的交换。在执行如下定义及调用语句后，a和b的值分别为（   B ）。
  int a=10, b=20;
  swap (a,b );
 A．10和10        B．10和20          C．20和10          D．20和20
62、下面程序段char *p="abcdefgh"; p+=3; printf("%d\n",strlen(strcpy(p,"ABCD")));的运行结果是(   C )。
 A． 8     B． 12    C． 4       D． 7
63、以下叙述中不正确的是(  D   )。
 A、在不同的函数中可以使用相同名字的变量 
 B、函数中的形式参数是局部变量  C、在一个函数内定义的变量只在本函数范围内有效 
 D、在一个函数内的复合语句中定义的变量在本函数范围内有效
64、C语言中不合法的字符串常量是(  B  )。
 A、 "\121"         B、 'y'         C、 "\n\n"         D、 "ABCD\x6d"
65、已知char m[]="Convert",*p=m;则*(p+5)的值是(  C  )。 
 A、  e            B、  Convert    C、  r             D、  不确定
66、设p1和p2是指向同一个int型一维数组的指针变量,k为int型变量,则不能正确执行的语句是(  B   )。 
 A、 k=*p1+*p2;       B、 p2=k;      C、p1=p2;            D、k=*p1;
 67、对语句float (*pf)(float x);的描述，正确的是(  A   )。
 A、一个用于指向函数的指针变量            B、一个返回值为指针型的函数名   C、一个用于指向float型数据的指针数组     D、一个用于指向float型数据的指针变量 
68、设已定义int a[3][2]={10,20,30,40,50,60};和语句(*p)[2]=a;，则*(*(p+2)+1)的值为（   A ）。
  A．60                     B．30                      C．50                     D．不能确定
69、若有以下定义和语句，则对a数组元素地址的正确引用是（C　　）。
    int a[2][3], (*p)[3];
    p=a;
  A．*(p+2)           B．p[2]             C．p[1]+1               D．(p+1)+2
70、若有int max( ), (*p)( );，为使函数指针变量p指向函数max，正确的赋值语句是（　A　）。
  A、p=max;       B．*p=max;          C．p=max(a, b);     D．*p=max(a, b);

71、程序段：int x=20,y=3;printf(“%d\n”,x/y);的输出结果是  (c  )      。
A)6.66                B)2               C)6                  D)6.7
73、关系表达式：x≤y≤z的C语言表达式正确的是 （B）       。
A)(x<=y<=z)     B) (x<=y)&&(y<=z)      C) (x<=y)||(y<=z)   D) (x<=y)&(y<=z) 
74、合法的数组定义是  (A  )    。
   A)char a[]="string";                         B)int a[5]={0,1,2,3,4,5};
   C)char s="string";                           D)char a[]={0,1,2,3,4,5};
75、若变量已正确定义为float型，要给x,y,z输入数据，正确的输入语句是  (  B)     。
A)scanf(“%f%f%f”,x,y,z)                     B) scanf(“%f%f%f”,&x,&y,&z) 
C)scanf(“%d%d%d”,x,y,z)                    D)read(a,b,c)
76、有以下语句
      typedef struct  S 
      {    int g;
 char h; 
}T
以下叙述中正确的是(B  )  。
A)可用S定义结构体变量                  B) 可用T定义结构体变量
   C)S是struct类型的变量                     D)T是struct S类型的变量
77、有定义语句：int  x,y,*px,*py,执行了px=&x, py=&y;之后，正确的输入语句是 (C  )  
    A）scanf(“%d%d”,x,y);                         B） scanf(“%d%d”,&px,&py);
   C）scanf(“%d%d”,px,py）;                  D） scanf(“%ldf%ld”,x,y);
78、有以下程序
# include<stdio.h>
main()
{ int a=1,b=0;
    if (!a)   b++;
    else  if(a==0)  if(a)  b+=2;
    else  b+=3;
    printf(“%d\n”,b);
}
程序运行后的输出结果是 （ A）       。
A) 0                    B）1                     C) 2                     D)  3 
79、有如下程序 
main()
{ int x=23;
do
{ printf("%d",x--);}
while(!x);
}
该程序的执行结果是  (  B )      。
A) 321              B) 23              C) 2322            D) 陷入死循环
80、以下程序的输出结果是 (C )   。
main()
{ int i, a[10];
 for(i=9;i>=0;i--) a[i]=10-i;
    printf("%d%d%d",a[2],a[5],a[8]);
}
A) 258              B) 741               C) 852             D) 369
81、以下程序的运行结果为（  D  ）。
#include <stdio.h>
int main( )
{
    int i=1,sum=0;
    while(i<=100)
        sum+=i;
        i++;
    printf("1+2+3+...+99+100=%d", sum);
return 0;
}
A．5050              B．1            C．0            D．程序陷入死循环
82、以下程序的输出结果是     C    。
# include<stdio.h>
int main()
{ int i, a[10];
 for(i=9;i>=0;i--) a[i]=10-i;
    printf("%d%d%d",a[2],a[5],a[8]);
return 0;
}
A． 258              B． 741               C．852             D．369
83、有如下程序
main()
{ int a[3][3]={{1,2},{3,4},{5,6}},i,j,s=0;
for(i=1;i<3;i++)
for(j=0;j<i;j++) 
s+=a[i][j];
printf("%d\n",s);
}
该程序的输出结果是  (A )       。
A) 14                  B) 19                 C) 20                   D) 21
84、执行下面的程序后,a的值为: (B )   。
   main()
   { int a,b;
     for (a=1,b=1;a<=100;a++) 
      { if(b>=20)break;
        if(b%3==1)
         {b+=3;
          continue;
          }b-=5;
         }
     }
    A)7                B)8                 C)9               D)10
85、以下循环体的执行次数是  （C  ）      。
A) 3                 B) 2                 C) 1               D) 0
main()
{ int i,j;
  for(i=0,j=1; i<=j+1; i+=2, j--)	printf(“%d \n”,i);
}
86、有以下程序
#include <stdio.h>
 int fun ()
  { static int x=1;
      x*=2;
   return x;
   }
  main()
  { int i,s=1;
    for(i=1;i<=3;i++)    s*=fun();
    printf(“%d\n”,s);
    }
   程序运行后的输出结果(  D  ) 。    A)0                        B)10                     C)30                       D)64
87、有以下程序
 #include <stdio.h>
  struct   S
     { int a,b; }data[2]={10,100,20,200};
   main()
     {struct  S  p=data[1];
      printf(“%d\n”,++(p.a));
     }
  程序运行的输出结果是(D  )
   A) 10                  B) 11                  C) 20                     D)21
88．设int a=5,b=9,c=15，表达式(a+b)/c||(a<b)&&(a%b)的值为(  C   )。 
 A．0    B．2    C．1      D．-189．若变量c为char类型，能正确判断出c为小写字母的表达式是( D    ) 。   
 A．'a'<=c<='z'              B．(c>='a')||(c<='z') C．('a'<=c)and('z'>=c)        D．(c>='a')&&(c<='z')90．下列字符序列中，不可用作C语言标识符的是（   B ）。
 A．xds426        B．No.1             C．_ok              D．Zwd
91．While(x)中的x相当于( D  )。 
 A．x==0         B．X+==1 C．x!=1         D．x!=0
92．若变量已正确定义为float型，要给x,y,z输入数据，正确的输入语句是  (B  )    。
  A．scanf(“%f%f%f”,x,y,z)                     B．scanf(“%f%f%f”,&x,&y,&z) 
  C．scanf(“%d%d%d”,x,y,z)                    D．read(a,b,c)
93．（ A  ）是构成C语言程序的基本单位。
A、函数        B、过程       C、子程序    D、子例程
94．C语言程序从     C          开始执行。
 A) 程序中第一条可执行语句     B) 程序中第一个函数
   C) 程序中的main函数          D) 包含文件中的第一个函数
95、以下说法中正确的是（  C  ）。
   A、C语言程序总是从第一个定义的函数开始执行
   B、在C语言程序中，要调用的函数必须在main( )函数中定义
   C、C语言程序总是从main( )函数开始执行
   D、C语言程序中的main( )函数必须放在程序的开始部分
96.下列关于C语言的说法错误的是（ B ）       。
A) C程序的工作过程是编辑、编译、连接、运行 
B) C语言不区分大小写。
C) C程序的三种基本结构是顺序、选择、循环 
D) C程序从main函数开始执行
97.下列正确的标识符是（C　）。
A.-a1             B.a[i]          C.a2_i          D.int t
98．下列C语言用户标识符中合法的是（ B ）。
     A)3ax   B)x   C)case   D)-e2    E)union
99．下列四组选项中，正确的C语言标识符是（ C  ）。
A）  %x           B）   a+b       C）  a123          D） 123
100、下列四组字符串中都可以用作C语言程序中的标识符的是（ A ）。
   A、print  _3d   db8  aBc     B、I\am  one_half  start$it  3pai
   C、str_1  Cpp  pow  while    D、Pxq  My->book  line#  His.age  
101.在C语言程序中，表达式5%2的结果是  C   。
        A)2.5     B)2      C)1         D)3
102．如果int a=3,b=4；则条件表达式"a<b? a:b"的值是__A__。
A) 3         B) 4            C) 0       D) 1
103．若int x=2,y=3,z=4 则表达式x<z?y:z的结果是( B  ).
     A)4   B)3    C)2    D)0  E)1
104．C语言中，关系表达式和逻辑表达式的值是（ B   ）    。
	A) 0         B) 0或1        C) 1       D) ‘T’或’F’
105. 下面(  D   )表达式的值为4.
     A)  11/3            B)  11.0/3
     C)  (float)11/3    D)  (int)(11.0/3+0.5)
106.设整型变量 a=2，则执行下列语句后，浮点型变量b的值不为0.5的是（  B　）
A.b=1.0/a           B.b=(float)(1/a) 
  C.b=1/(float)a      D.b=1/(a*1.0)
107. 若“int n; float f=13.8;”,则执行“n=(int)f%3”后，n的值是（A）
A.1               B.4                 C.4.333333         D.4.6
108. 以下对一维数组a的正确说明是：   D    
A)char a（10）； 			B) int a[]； 
C)int k＝5，a[k]；      D）char  a[3]={‘a’,’b’,’c’};
109.以下能对一维数组a进行初始化的语句是: (    C    )
  A. int a[5]=(0,1,2,3,4,)  B. int a(5)={}  
C. int a[3]={0,1,2}       D. int a{5}={10*1}
110.在C语言中对一维整型数组的正确定义为   D    。
        A)int a(10);          B)int n=10,a[n]; 
C)int  n;a[n];        D)#define N 10
                       int a[N]; 
111、已知：int  a[10]; 则对a数组元素的正确引用是（  D  ）。
   A、a[10]     B、a[3.5]     C、a(5)     D、a[0]
112.若有以下数组说明，则i=10;a[a[i]]元素数值是（C　）。
int a[12]={1,4,7,10,2,5,8,11,3,6,9,12};
A.10          B.9           C.6           D.5
113.若有说明：int a[][3]={{1,2,3},{4,5},{6,7}}; 则数组a的第一维的大小为: ( B  )
  A.  2     B.  3     C.  4   D.无确定值
114.对二维数组的正确定义是（ C　）
　　 A.int a[ ] [ ]={1,2,3,4,5,6};     B.int a[2] [ ]={1,2,3,4,5,6};
C.int a[ ] [3]={1,2,3,4,5,6};     D.int a[2,3]={1,2,3,4,5,6};
115．已知int a[3][4];则对数组元素引用正确的是__C___
       A)a[2][4]    B)a[1,3]   C)a[2][0]    D)a(2)(1) 
116.C语言中函数返回值的类型是由（A ）决定的.
    A)函数定义时指定的类型          B) return语句中的表达式类型 
    C) 调用该函数时的实参的数据类型 D) 形参的数据类型
117. 在C语言中，函数的数据类型是指( A )
A 函数返回值的数据类型           B. 函数形参的数据类型
C 调用该函数时的实参的数据类型   D.任意指定的数据类型
118.  在函数调用时，以下说法正确的是（ B　）
　A.函数调用后必须带回返回值
　B.实际参数和形式参数可以同名
　C.函数间的数据传递不可以使用全局变量
　D.主调函数和被调函数总是在同一个文件里
119. 在C语言中，表示静态存储类别的关键字是: （   C   ）
A) auto   	B) register   	C) static    	D) extern
120．未指定存储类别的变量，其隐含的存储类别为（ A  ）。
        A)auto   B)static   C)extern   D)register 
121. 若有以下说明语句：
        struct  student
         { int num;
           char name[ ];
           float score;
          }stu;
      则下面的叙述不正确的是: ( D )
A. struct是结构体类型的关键字 
B. struct student 是用户定义的结构体类型
C. num, score都是结构体成员名        
D. stu是用户定义的结构体类型名
122.若有以下说明语句：
        struct  date
         { int year;
           int month;
           int day;
          }brithday;
      则下面的叙述不正确的是__C___.
A) struct是声明结构体类型时用的关键字       
B) struct date 是用户定义的结构体类型名
C) brithday是用户定义的结构体类型名   
D) year,day 都是结构体成员名
123. 以下对结构变量stul中成员age的非法引用是   B     
struct student
{ int age；
int num；
}stu1,*p；
p=&stu1；
A) stu1.age   B) student.age   C) p->age    D) (*p).age
124.设有如下定义：
struck sk
{   int a;
float b;
}data;
int *p;
若要使P指向data中的a域，正确的赋值语句是  C    
A)p=&a;		B) p=data.a;	C) p=&data.a;	D)*p=data.a;
125．有如下程序
# include<stdio.h>
int main()
{ int a[3][3]={{1,2},{3,4},{5,6}},i,j,s=0;
for(i=1;i<3;i++)
for(j=0;j<i;j++) 
s+=a[i][j];
printf("%d\n",s);
return 0;
}
该程序的输出结果是 （A）        。
A．14                  B．19                 C． 20                   D． 21
126．执行下面的程序后,a的值为:  （B）      。
# include<stdio.h>
  int  main()
   { int a,b;
     for (a=1,b=1;a<=100;a++) 
      { if(b>=20)break;
        if(b%3==1)
         {  b+=3;
            continue;
          }
b-=5;
         }
       return 0;   }
  A．7                B．8                 C．9               D．10

127.设有以下说明语句：
           typedef  struct  stu
           {  int  a;
              float  b;
           } stutype;
    则下面叙述中错误的是（ D  ）。
    A、struct是结构类型的关键字   
B、struct stu是用户定义的结构类型  
    C、a和b都是结构成员名
D、stutype是用户定义的结构体变量名
128． 语句int *p;说明了   C   。
A)p是指向一维数组的指针    
B)p是指向函数的指针,该函数返回一int型数据
C)p是指向int型数据的指针   // 指针的定义教材P223
D)p是函数名,该函数返回一指向int型数据的指针
129．下列不正确的定义是（　A  ）。
A.int *p=&i,i;                  B.int *p,i;
C．int i,*p=&i;                  D.int i,*p;
130. 若有说明：int n=2,*p=&n,*q=p,则以下非法的赋值语句是: （　D  ）
A）p=q        B）*p=*q     C）n=*q      D）p=n
131．有语句：int a[10],;则  B   是对指针变量p的正确定义和初始化。
A)int p=*a;  B)int *p=a;   C)int p=&a;  D)int *p=&a;
132.若有说明语句“int a[5],*p=a;”,则对数组元素的正确引用是( C )。
A.a[p]            B.p[a]              C.*(p+2)         D.p+2
133. 有如下程序
int  a[10]={1,2,3,4,5,6,7,8,9,10},*P=a;
则数值为9的表达式是  B    
A) *P+9            B) *(P+8)          C) *P+=9         D) P+8
134. 在C语言中，以   D   作为字符串结束标志
A)’\n’      B)’ ’      C) ’0’    D)’\0’ 
135.已知char x[]="hello", y[]={'h','e','a','b','e'};, 则关于两个数组长度的正确描述是  （B）   .
A)相同     B)x大于y    C)x小于y   D)以上答案都不对
136、有以下程序段
      struct st 
      { int x; int *y;}*pt: 
      int a[]={1,2}，b[]={3,4}; 
      struct st c[2]={10,a,20,b};
      pt=c; 
      以下选项中表达式的值为11的是（c ）
      A) *pt->y  B) pt->x  C) ++pt->x  D) (pt++)->x 
137、有以下程序
      typedef struct{int b,p;}A; 
      void f(A c) /*注意：c是结构变量名 */
      {int j;
      c.b+=1; c.p+=2;
      }
      main()
      {int i;
      A a={1,2};
      f(a);
      printf(“%d,%d\n”,a.b,a.p);
      }
      程序运行后的输出结果是
      A）2，3  B）2，4  C）1，4  D）1，2
138、设已有定义：float x;则以下对指针变量p进行定义且赋初值的语句中正确的是
      A)float *p=1024;    B)int *p=(float x);
      C)float p=&x;       D)float *P=&x;
  
 139、有以下程序
      #include <stdio.h>
      main()
      {int n,*p=NULL;
      *p=&n;
      printf(“Input n:”); scanf(“%d”,&p); printf(“output n:”); printf(“%d\n”,p);
      }
      该程序试图通过指针p为变量n读入数据并输出，但程序有多处错误，以下语句正确的是
A,intn,*p=NULL;      B)*p=&n;      C)scanf(“%d”,&p)        D)printf(“%d\n”,p); 

二、判断题（10道小题，共10分）
3、若a是实型变量，C程序允许赋值a=10，因此实型变量中允许存放整型数据。（×） 
2、int i=20;switch(i/10){case 2:printf("A");case 1:printf("B");}的输出结果为A。（X）
3.  C程序中，%是只能用于整数运算的运算符。（√）
3、C程序中，无论是整数还是实数，都能被准确无误地表示出来。（X）
10、若成功执行fopen( )函数，则函数返向值是NULL。（X）
8、同一结构体类型中的各成员项数据类型可以不相同。（√）
4、for循环是先执行循环体语句，后判断表达式。（×）
5、函数的形参可以是常量、变量或表达式。（×）
6、字符数组可以存放字符串。（√）
7、设有定义char str[80];能将字符串"Zhengzhou  2019"从键盘输入数组str的语句是scanf("%s",str)。（×）
9、char *s="china";等价于 char *s;s="china";（×）
10、指向文件型数据的指针变量的正确定义为：FILE *fp;。（√）
3、设x、y和z是int型变量，且x=3,y=4,z=5,则!((x<y)&&!z||1)表达式的值为0。（×）
6、可以在赋值语句中通过赋值运算符“=”对字符数组整体赋值。（×）
8、可以通过输出结构体变量名来输出结构体变量的所有成员。（√）
10、在C程序中，可以对文件顺序读写，也可以对文件随机读写。（√）
1、预定义标识符可用作用户标识符，但失去原有意义。（√）
5、形参是局部变量。（√）
8、结构体变量所需内存长度为第一个变量的长度。（×）
9、char *p="girl";的含义是定义字符型指针变量p，p的值是字符串"girl"。（×）
10、当成功关闭一个文件时返回值为0，否则返回EOF(-1)。（√）
4、当调用函数时，实参是一个数组名，则向函数传送的是数组的首地址。（√）
8、在程序中定义了一个结构体类型后，可以多次用它来定义具有该类型的变量。（√）
判断题
1、do-while语句构成的循环只能用Break语句退出。( ×) 
2、函数的返回值是通过函数中的return语句获得的。( √)  
3、C语言程序中的#include和#define均不是C语句。( √ )  
4、字符数组中的字符串可以整体输入或输出。( √  )     
5、同一结构体类型中的各成员项数据类型可以不相同。( √  ) 
6、对于指向同一个数组的两个指针变量而言，两个指针变量相减的操作是有意义的。(  √ ) 
7、C语言源程序文件通过了编译、连接之后，生成一个后缀为 .EXE 的文件。(  √ ) 
8、若有运算符：>、*=、%，则他们按优先级（由低至高）的正确排列次序为：*=、>、% ( ×  ) 
9、C语言认为名为Student和student的变量是不同变量。 ( √  ) ,
10，while语句构成的循环不能用其他语句构成的循环来代替。(  √ ) 
11，参加位运算的数据可以是任何类型的数据。   ( ×  ) 
12、在C语言中，函数返回值的类型最终取决于return语句中表达式值的类型（× ）
13、一个C语言程序可以由多个程序文件组成。（ √）
14、C程序中所有函数之间都可以相互调用,与函数所在位置无关。（ × ）
15、在C程序中，函数既可以嵌套定义，也可以嵌套调用。   ( ×  ) 
16、静态变量和外部变量都是全局变量。                 (  × ) 
17、同一数组可以存储不同类型的值。           ( ×  ) 
18、若有语句：char *s1="string2";则语句strcpy("china",s1);是正确的。(×  ) 
19、C程序总是从main()函数的第一条语句开始执行的。    (√ ) 
20、在C程序中，赋值号（ = ）运算优先级别最低。      ( √ ) 
21、函数的形参可以是常量、变量或表达式。           ( × ) 
22、在定义二维数组时，可以将该数组的两个维数全部省略。 ( ×  ) 
23、字符串"The"小于字符串"the"。                  (  √ ) 
24、C语言程序的变量必须先定义再使用。   ( ×  ) 
25、如果x>y或者a<b为真，表达式（x>y&&a<b）就为真。( ×  ) 
26、for循环只能用于循环次数已经确定的场合。        ( ×  ) 
27、int *p=150;语法错误。                           ( √  ) 
28、C语言是一种结构化程序设计语言。                 (√   ) 
29、在switch-case语句中，不是每个case后都必须使用break语句，可以根据需要使用break语句。                                               (  √ ) 
30、C语言为所定义的数组在内存中分配一片连续的存储单元。(√   ) 
31、char str[50]; str="I am a student."; 是合法语句。          ( ×  ) 
32、_ya是不合法的C语言标识符。                   ( ×  ) 
33、若有定义：long int j,*p;则操作j=p;是合法操作。        ( ×  ) 
34、若有定义：double x[3][5]；则x数组中行下标的下限为0，列下标的上限为4 。(  √ ) 
35、宏替换不占用程序运行时间，只需编译时间。        ( √  ) 
36、Break语句用在循环体中，可使此循环结束。        ( ×  ) 
37、a-=7等价于a=a-7。                        ( √  ) 
38、若调用一个没有return语句的函数，则该函数也能返回一个用户所希望的函数值。( ×  ) 39、运算符/和%要求参加运算的对象均为整型数据。  (  × ) 
40、在C语言中，5种基本数据类型的存储空间长度的排列顺序为:char<int<long int <=float<double 。 ( √  ) 
41、若有定义和语句：
int a;
char c;
float f;
scanf("%d,%c,%f",&a,&c,&f);
若通过键盘输入：10 A 12 5
则a=10,c=‘A’,f=12.5。    (  √  )　　
42、若有定义：
char s[ ]＝"china"；
则V C系统为数组s开辟6个字节的内存单元。    (  √  )　　
43、若有定义和语句：
int a[3][3]＝{{3,5},{8,9},{12,35}},i,sum=0;
for(i=0;i<3;i++)
  sum+=a[i][2-i];
则sum=21。    (  √  )　

四、编程题
（1）百马百担问题：有100匹马，驮100担货，大马驮3担，中马驮2担，两匹小马驮1担，问大、中、小马各多少匹?
#include"stdio.h"
main( )
{
  Int  hb,hm,hl,n=0;
  for(hb=0;hb<=100;hb+=(1))
  for(hm=0;hm<=100-hb;hm+=(2))
    {
      hl=100-hb- (3) ;
      if(hb/3+hm/2+2*(3)==100)
      {
        n++;
        printf("hb=%d,hm=%d,hl=%d\n",hb/3,hm/2,2*hl);
      }
  }
  printf("n=%d\n",n);
}

（2）
  1 1 1 1 1 1 
   1 1 1 1 1 
     1 1 1
       1
#include"stdio.h"
void main()
{int k,i,j;
for(i=0;i<=4;i++)
{for(k=1;k<=i;k++)printf(" ");
for(j=0;j<7-i*2;j++)printf("1");
printf("\n");
}}

（3）

         1
      1 1 1
    1 1 1 1 1
  1 1 1 1 1 1 1
#include"stdio.h"
main()
{int k,j,i;
 for(i=1;i<=4;i++)
 {for(j=1;j<=4-i;j++)printf(" ");
  for(k=1;k<=2*i-1;k++)printf("1");
 printf("\n");
 }
}

(4) 3*3矩阵

#include<stdio.h>
int main()
{int array[3][3],sum;
int i,j;
for(i=0;i<3;i++)
{
	for(j=0;j<3;j++)
	{scanf("%d"<&array[i][j]);
	}
}
sum=array[0][0]+array[0][2]+array[1][1]+array[2][0]+array[2][2];
printf("%d\n",sum);
return 0;
}


（5）有一个已排好序的数组，输入一个数，要求按照顺序将它插入到数组中。

#include <stdio.h>
void main()
{
	int a[6]={1,3,5,7,9};
	int i,m,j;
	for (i=0;i<5;i++)
		printf("%5d",a[i]);
	printf("please input a digit;\n");
	scanf("%d",&m);
	a[5]=m;
	for(i=0;i<6;i++)
		for(j=0;j<=i;j++)
		{
			if(a[i]<a[j])
			{
				int t=a[i];
				a[i]=a[j];
				a[j]=t;
			}
		}
		printf("Now the :\n");
		for (i=0;i<6;i++)
			printf ("%d",a[i]);
		printf ("\n");
}


(9)   求s=1!+3!+5!…+19!的值，并将s输出。

#include<stdio.h>
main()
{
float sum=0,tmp=1;
int i;
for(i=1;i<=19;i++)
{
	tmp*=i;
	if(i%2)
		sum+=tmp;
}
printf("the number is:%f",sum);
}

(10). 编写程序，其中自定义一函数，用来判断一个整数是否为素数，在主函数中调用此函数并输出10~500的素数
#include <math.h>
#include  <stdio.h>
int IsPrimeNumber(int number)
{	int i;
	if (number <= 1)	
		return 0;
	for (i=2; i<sqrt(number); i++)
	{	if ((number % i) == 0)	
			return 0; 	}
	return 1;}
 void main()
{ int n;
  printf(“Please input n:”);
     for (i=100;i<500;i++)
{  if(IsPrimeNumber(i))
          { printf(" %5d",i);
				count++;
			}
			if(count==5)
			{
				printf("\n");
				count=0;
			}
       }
    }
 (11)
从键盘上输入a与n的值，计算sum=a+aa+aaa+aaaa的和


#include<stdio.h>
#include<iostream.h>
#include<string.h>
main()
{
int a;
int n;
int i;
int sum=0;//总数
int sum1;//前一个数字
printf("input two number:");
scanf("%d",&a);
scanf("%d",&n);
sum1=a;
for(i=2;i<=n;i++)
{
sum1=sum1*10+a;
sum=sum+sum1;
}
printf("the result is %d",sum);
}

(12)

   1
  222
 33333
4444444
Press any key to continue


#include "stdio.h"
const int N=4;
int main()
{
int i,j,k=1;
for(i=0;i<N;i++)
{
for(j=0;j<N-i-1;j++)
printf(" ");
for(j=0;j<2*i+1;j++)
printf("%d",k);
for(j=0;j<N-1-i;j++)
printf(" ");
printf("\n");
k++;
}
return 0;
}


(13)输入一行字符，分别统计出其中英文字母。空格数字和其他字符的个数

#include "stdio.h"
int main(void)
{char ch;
int char_num=0,kongge_num=0,int_num=0,other_num=0;
while((ch=getchar())!='\n')
{if(ch>='a'&&ch<='z'||ch<='z'&&ch>='a')
{
char_num++;
}
else if(ch==' ')
{
kongge_num++;
}
else if(ch>='0'&&ch<='9')
{
int_num++;
}
else
{
other_num++;}
}
printf("字母=%d,空格=%d,数字=%d,其他=%d\n",char_num,kongge_num,int_num,other_num);
return 0;
}

(14)编程实现用选择法对10个随机整数排序

#include<stdio.h>
int main()
{
	int i,j,min,temp,a[11];
	printf("enter data:\n");
	for (i=1;i<=10;i++)
	{
		printf("a[%d]=",i);
		scanf("%d",&a[i]);//输入10个数
	}
	printf("\n");
	printf("the orginal numbers:\n");
	for(i=1;i<=10;i++)
		printf("%5d",a[i]);//输出这10个数
	printf("\n");//以下8行是对这10个数排序
	for(i=1;i<=9;i++)
	{
		min=i;
		for(j=i+1;j<=10;j++)
			if (a[min]>a[j])min=j;
			temp=a[i];//以下3行将a[i+1]~a[10]中最小值与a[i]对换
			a[i]=a[min];
			a[min]=temp;
	}
	printf("\n the sorted numbers:\n");//输出已排好序的10个数
	for(i=1;i<=10;i++)
		printf("%5d",a[i]);
	printf("\n");
	return 0;
}
(15)有一头母牛，它每年年初生一头小母牛，每头小母牛从第四个年头起，每年年初
也生一头小母牛，编写程序，求第20年时，共有多少头牛。

#include<stdio.h>
int cattle(int n)
{
if(n<4)
return 1;
else
return(cattle(n-1)+cattle(n-3));
}
int main()
{
int n,m;
printf("请输入一个正整数:\n");
scanf("%d",&n);
m=cattle(n);
printf("第%d年共有%d头牛!\n",n,m);
return 0;
}

(16)编写程序，随机生成10个1~100之间的整数，输出其中的最大数和最小数.
#include"stdio.h"
main()
{
	int a,b,c,t;
    printf("input a<=100,b<=100,c<=100,");scanf("%d%d%d",&a,&b,&c);
    printf("a=%d,b=%d,c=%d\n",a,b,c);
    if(a>b)
	{t=a;a=b;b=t;}
	if(a>c)
	{t=a;a=c;c=t;}
	if(b>c)
	{t=b;b=c;c=t;}
	printf("min=%d,max=%d\n",a,c);
} 
(17)   4444444
        33333
         222
          1
 解：#include<stdio.h>
void main()
{int i,k,l;
for(i=4;i>0;i--)
{for(k=0;k<4-i;k++)printf(" ");

for(l=1;l<i*2;l++)printf("%d",i);
printf("\n");
}
}
(18)、输出一个3×5矩阵每行的平均值（元素为1~100的随机整数）。
#include<stdio.h>
#include<stdlib.h>
main()
{int i,j,a[3][5],sum;
for(i=0;i<3;i++)
{ printf("\n");
for (j=0;j<5;j++)
{a[i][j]=1+rand()%100;
printf("%4d",a[i][j]);}}
for(i=0;i<3;i++)
sum=0;
for (j=0;j<5;j++)
{sum=sum+a[i][j];}
printf("\ni=%d,ave=%d\n",i,sum/5);
}
  42  68  35   1  70
  25  79  59  63  65
   6  46  82  28  62

19、已知函数y=f(x)，编程实现输入一个x值，输出y值。
                   2x+1   (x<0)
             y=    0     (x=0) 
                   2x-1  (x>0) 
  
#include <stdio.h>
void main()
{ int x,y;
scanf(“%d”,&x);
if(x<0) y=2*x+1;
else if(x>0) y=2*x-1;
else  y=0;
printf(“%d”,y);
}
20.从键盘上输入一个百分制成绩score，按下列原则输出其等级：score≥90，等级为A；80≤score<90，等级为B；70≤score<80，等级为C；60≤score<70，等级为D；score<60，等级为E。
 #include <stdio.h>
void main(){
	int    data;          
	char  grade;                    
	printf("Please enter the score:");
	scanf("%d”, &data);  
	switch(data/10)                   
	{   case 10:  
       case 9 :  grade=’A’;  break; 
		case 8:  grade=’B’;	  break;
		case 7:  grade=’C’;	  break;
       case 6:  grade=’D’;	  break; 
		default:  grade=’E’;
	}
    printf("the grade is %c”,grade);
}
21．从键盘输入两个数，求出其最大值（要求使用函数完成求最大值，并在主函数中调用该函数）     
#include <stdio.h>
float max(float x,float y);
void main()
{  float a,b,m;
scanf("%f,%f",&a,&b);
m=max(a,b);
printf("Max is %f\n",m);
}
float max(float x,float y)
{
if (x>=y) 
  return x;
else
return y;
}


22、从键盘输入n个数存放在数组中，将最小值与第一个数交换，输出交换后的n个数。
#include <stdio.h>
int main(void){
      int i,n,iIndex,temp;
	  int a[10];
      printf("Enter n: ");
	  scanf("%d", &n);
      printf("Enter %d integers:\n ");
        for(i=0;i<n;i++)
	      scanf("%d", &a[i]);
	  iIndex=0;
      for(i=1;i<n;i++){
		 if(a[i]<a[iIndex])   	iIndex=i;
	   }
     temp=a[0];a[0]=a[iIndex];a[iIndex]=temp;
     for(i=0;i<n;i++)
	   printf("%5d", a[i]);
	 printf("\n");
     return 0;
}    


第二种解法 利用函数
#include<stdio.h>

int comp(int arry[], int n)
{
	int i,index,temp;
	printf("为数组赋值：\n");
	for(i=0;i<n;i++)
	{		scanf("%d",&arry[i]);
	}
	for(i=1,index=0;i<=n-1;i++)
	{	if(arry[i]<arry[index])
		{	index=i;
		}
	}
	temp=arry[0];arry[0]=arry[index];arry[index]=temp;
	for(i=0;i<n;i++)
		{			printf("%d  ",arry[i]);			
		}
	return 0;
}
main()
{	int n;
	int a[10];
	printf("为n赋值：\n");
	scanf("%d",&n);
	comp(a,n);}
23、用指针方法编写一个程序，输入3个整数，将它们按由小到大的顺序输出.
 
#include <stdio.h> 
void swap(int *pa,int *pb) 
{  
int temp; 
temp = *pa; 
*pa = *pb; 
*pb = temp; 
} 
void main() 
{ 
int a,b,c,temp;  
scanf("%d%d%d",&a,&b,&c); 
if(a>b) 
swap(&a,&b); 
if(b>c)  
swap(&b,&c); 
if(a>c) 
swap(&a,&c); 
printf("%d,%d,%d",a,b,c); 
}
24、编程输入一行文字，找出其中的大写字母，小写字母，空格，数字，及 其他字符的个数 .
#include<stdio.h> 
 void main() 
 {   int a=0,b=0,c=0,d=0,e=0,i=0;  
char *p,s[20];   
while((s[i]=getchar())!='\n')
i++;  
p=s;   
while(*p!=10) 
 {   if(*p>='A'&&*p<='Z')  a++; 
  else if(*p>='a'&&*p<='z')  b++;  
 else if(*p==' ')  c++;   e
lse if(*p>='0'&&*p<='9')  d++;  
 else e++;  p++;  }  
 printf("大写字母 %d 小写字母 %d\n",a,b);   printf("空格 %d 数字 %d 非字符 %d\n",c,d,e); }
25、编写一个函数（参数用指针）将一个3×3矩阵转置。
#include <stdio.h>
int main()
{void move(int *pointer);
 int a[3][3],*p,i;
 printf("input matrix:\n");
 for (i=0;i<3;i++)
   scanf("%d %d %d",&a[i][0],&a[i][1],&a[i][2]);
 p=&a[0][0];
 move(p);
 printf("Now,matrix:\n");
 for (i=0;i<3;i++)
   printf("%d %d %d\n",a[i][0],a[i][1],a[i][2]);
 return 0;
  }

 void move(int *pointer)
  {int i,j,t;
   for (i=0;i<3;i++)
     for (j=i;j<3;j++)
       {t=*(pointer+3*i+j);
        *(pointer+3*i+j)=*(pointer+3*j+i);
        *(pointer+3*j+i)=t;
       }
  }
选择：

26、求三个数的最大数。
#include<stdio.h>
main()
{int a,b,c,max;
scanf("%d%d%d",&a,&b,&c);
if(a>b) max=a;
else    max=b;
if(max<c)  c=mac;
printf("max=%d",max);
}

27、输入三个数，按从小到大顺序输出。

#include<stdio.h>
main()
{int a,b,c,t;
scanf("%d%d%d",&a,&b,&c);
if(a>b) {t=a;a=b;b=t;}
if(a>c) {t=a;a=c;c=t;}
if(b>c) {t=b;b=c;c=t;}
printf("%d,%d,%d",a,b,c);
}

数列：

28、求数列：s=1-3+5-7...+99

#include<stdio.h>
main()

{   int i,sign=1,s=0;
	for(i=1;i<100;i++)
         {
	  s+=i*sign;                    //sign变号。
	  sign=-sign;
	 }
    printf("s=%d\n",s);

}

29、求数列：s=1!+2!+3!+...+10!

#include<stdio.h>
main()

{   int i,p=1,s=0;
   	for(i=1;i<=10;i++)
	{
	  p=p*i;                      
	  s=s+p;
	}
    printf("s=%d\n",s);
}

循环、数组

31、素数判断

#include<stdio.h>
main()

{   int i,k;
    scanf("%d",&k);
	for(i=2;i<=k-1;i++)
	if(k%i==0)  break;              
	if(i>=k)        printf("%d is su shu!\n",k);
          else          printf("%d no su shu!\n",k);

}


32、求200以内素数
#include<stdio.h>
main()

{   int i,k;
    for(k=3;k<=200;k+=2)
      {
	for(i=2;i<=k-1;i++)
	    if(k%i==0)  break;
	if(i>=k)        printf("%5d",k);
      }
}

33、求水仙花数：是指一个3位数，其各位数字的立方和等于该数本身。如：153=13+53+33
#include<stdio.h>
main()

{   int i,g,s,b;
    for(i=101;i<1000;i++)
	{
	 g=i%10;	                
	s=i/10%10;
                b=i/100;
	if(i==g*g*g+s*s*s+b*b*b)
	           printf("%5d  ",i);
	}	   
}


34、输入一行字符，统计其中字母、数字、空格及其他字符的个数。

#include <stdio.h>
int main()
 {
  char c;
  int letters=0,space=0,digit=0,other=0;
  printf("请输入一行字符:\n");
  while((c=getchar())!='\n')                     // 输入一行字符。
   {
     if (c>='a' && c<='z' || c>='A' && c<='Z')
    	letters++;
     else if (c==' ')
	    space++;
     else if (c>='0' && c<='9')
	    digit++;
     else
	    other++;
    }
   printf("字母数:%d\n空格数:%d\n数字数:%d\n其它字符数:%d\n",letters,space,digit,other);
   return 0;
  }

35、输出一个*号的菱形图案。

#include <stdio.h> 
int main()
 {int i,j,k;
  for (i=0;i<=3;i++)                          
   {
     for (j=0;j<=2-i;j++)    printf(" ");     
     for (k=0;k<=2*i;k++)    printf("*");    
    printf("\n");
   }

  for (i=0;i<=2;i++)                        
   {
     for (j=0;j<=i;j++)      printf(" ");
     for (k=0;k<=4-2*i;k++)  printf("*");
    printf("\n");
   }
  }


36、给数组赋值0~9的随机数，输出该数组中的最大值及位置。

#include<stdio.h>
#include<stdlib.h>
main()
{
int i,max,k,a[10];
for(i=0;i<10;i++)                   
a[i]=rand()%10;           
max=a[0];
for(i=0;i<10;i++)
if(a[i]>max) { max=a[i];  k=i;}
printf("\nmax=%d,k=%d\n",max,k);
}

37、将一个数组元素逆序排放。

#include <stdio.h>
main()
{ int a[10],i,t;
  for (i=0;i<10;i++)
    scanf("%d",&a[i]);      
  for (i=0;i<10/2;i++)          
    { t=a[i];a[i]=a[10-i-1];a[10-i-1]=t;}
  for (i=0;i<10;i++)          
    printf("%4d",a[i]);
  printf("\n");
 }   

38、选择法排序

#include <stdio.h>
main()                      
{
int i,j,t,a[10]={5,0,3,1,8,7,4,2,6,9};
  for (i=0;i<=9;i++)       
   for (j=i+1;j<=9;j++)
     if (a[i]>a[j])  {t=a[i];a[i]=a[j];a[j]=t;}
  for (i=0;i<=9;i++)
    printf("%5d",a[i]);
  printf("\n");
 }

39、冒泡法排序。
#include<stdio.h>
main()
{
int a[10];
int i,j,t;
printf("input 10 numbers :\n");
for(i=0;i<10;i++)
  scanf("%d",&a[i]);
printf("\n");
for(j=0;j<9;j++)
 for(i=0;i<9-j;i++)
	  if(a[i]>a[i+1])
	  {t=a[i];a[i]=a[i+1];a[i+1]=t;}
printf("the sorted numbers :\n");
for(i=0;i<10;i++)
  printf("%5d",a[i]);
printf("\n");
}

40、10个元素数组，删除其中一个元素。

#include <stdio.h>
main()                      
{int i,k,a[10];
  for (i=0;i<=9;i++)
    scanf("%d",&a[i]);     
  printf("删除第几个元素:\n");
  scanf("%d",&k);

  for (i=k;i<=9;i++)       
   a[i]=a[i+1];
  for (i=0;i<=8;i++)        
    printf("%5d",a[i]);
  printf("\n");
 }

41、将一个排好序的数组，插入一个数后，保持数组原排序顺序。
#include <stdio.h>
main()
{ int a[11]={1,4,6,9,13,16,19,28,36,39};
  int t1,t2,num,i,j;
  printf("请输入要插入的数据: ");
  scanf("%d",&num);
  if (num>a[9])
    a[10]=num;
  else
   {
	  for (i=0;i<11;i++)
    {
	  if (a[i]>num)
       {
	     t1=a[i];a[i]=num;                  // 插入新数据，同时保存原数据
	     for (j=i+1;j<11;j++)           
		 {t2=a[j];a[j]=t1;t1=t2;}       // 从该位置开始，其后数据依次后移一位。
	     break;
       }
    }
  }
  printf("处理后数组为:\n");
  for (i=0;i<11;i++)
    printf("%5d",a[i]);
  printf("\n");
 }


42、二维数组对角线

#include <stdio.h>
main()
{
	int i,j,s1=0,s2=0,a[3][3]={1,2,3,4,5,6,7,8,9};
	for(i=0;i<3;i++)
	for(j=0;j<3;j++)
	printf("%5d",a[i][j]);
	printf("\n");

    for(i=0;i<3;i++)
	for(j=0;j<3;j++)
	{
	    if(i==j)   s1=s1+a[i][j];
	    if(i+j==2) s2=s2+a[i][j];
	
	}
	printf("s1=%d,s2=%d\n",s1,s2);
}

43、求1980年---2016年间的闰年。

#include<stdio.h>
main()

{   int year;
    for(year=1980;year<=2016;year++)
	if((year%4==0&&year%100!=0)||(year%400==0))
		printf("%8d",year);
}


44、求2个数的最大公约数、最小公倍数。
#include<stdio.h>
main()
{ 
  int  a,b,t,i;
  scanf("%d,%d",&a,&b);
  if(a<b)                     
   {  t=a;  a=b;  b=t; }

  for(i=b;i>=0;i--)  
	  if(a%i==0&&b%i==0)  break;   
  
 printf("最大公约数是:%d\n最小公倍数是:%d\n",i,a*b/i);
}

45、求出100至1000之内能同时被2、3、7整除的整数，并输出。
#include <stdio.h>
void main()
{ int i;
  for (i = 100; i <= 1000; i++)
    { if (i%2==0 && i%3==0 && i%7==0)
      printf("%d\n",i);  
    }
}
46、输入圆的半径，求圆的周长和面积。 要求定义圆周率为如下宏常量 #define PI 3.14159 
输入：输入半径r的值，为一实数。 
输出：输出一行，包括周长和面积。数据之间用一个空格隔开，数据保留小数后面两位。
#include<stdio.h>
# define Pl 3.14159
int main()
{
int r;
scanf("%d",&r);
double c,s;
c=2*r*Pl;
s=Pl*r*r;
printf("%.2f %.2f\n",c,s);
return 0;
}
47，输入一个整数n，输出数列1+1/3+1/5+……前n项的和。 
输入：输入只有一个正整数n。 
输出：结果保留2位小数，单独占一行
#include<stdio.h>
int main()
{
int i,n;
double s = 0;
scanf("%d",&n);
for(i = 1;i <= n;i ++)
{
 s+= 1.0/(2*i-1);

}
printf("%.2f",s);
return 0;

}
48，随机产生10个数(1~100)存入一维数组a中，求这10数中的最大数并输出。
#include<stdio.h>
#include<stdlib.h>
main()
{
int i,max,a[10];
for(i=0;i<10;i++)                   
a[i]=rand()%100+1;           
max=a[0];
for(i=0;i<10;i++)
if(a[i]>max) 
{ max=a[i]; }
printf("%d\n",max);
}
49、编写完整程序。编写函数fun(结构如下)，其功能是：将两个两位数的正整数a、b合并形成一个整数放在c中。合并的方式是：
将a数的十位和个位数依次放在c数的千位和十位上，b数的十位和个位数依次放在c数的个位和百位上，其它功能在主函数实现。
如主函数中输入a、b的值，调用fun函数得到一个合并后的值。
int fun(int a,int b)
{
    //实现两个数的合并
}
运行示例：(要求输入输出按运行示例格式实现)
输入：45 12 
输出：4251
#include <stdio.h>
int fun(int a,int b)
{ int c=0,a10,a1,b10,b1;
  a10=a/10;
  a1=a%10;
  b10=b/10;
  b1=b%10;
c=b10+b1*100+a10*1000+a1*10;
return c;
}
 main()
{
   int a,b,c;
	scanf("%d%d",&a,&b);
	c=fun(a,b);
  printf("%d\n",c);
  }
50、给定A(x1, y1), B(x2, y2)两点坐标，计算它们间的距离。 
输入：输入包含四个实数x1, y1, x2, y2，分别用空格隔开，含义如描述。其中0≤x1,x2,y1,y2≤100。 
输出：输出占一行，包含一个实数d，表示A, B两点间的距离。结果保留两位小数。
#include <stdio.h> 
#include <math.h> 
int main()
{ double x1,y1,x2,y2,dx,dy,d;
  scanf("%lf %lf %lf %lf",&x1,&y1,&x2,&y2);   
    dx=x1-x2; 
    dy=y1-y2; 
    d=sqrt(dx*dx+dy*dy); 
    printf("%.2lf\n",d); 
    return 0; 
}
51、编写程序，随机生成10个1~100之间的整数，输出其中的最小数。
#include<stdio.h>
#include<stdlib.h>
main()
{
int i,min,a[10];
for(i=0;i<10;i++)                   
a[i]=rand()%100+1;           
min=a[0];
for(i=0;i<10;i++)
if(a[i]<min) 
{ min=a[i]; }
printf("%d\n",min);
}
52.马上要举办新生程序设计竞赛了，与以往不同的是，本次比赛以班为单位，为了全面衡量一个班级的整体水平，
要求从一个班的m位同学中任选k位同学代表本班参加比赛，问有多少种组合方案。显然，这个组合数是m!/(k!*(m-k)!)。
int fact(int n) 
 { 
    //函数返回值为n的阶乘。 
}    
（1）在主函数里输入两个正整数m,k，k<=m<=12；
（2）编写函数fact()，实现求一个数的阶乘功能；
（3）在主函数中调用此函数，输出一个整数，即组合方案数。
运行示例：(要求输入输出按运行示例格式实现)
输入：5 3
输出：10
#include<stdio.h>
#include<stdlib.h>
int fact(int n)
{int s=1;
for(int i=1;i<=n;i++)
 s=i*s;
 return s;
 } 
 int main()
 {int m,k,s;
scanf("%d %d",&m,&k);
 s=fact(m)/(fact(k)*fact(m-k));
 printf("%d\n",s);
 }
52、编程实现，从键盘输入一个正整数，判定是否同时被3,5,7整除。如果是输出yes不是输出no。
#include<stdio.h>
int main()
{
    int n;
    scanf("%d",&n);
    if((n%3 == 0)&&(n%5 == 0)&&(n%7 == 0)){
        printf("yes\n");
    }
    else{
        printf("no\n");
    }
}
53、设计函数统计数组a[10]中下标和数组元素的值都是偶数的元素个数，结果在主函数中输出
#include <stdio.h>
int main()
{ int i,s=0,a[10];
printf("输入数组元素") ;
  for (i=0;i<10;i++)
    scanf("%d",&a[i]);      
  for (i=0;i<10;i++)          
    { 
	if((i%2==0&&a[i]%2==0)) 
	s++;    } 
	printf("满足条件的数据个数");
  printf("%d\n",s);
  return 0;
 } 
54，编写程序，输入三个数，求出其中的最大值
#include<stdio.h>
int main()
{
int a,b,c;
scanf("%d%d%d",&a,&b,&c);
if(a>=b&&a>=c)
printf("%d",a);
else 
if(b>=c)
printf("%d",b);
else 
printf("%d",c);
}
54、从键盘上输入两个正整数m和n，求最大公约数
#include<stdio.h>
 int main()
 {int m,n,s;
 scanf("%d%d",&m,&n);
 do
 {s=m%n;
 m=n;
 n=s;
 }while(s!=0);
 printf("%d\n",m);
 }
56、用函数实现求均值问题。请编写一个函数fun(结构如下)，它的功能是：计算n门课程的平均分，计算结果作为函数值返回给主函数。
例如：若有5门课程的成绩是：90，72，80，61，55，则函数的值为71.6。
double fun(int a[],int n)
{
//求数组a的平均值
}
#include <stdio.h>
double fun(int a[],int n)
{ int s=0,i;
float c;
  for(i=0;i<n;i++)
    s=s+a[i];
    c=s*1.0/n;
    return c;
}
int main()
{
int a[]={90,72,80,61,55},n=5;
	float c;
	c=fun(a,n);
  printf("%.1f\n",c);
  }
57、春天是鲜花的季节，水仙花就是其中最迷人的代表，数学上有个水仙花数，他是这样定义的：
“水仙花数”是指一个三位数，它的各位数字的立方和等于其本身。现在要求输出所有在m和n范围内的水仙花数。  
要求定义一个narcissus()函数判断一个整数n是否为水仙花数，其余功能在main()函数中实现，narcissus()函数的结构如下： 
int narcissus(int n) 
{ 
  //判断n是否为水仙花数， 若是函数返回1，否则返回0。
} 
输入输出说明：
输入数据有多组，每组占一行，包括两个整数m和n（100<=m<=n<=999）。
输出对于每个测试实例，要求输出所有在给定范围内的水仙花数，就是说，输出的水仙花数必须大于等于m,并且小于等于n，如果有多个，则要求从小到大排列在一行内输出，之间用一个空格隔开;如果给定的范围内不存在水仙花数，则输出no;每个测试实例的输出占一行。 
运行示例：(要求输入输出按运行示例格式实现)
输入：
100 120
300 380
输出：
no
370 371
#include<stdio.h>
int narcissus(int n)
{
	int g,s,b,t;
	g=n%10;
	s=n/10%10;
	b=n/100;
	t=g*g*g+b*b*b+s*s*s;
	if(t==n)
	return 1;
	else return 0;
}
 int main()
 {int i,m,n,s,flag=0;
 scanf("%d%d",&m,&n);
 for(i=m;i<=n;i++)
 {s=narcissus(i);
 if(s==1) 
{
printf("%d ",i);
 flag=1;}
 }
if(flag!=1)
printf("no");
 }
58.编写程序，打印在所有三位数中，其个位，十位，百位上的数码相加等于21的数
#include<stdio.h>
int main()
{
int i,g,s,b,t=0;
for(i=100;i<=999;i++)
{  
	g=i%100%10;
	s=i%100/10;
	b=i/100;
	t=g+s+b; 
if(t==21){
	printf("%d\n",i);
} }
return 0;
}
59,编写程序，输出下列三角形(用双重循环实现)：
                1 1 1 1 1 1 1  
                  2 2 2 2 2
                    3 3 3 
                      4
#include<stdio.h>
int main()
{int i,j,l,k=4;
for(i=1;i<=4;i++)
{for(j=1;j<i;j++)
printf(" ");
for(l=1;l<2*(4+1-i);l++)
printf("%d",i);
printf("\n");
}
}
60、用函数实现求最大值问题。请编写一个函数fun(结构如下)，它的功能是：计算n门课程的最高分，计算结果作为函数值返回给主函数。
例如：若有5门课程的成绩是：90，92，80，61，55，则函数的值为92。
double fun(int a[],int n)
{
//求数组a的最大值
}
#include<stdio.h>
double fun(int a[],int n)
{
    int b = 0;
    for (int i = 0; i < n; i++)
        if (b < a[i]) 
            b = a[i];
    return b;
}
int main()
{
int a[]={90,92,80,61,55};
double max;
max=fun(a,4);
printf("%.f",max); 
}
61、编写程序，实现以下成绩处理功能：
（1）输入10个成绩（整数类型，数组名记为a） ；
（2）计算并输出最高分（记为Max）、最低分（记为Min）与成绩中值（记为Midd），其中成绩中值为最高分与最低分的平均值（保留一位小数输出）；
（3）将Midd及以上的成绩归为A档，Midd以下的成绩归为B档，统计并输出A、B两档的人数。
要求最大值、最小值分别用函数max、min函数实现，其它功能在主函数中实现，max、min的结构如下：
int max(int a[])
{
//求数组a的最大值。
}
int min(int a[])
{
//求数组a的最小值。
}
运行示例：(要求输入输出按运行示例格式实现)
输入：88 59 50 74 60 99 75 90 68 70
输出：Max=99, Min=50, Midd=74.5, A=4, B=6
#include<stdio.h>
int main()
{
    int i,a[10],max,min,A=0,B=0;
    float midd;
    for(i=0;i<10;i++)
    scanf("%d",&a[i]);
    max=a[0];
    min=a[0];
    for(i=1;i<10;i++)
    {
    	if(a[i]>max) max=a[i];
    	else if(a[i]<min) min=a[i];
	}
	midd=(float)(max+min)/2;
	for(i=0;i<10;i++)
	{
		if(a[i]>midd) A++;
		else   B++;
	}
	printf("max=%d,min=%d,midd=%.1f,A=%d,B=%d\n",max,min,midd,A,B);
	}
    
62、编程实现用选择法对10个1~100之间的随机整数排序
#include <stdio.h>
#include <stdlib.h>
#include<time.h>
int main (void)
{
srand(time(0));
int a[10],n=10,i,j,k,temp;
for (i=0;i<10;i++)
a[i]=rand()%100+1;
for(i=0;i<n-1;i++)
{
k=i;
for(j=i+1;j<n;j++)
if(a[k]>a[j]) k=j;
if(i!=k)
{
temp=a[i];
a[i]=a[k];
a[k]=temp;
}
}
for (i=0;i<10;i++)
printf ("%d\n",a[i]);
return 0;
}
63、编程要求:请按题中的功能要求，编写程序并能得到正确的结果。
功能说明:编写程序，通过以下步骤验证个正整数是否符合特定的规则:
(1)输入一个4位正整数n， 将n分拆成a与b， a为n的低2位， b为n的高2位;
(2) 计算a的所有因子之积，记为s (当1≤i<a时，如果a是i的倍数，则是a的因子);(3)如果s的低2位等于b,则输出"Yes"， 否则输出"No";输出格式参见以下示例。运行示例:输入: 4412
输出: 12: 1*2*3*4*6-144, Yes
说明:输入数为4412 (对应n)分拆为12 (对应a)和44 (对应b)，12的因子为1、 2、3、4和6，累乘值为144 (对应s), s的低2位和b相等，输出"Yes"。
#include<stdio.h>
int main()
{   int n,a,b;
    int i,j=0;
   int str[100],sum=1,x;
   scanf ("%d", &n);
   a=n%100;
   b=n/100;
for(i=1;i<a;i++)
    if(a%i==0)
    str[j++]=i;
for(i=0;i<j;i++)
     sum=sum*str[i];
      x=sum%100;
    printf("%d:" ,a);
	for(i=0;i<j;i++)
	{ if(i==0)
     printf("%d", str[i]) ;
	 else 
      printf("*%d",str[i]);
	  }    
	  printf("=%d",sum) ;
printf("%s\n",(x==b)?"YES":"N0");
}
64，编程实现:读入两个整数及一个字符类型的运算符（可为+,-,*,/），根据输入的运算符操作两个整数,输出相应的结果.
#include<stdio.h>
int main()
{  int  a,b;
   char c;
   scanf("%d %d %c",&a , &b,&c);
   switch(c){
   case'+':printf("%d\n",a+b);break;
   case'-':printf("%d\n",a-b);break;
   case'*':printf("%dn",a*b);break;
   case'/':if(b==0)
      printf("除数不能为0！");
	  else
       printf("%f\n",a*1.0/b);break;
       case'%':printf("%d\n",a%b);break; 
      default:break ;
	  }
	  return 0;
}

65 输入一个整数n和个整数，输出这n个整数的和，
输入:输入有两行:第一行是一个正整数n.第二行是n个整数。
输出:输出一个整数，即n个数的和。输出单独占一行.
运行示例:(要求输入输出按运行示例格式实现)
输入：
3
7 3 2
输出:12
#include<stdio.h>
int main()
{  int i,n,x,s=0;
     scanf("%d",&n);
    for(i=0;i<n;i++)
    {  
	scanf("%d",&x);
      s+=x;
	  }
    printf("%d\n",s);
	return  0;
}
66.编写程序 ，通过以下步骤验正一个正整数是否符合特定的规则:
（1）输入一个位正整数n，将n为拆为a和b两部分；a为n的低3位，b为n的最高位。
（2）计算a的所有因子之和s（当1<=i<a时，如果a是i的倍数，则i是a的因子)
(3)如果s的个位数等于b，则输出“Pass”否则输出“Fail”
要求定义一个sum判断并输出a的因子及统计所有因子之和，其它功能在主函数中实现，sum结构如下:
int sum(int a)
{
判定并输出a的y因子及统计的所有因子之和
}
运行示例，要求输入输出安运行示例格式实现)
输入:1164
输出：164:1+2+4+41+82=130，Fail
#include<stdio.h>
int main( )
{ int a,b,i,n,s=0;
  printf("输入一个四位数: ");
  scanf("%d",&n) ;
  a=n%1000;
  b=n/1000;
   printf("%d:",a);
    for(i=1;i<a;i++)
   {if(a%i==0)
   {
   if(i==1)
   printf("%d",i);
   else
   printf("+%d",i);
   s+=i;
   }
   }
   printf("=%d",s);
   if(s%10==b)
   printf("pass\n");
   else 
   printf(",fail\n");
}
67,输出一个3×5矩阵每行的平均值
#include <stdio.h>
double av(double a[3][5])
{int i,j;
 double s=0;
 for(i=0;i<3;i++)
   for(j=0;j<5;j++)
     s+=a[i][j];
 return s/(3*5);    
}
int main()
{double a[3][5];
 int i,j;
 for(i=0;i<3;i++)
   for(j=0;j<5;j++)
     scanf("%lf",&a[i][j]);
 printf("avg=%.2lf",av(a));
 return 0;
}




