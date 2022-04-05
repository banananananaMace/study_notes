# study_notes
1、pointer_func.c 关于函数指针和指针函数的一些理解；
	typedef int (*method_1)();
	typedef int (*method_2)(int, int);
	typedef int (*method_3)(int a, int b);
	typedef int *(*method_4)(int, int);
	其中:	method为类型，用于定义变量;
		int / int * 为返回值类型;
		method_1 定义的变量入参无限制;
		其余定义的变量入参必须为int，个数为2;

