# swap-even-and-odd-char
void main()
{
char s[20],tmp;
int i,j;
scanf("%s',&s);
for(i=0;i<strlen(s);i+=2)
{
tmp=s[i+1];
s[i]=str[i+1];
s[i+1]=tmp;
}
printf(str);
}
