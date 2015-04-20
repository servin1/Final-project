# Final-project
#include <iostream>
using namespace std;

void matriz()
{
  int A1[9], B1[9], C1[9], D1[9], E1[9], F1[9], G1[9], H1[9], I1[9];
  int A2[9], B2[9], C2[9], D2[9], E2[9], F2[9], G2[9], H2[9], I2[9];
  int i;
  int cont1=0;
  for(i=0; i<=8; i++){
    cout<<endl;
    cout<<"Dame el valor del arreglo A1 en su posición "<<i<<" "; cin >> A1[i];
    if(A1[i]==A1[i-1]){
      cout<<"there is a wrong number "<< endl;
    }
  }
  A2[0]=A1[0];
  B2[0]=A1[1];
  C2[0]=A1[2];
  D2[0]=A1[3];
  E2[0]=A1[4];
  F1[0]=A1[5];
  G1[0]=A1[6];
  H1[0]=A1[7];
  I1[0]=A1[8];


  cout<<endl;

  for(i=0; i<=8; i++){
    cout<<endl;
    cout<<"Dame el valor del arreglo B1 en su posición "<<i<<" "; cin >> B1[i];
  }

  A2[1]=A1[0];
  B2[1]=A1[1];
  C2[1]=A1[2];
  D2[1]=A1[3];
  E2[1]=A1[4];
  F1[1]=A1[5];
  G1[1]=A1[6];
  H1[1]=A1[7];
  I1[1]=A1[8];
  cout<<endl;

  for(i=0; i<=8; i++){
    cout<<endl;
    cout<<"Dame el valor del arreglo C1 en su posición "<<i<<" "; cin >> C1[i];
  }

  A2[2]=A1[0];
  B2[2]=A1[1];
  C2[2]=A1[2];
  D2[2]=A1[3];
  E2[2]=A1[4];
  F1[2]=A1[5];
  G1[2]=A1[6];
  H1[2]=A1[7];
  I1[2]=A1[8];
  cout<<endl;

   for(i=0; i<=8; i++){
   cout<<endl;
   cout<<"Dame el valor del arreglo D1 en su posición "<<i<<" "; cin >> D1[i];
     }

     A2[3]=A1[0];
     B2[3]=A1[1];
     C2[3]=A1[2];
     D2[3]=A1[3];
     E2[3]=A1[4];
     F1[3]=A1[5];
     G1[3]=A1[6];
     H1[3]=A1[7];
     I1[3]=A1[8];

  cout<<endl;

      for(i=0; i<=8; i++){
        cout<<endl;
        cout<<"Dame el valor del arreglo E1 en su posición "<<i<<" "; cin >> E1[i];
  }

  A2[4]=A1[0];
  B2[4]=A1[1];
  C2[4]=A1[2];
  D2[4]=A1[3];
  E2[4]=A1[4];
  F1[4]=A1[5];
  G1[4]=A1[6];
  H1[4]=A1[7];
  I1[4]=A1[8];
  cout<<endl;


    for(i=0; i<=8; i++){
      cout<<endl;
      cout<<"Dame el valor del arreglo F1 en su posición "<<i<<" "; cin >> F1[i];
  }

  A2[5]=A1[0];
  B2[5]=A1[1];
  C2[5]=A1[2];
  D2[5]=A1[3];
  E2[5]=A1[4];
  F1[5]=A1[5];
  G1[5]=A1[6];
  H1[5]=A1[7];
  I1[5]=A1[8];
  cout<<endl;

  for(i=0; i<=8; i++){
  cout<<endl;
  cout<<"Dame el valor del arreglo G1 en su posición "<<i<<" "; cin >> G1[i];
  }

  A2[6]=A1[0];
  B2[6]=A1[1];
  C2[6]=A1[2];
  D2[6]=A1[3];
  E2[6]=A1[4];
  F1[6]=A1[5];
  G1[6]=A1[6];
  H1[6]=A1[7];
  I1[6]=A1[8];
  cout<<endl;


  for(i=0; i<=8; i++){
  cout<<endl;
  cout<<"Dame el valor del arreglo H1 en su posición "<<i<<" "; cin >> H1[i];
  }
  A2[7]=A1[0];
  B2[7]=A1[1];
  C2[7]=A1[2];
  D2[7]=A1[3];
  E2[7]=A1[4];
  F1[7]=A1[5];
  G1[7]=A1[6];
  H1[7]=A1[7];
  I1[7]=A1[8];
  cout<<endl;

  for(i=0; i<=8; i++){
  cout<<endl;
  cout<<"Dame el valor del arreglo I1 en su posición "<<i<<" "; cin >> I1[i];
  }

  A2[8]=A1[0];
  B2[8]=A1[1];
  C2[8]=A1[2];
  D2[8]=A1[3];
  E2[8]=A1[4];
  F1[8]=A1[5];
  G1[8]=A1[6];
  H1[8]=A1[7];
  I1[8]=A1[8];
  cout<<endl;

  for(i=0; i<=8; i++){
    cout<<""<<A1[i]<<"     ";
  }
    cout<<endl;
    cout<<endl;
    cout<<endl;


  for(i=0; i<=8; i++){
    cout<<""<<B1[i]<<"     ";
  }
    cout<<endl;
    cout<<endl;
    cout<<endl;

    for(i=0; i<=8; i++){
      cout<<""<<C1[i]<<"     ";
    }
       cout<<endl;
       cout<<endl;
       cout<<endl;


      for(i=0; i<=8; i++){
        cout<<""<<D1[i]<<"     ";
      }
        cout<<endl;
        cout<<endl;
        cout<<endl;


        for(i=0; i<=8; i++){
          cout<<""<<E1[i]<<"     ";
        }
          cout<<endl;
          cout<<endl;
          cout<<endl;


          for(i=0; i<=8; i++){
            cout<<""<<F1[i]<<"     ";
          }
            cout<<endl;
            cout<<endl;
            cout<<endl;


            for(i=0; i<=8; i++){
              cout<<""<<G1[i]<<"     ";
            }
              cout<<endl;
              cout<<endl;
              cout<<endl;

              for(i=0; i<=8; i++){
                cout<<""<<H1[i]<<"     ";
              }
                cout<<endl;
                cout<<endl;
                cout<<endl;


                for(i=0; i<=8; i++){
                  cout<<""<<I1[i]<<"     ";
                }
                  cout<<endl;
                  cout<<endl;
                  cout<<endl;


                  for(i=1; i<=8; i++){

                    if(A2[i]==B1[0] || A2[i]==B1[0] || A2[i]==C1[0] || A2[i]==D1[0] || A2[i]==E1[0] || A2[i]==F1[0] || A2[i]==G1[0] || A2[i]==H1[0] || A2[i]==I1[0])

                    {
                      cont1=cont1+1;
                    }
                  }
                  cout<<""<<cont1<< " numbers repited"<< endl; 


}

int main ()
{
  matriz();

  return 0;
}
