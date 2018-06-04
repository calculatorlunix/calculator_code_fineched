!/bin/bash
#! this file is writting by jamal roger,zakaria,anass | ESTSB

#!simple caculator

plus (){ echo "$rep+=$1" |bc ;}

calc  (){ echo "$(($1))" ;}

#!calculator functions

fcal  (){ echo "$1($2)" | bc -l ;}

#1calculator bainire

tobase (){ echo "obase=$1;ibase=$2;$3"|bc -l;}

#!factriel

fact (){ echo  "define fct(a){ if(a<=1) return 1;return a*fct(a-1);} fct($1);"|bc -l ;}

#!fibonachii

fibo (){ echo  "define fb(a){ if(a<=2) return 1; return fb(a-1)+fb(a-2);} fb($1);" |bc -l ;}
#! print n to m 

printab (){ echo  "for(i=$1;i<=$2;i++) i;"|bc -l ;}
printba (){ echo  "for(i=$1;i>=$2;i--) i;"|bc -l ;}


#!power

pow (){ echo  "define pw(a,n){ if(n==0) return 1; return a*pw(a,n-1);} pw($1,$2);" |bc -l ;}

#!end_f

#!menu/of/calcule

menu(){

echo -e "\e[39m >>to calclater simpe use calc <expression> ex:calc 1+3 \e[0m"
echo -e "\e[32m >>for cos or sin or any others function use fcal *fc <exp>\e[0m"
echo -e "\e[31m  >>for *fc we have"
echo -e " \e[36m   *fc=s:sin\e[0m"
echo -e " \e[36m   *fc=c:cos\e[0m"
echo -e " \e[36m   *fc=e:exp\e[0m"
echo -e " \e[36m   *fc=l:lin\e[0m"
echo -e " \e[36m   *fc=a:atang\e[0m"
echo -e " \e[36m   *fc=sqrt\e[0m"
echo -e " \e[95m>>convert to any base just tobase *base courrent_base  number\e[0m"
echo -e " \e[96m>>for power just write  pow <base> <power> exp : pow 3 2 = 9\e[0m"
echo -e " \e[90m>>for factoriel or fibonnachi just fact <number> or fibo <number>\e[0m"
echo -e " \e[32m>>to print all number bettwen a and b just write printab a b exp printab 1 10 a<b\e[0m"
echo -e " \e[93m>>to print all number bettwen a and b just write printba b a exp printba 1 10 b>a\e[0m"
echo -e " \e[94m>>for show menu *menu\e[0m"
echo -e " \e[95m>>to exit  *out\e[0m"



}

#!end_menu



echo -e "       \e[31m========= << caculatrice v0.0.0 | ESTSB >> ==========\e[0m"
 

menu

#boucle/while/main/of/use/interface



while [ "$rep" != "out" ]


do



    read -p "cal-ESTSB>>>" rep

      $rep

done



