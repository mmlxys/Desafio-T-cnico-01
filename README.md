#include <iostream>
#include <iomanip>
using namespace std;

int main()
{ 
    string tecla;
    string resposta; // se escrever outra coisa tambem funciona mas não consegui arrumar isso
    string searchnome;
    
   cout << ("Lupa: Quem esta procurando?")<< endl; // digitar nome gwen ou qualquer incitação de gwen stacey
   cin >> searchnome;
   
   cout<< ("Voce esta vistando o perfil de Gwendolyne Stacy")<< endl;
   cout<< ("Confirme com qualquer tecla+enter para visualizar perfil:")<< endl;
   cin >> tecla;
   
   cout << ("Apresentando perfil by Dump Memories ")<< endl;
   
   cout <<("Usuario: gwen.stacey ")<< endl;
   cout << ("Seguidores: 2.000 ")<< endl;
   cout << ("Seguindo: 10 ")<< endl;
   cout << ("Posts: 100 " )<< endl;
   cout << ("Bio: 1995; cafe, fotografia e livros. @peterparker <3")<< endl;
   
   cout << ("Deseja visualizar o historico do usuario no Dump Memories? Confirme com qualquer tecla+enter para visualizar: ");
   cin >> resposta;
   
   cout << ("Ultimo acesso de @gwen.stacey : 2014") <<endl;
   cout << ("@gwen.stacey recebeu selo star de Dump Memories Aplication")<< endl;
   cout << ("@gwen.stacey postou 10 novos dumps no mês de maio")<<endl;
   cout << ("@gwen.stacey adicionou nova pasta fotografica no seu perfil") <<endl;
   cout << ("@gwen.stacey estava com @peterparker em seu ultimo dump")<<endl;
   cout << ("ver mais...")<<endl;
   
 
}
