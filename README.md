# REPOALEX12.12.2022

String name='kerime';
System.debug(name);

//+=
name='New Name : '+name+' ' +'alici';
System.debug(name);

Integer x=15;
System.debug(x);
x+=16;
System.debug(x);
x-=10;
System.debug(x);
x*=2;
System.debug(x);
x/=3;
System.debug(x);

String numberResult;
numberResult=x<34?'numberResult 34 ten kucuk':'numberResult 34 ten buyuk';
System.debug(numberResult);
//Integer y=28;
//System.debug(y);
//y+=9;

//Integer z=28;
//z=y<45 ? 10 : 0;
//System.debug('number:'+z);


Boolean isDeveloper= true;
Boolean isConsultant= false;

System.debug('Both isDeveloper and isConsultant:' +(isDeveloper&&isConsultant));
 
System.debug('Either isDeveloper or isConsultant:' +(isDeveloper||isConsultant));

System.debug('Either isDeveloper or isConsultant:' +(isDeveloper||isConsultant));


if(isDeveloper&&isConsultant){
    System.debug('hem dev hem de cons ilanlarina bakiyor');}
else{
    System.debug('dev veya cons ilanlarina bakiyor, her ikisine de bakmiyor');}


if(isDeveloper||isConsultant){
    System.debug('hem dev hem de cons ilanlarina bakiyor');}
else{
    System.debug('dev veya cons ilanlarina bakiyor, her ikisine de bakmiyor');}

Boolean isover500k= True;
Boolean isITCompany= True;

if(isover500k&&isITCompany){System.debug('Sirket hem IT sirketi hem de geliri 500k uzeri');}
else{
    System.debug('Sirket ya IT Sirketi ya da geliri 500k uzerinde dedil veya her ikisi de degil');
    
}

Integer x1=10;
Integer y1=78;

System.debug(x1<y1);
System.debug(x1>y1);
System.debug(x1>=y1);
System.debug(x1<=y1);

x1++;
System.debug(x1);
x1--;
System.debug(x1);

x1=x1+1;
System.debug(x1);
x1+=1;
System.debug(x1);
