# Contoh pengenalan variabel

Coding program lengkap

  
    #include <stdio.h>
    #include <conio.h>

    int c=4;
    int m=3;
    void lokal ()
    {
    int a=5;
    int b=a+2;
    printf ("Lokal a = %d\n",a);
    printf ("Lokal b = %d\n",b);
    // karena tidak ada c, maka ambil global
    printf ("global c=%d\n",c);
    }

    int main ()
    {
    int a=1;
    int b=2;
    int c=3;
    lokal ();
    printf ("main a = %d\n",a);
    printf ("main b = %d\n",b);
    //walaupun global c ada tapi c yang digunakan yang di main
    printf ("main c =%d\n",c);
    //karena tidak ada m, maka ambil global
    printf ("global m =%d\n",m);
    getch ();
    }


Hasil program
![img](https://raw.githubusercontent.com/MUTIARAIZMI/Contoh-pengenalan-variabel/master/contoh%20pengenalan%20variabel.jpg)
