#include<stdio.h>
#include<stdio.h>
int main(){
    char a[100];
printf("Enter the expression\n");
gets(a);
int n=strlen(a);

for(int i=0;i<n;i++){

    if(a[i]>='a'&&a[i]<='z'||a[i]>='A'&&a[i]<='Z'){
            printf("%c is an Identifier\n",a[i]);
    }
    else if(a[i]>='0'&&a[i]<='9'){
            printf("% c is an Number\n",a[i]);
    }
    else if(a[i]=='='){
        printf("%c is an Assignment Operator\n",a[i]);
    }
    else if(a[i]=='+'||a[i]=='-'||a[i]=='*'||a[i]=='%'||a[i]=='/'){
        printf("%c is an Arithmetic operator\n",a[i]);
    }
}
return 0;
}
