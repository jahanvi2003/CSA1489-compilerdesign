%{
int c=0;
%}
%%
"//"[a-z]+|"/*"[a-z]+ {c++;printf("\n %s is a comment line\n",yytext);}
.+ {printf("the given input is not comment line");}
%%
int yywrap( ){}
int main()
{
printf("enter:");
yylex( );
printf("The number of comment lines=%d\n",c);
return 0;
}
