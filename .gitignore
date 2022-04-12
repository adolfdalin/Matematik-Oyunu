#include
#include
#include #include <windows.h> ad alanını std kullanarak;

int main() { karakter islem;

bool done=false;
while (!done)
   {
   	cout<<"**********************************************************************************************************************************************"<<endl;
    cout<<"**********************************************************************************************************************************************"<<endl;
   	cout<<"**********************************************************************************************************************************************"<<endl;
   	cout<<"**********************************************************************************************************************************************"<<endl;

   	cout<<"							          ANA MENU"<<endl<<endl<<endl;
   	cout<<"                            	      			       1) toplama"<<endl;
   	cout<<"                                    			       2) cikarma"<<endl;
    cout<<"                                     			       3) carpma"<<endl;
    cout<<"                                    		   	       4) bolme"<<endl<<endl<<endl<<endl<<endl<<endl<<endl<<endl<<endl<<endl;
    cout<<"                                    		   	    CREDI:Omer Apyadin "<<endl;


	cin>>islem; // burda hangi islem cözceksek onu yazdığımız değişken
	if(islem=='+') //burada eğer "+" yazarsak toplama islemi devreye giriyor eğer "-" yazarsak çıkarma işlemi
	{ 
	system ("CLS");
   srand(time(NULL)); // raskele sayı üretmek için kullanılan basit bir kod
   int CorrectAnswers=0,AnswersDone=0;

   while(1)
       {
       if (AnswersDone==10){break;}
       int Answer=0;
       int Num  = rand()%100;  // raskele sayıyı ondalığa indiriyor yanı mesala 954654 sayısı geldiyse 86 yapıyor
       int Num2 = rand()%100;  // aynısı sadece sayı iki için
       cout << Num << " + " << Num2 << " = ";
       cin >> Answer;
       if (Answer==(Num+Num2)) //burada doğru cevap = sayi1 + sayi2 ise "doğru" yaz diyoruz
          {
          cout << endl << "DOGRU! \"" << Num << " + " << Num2 << "\" aferim " << Answer << endl;
          CorrectAnswers++;
          }
       else
          {
          cout << endl << "YANLIS APTAL \"" << Num << " + " << Num2 << " = " << Num+Num2 << endl;// yanlış olursa yanlış aptal yazıyor
          }
       AnswersDone++;
       }
       		system ("CLS");

   if (CorrectAnswers==10){cout << endl << CorrectAnswers << "da " << AnswersDone << " pravo" << endl;} //burada ise karşılaştırma yaparak derecelendiriyoruz yani 10 doğrun varsa pravo yazıyor
   if (CorrectAnswers>=6 && CorrectAnswers<10){cout << endl << CorrectAnswers << " da " << AnswersDone << " IYI" << endl;}
   if (CorrectAnswers>=3 && CorrectAnswers<6){cout << endl << CorrectAnswers << " da " << AnswersDone << " KOTU" << endl;}   
   if (CorrectAnswers>=0 && CorrectAnswers<3){cout << endl << CorrectAnswers << " da " << AnswersDone << " BERBAT!!!!!!!!!" << endl;}    
   cout << endl << "TEKRER DENE [0=evet][1=hayir]" << endl;
   cin >> done;
   cout << endl;
      
cout << "TESSEKURLER !" << endl; //bitiikten sonra teşekkür ediyoruz 
system("PAUSE");   //ve bitiriyoruz
}

 if(islem=='-') //çıkarma işlemi için karşılaştırma yine herşey aynı sadece "+" yerine - var
{
	system ("CLS");
   srand(time(NULL)); 
   int CorrectAnswers=0,AnswersDone=0;

   while(1)
       {
       if (AnswersDone==10){break;}
       int Answer=0;
       int Num  = rand()%100;  
       int Num2 = rand()%100; 
       cout << Num << " - " << Num2 << " = ";
       cin >> Answer;
       if (Answer==(Num-Num2))
          {
          cout << endl << "DOGRU! \"" << Num << " - " << Num2 << "\" aferim " << Answer << endl;
          CorrectAnswers++;
          }
       else
          {
          cout << endl << "YANLIS APTAL \"" << Num << " - " << Num2 << " = " << Num+Num2 << endl;
          }
       AnswersDone++;
       }
       		system ("CLS");

   if (CorrectAnswers==10){cout << endl << CorrectAnswers << " da " << AnswersDone << " pravo" << endl;}
   if (CorrectAnswers>=6 && CorrectAnswers<10){cout << endl << CorrectAnswers << " da " << AnswersDone << " IYI" << endl;}
   if (CorrectAnswers>=3 && CorrectAnswers<6){cout << endl << CorrectAnswers << " da " << AnswersDone << " KOTU" << endl;}   
   if (CorrectAnswers>=0 && CorrectAnswers<3){cout << endl << CorrectAnswers << " da " << AnswersDone << " BERBAT!!!!!!!!!" << endl;}      
   cout << endl << "TEKRER DENE [0=	Evet][1=Hayir]" << endl;
   cin >> done;
   cout << endl;
       
cout << "TESSEKURLER !" << endl;
system("PAUSE");   
}

	 else if (islem=='*')//burda çarpma işlemi var burda farklı olarak sadece rasgele sayı 100 delik değilde 10dalık sistemde oluyor bunu istersek değiştirebiliriz 
	
	{
	system ("CLS");
   srand(time(NULL)); 
   int CorrectAnswers=0,AnswersDone=0;

   while(1)
       {
       if (AnswersDone==10){break;}
       int Answer=0;
       int Num  = rand()%10;  
       int Num2 = rand()%10; 
       cout << Num << " * " << Num2 << " = ";
       cin >> Answer;
       if (Answer==(Num*Num2))
          {
          cout << endl << "DOGRU! \"" << Num << " * " << Num2 << "\" aferim " << Answer << endl;
          CorrectAnswers++;
          }
       else
          {
          cout << endl << "YANLIS APTAL \"" << Num << " * " << Num2 << " = " << Num+Num2 << endl;
          }
       AnswersDone++;
       }
       		system ("CLS");

   if (CorrectAnswers==10){cout << endl << CorrectAnswers << " da " << AnswersDone << " pravo" << endl;}
   if (CorrectAnswers>=6 && CorrectAnswers<10){cout << endl << CorrectAnswers << " da " << AnswersDone << " IYI" << endl;}
   if (CorrectAnswers>=3 && CorrectAnswers<6){cout << endl << CorrectAnswers << " da " << AnswersDone << " KOTU" << endl;}   
   if (CorrectAnswers>=0 && CorrectAnswers<3){cout << endl << CorrectAnswers << " da " << AnswersDone << " BERBAT!!!!!!!!!" << endl;}   
   cout << endl << "TEKRER DENE [0=Yes][1=No]" << endl;
   cin >> done;
   cout << endl;
  
cout << "TESSEKURLER !" << endl;
system("PAUSE");   
}

else if(islem=='/') //bölmenin çarpmadan farkı "*" yerine "/" var { system ("CLS"); srand(zaman(NULL)); int CorrectAnswers=0,AnswersDone=0;

   while(1)
       {
       if (AnswersDone==10){break;}
       int Answer=0;
       int Num  = rand()%10; 
       int Num2 = rand()%100;  
       cout << Num << " / " << Num2 << " = ";
       cin >> Answer;
       if (Answer==(Num/Num2))
          {
          cout << endl << "DOGRU! \"" << Num << " / " << Num2 << "\" aferim " << Answer << endl;
          CorrectAnswers++;
          }
       else
          {
          cout << endl << "YANLIS APTAL \"" << Num << " +/ " << Num2 << " = " << Num+Num2 << endl;
          }
       AnswersDone++;
       }
       		system ("CLS");

   if (CorrectAnswers==10){cout << endl << CorrectAnswers << " da " << AnswersDone << " pravo" << endl;}
   if (CorrectAnswers>=6 && CorrectAnswers<10){cout << endl << CorrectAnswers << "da " << AnswersDone << "  IYI" << endl;}
   if (CorrectAnswers>=3 && CorrectAnswers<6){cout << endl << CorrectAnswers << " da " << AnswersDone << "  KOTU" << endl;}   
   if (CorrectAnswers>=0 && CorrectAnswers<3){cout << endl << CorrectAnswers << " da " << AnswersDone << "  BERBAT!!!!!!!!!" << endl;}   
   cout << endl << "TEKRER DENE [0=Yes][1=No]" << endl;
   cin >> done;
   cout << endl;
       
cout << "TESSEKURLER !" << endl;
system("PAUSE");   
}

else if (islem==4){ system ("CLS"); srand(zaman(NULL)); // rastgele tohum int CorrectAnswers=0,AnswersDone=0;

   while(1)
       {
       		

       if (AnswersDone==10){break;}
       int Answer=0;
       int Num  = rand()%10;  // Get a random number between 0 and 10
       int Num2 = rand()%10;  // Get a random number between 0 and 10
       cout << Num << " + " << Num2 << " = ";
       cin >> Answer;
       if (Answer==(Num+Num2))
          {
          cout << endl << "DOGRU! \"" << Num << " + " << Num2 << "\" aferim " << Answer << endl;
          CorrectAnswers++;
          }
       else
          {
          cout << endl << "YANLIS APTAL \"" << Num << " + " << Num2 << " = " << Num+Num2 << endl;
          }
       AnswersDone++;
       }
       		system ("CLS");

   if (CorrectAnswers==10){cout << endl << CorrectAnswers << " da " << AnswersDone << " pravo" << endl;}
   if (CorrectAnswers>=6 && CorrectAnswers<10){cout << endl << CorrectAnswers << "da " << AnswersDone << " IYI" << endl;}
   if (CorrectAnswers>=3 && CorrectAnswers<6){cout << endl << CorrectAnswers << " da " << AnswersDone << " KOTU" << endl;}   
   if (CorrectAnswers>=0 && CorrectAnswers<3){cout << endl << CorrectAnswers << " da " << AnswersDone << " BERBAT!!!!!!!!!" << endl;}      
   cout << endl << "TEKRER DENE [0=Yes][1=No]" << endl;
   cin >> done;
   cout << endl;
   }    
cout << "TESSEKURLER !" << endl;
system("PAUSE");  
} 0 döndür;

}
