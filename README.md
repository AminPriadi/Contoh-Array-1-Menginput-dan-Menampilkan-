# Contoh-Array-1-Menginput-dan-Menampilkan-
    #include<stdio.h>
    #include<conio.h>

    int main()
    {
        int nilai[5], x;
        printf("memasukan nilai :\n");
        for(x=0;x<5;x++)
        {
            printf("nilai angka : "); scanf("%d",&nilai[x]);
        }
        printf("\n");
        printf("membaca nilai :\n");
        for(x=0;x<5;x++)
        {
            printf("nilai angka : %d",nilai[x]);
            printf("\n");
        }
        getch();
    }
   # Hasil
   ![img](https://raw.githubusercontent.com/AminPriadi/Contoh-Array-1-Menginput-dan-Menampilkan-/master/7.png)
