# C-problem1
	
  int i=8;
	printf("%d,%d,%d,%d\n",++i,--i,i++,i--);

i=8;
temp0=i; //temp0=8;
i--;     //7
temp1=i; //temp1=7
i++;     //8
--i;     //7
++i;     //i=8
printf("%d,%d,%d,%d",i,i,temp1,temp0);     
