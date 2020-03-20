int main()
{
  char password[32]
  int i=3;
  do{
      printf("请输入密码：（还有%d次机会）",i);
      scanf("%s",&passsword);
  if(0==strcmp(password,"666"))
{
  printf("密码输入正确！\n");
  break;
}
  else
{
 printf("密码输入错误，请重新输入！\n")；
i--;
} 
}while(i>0);
getch();
return 0;
}
