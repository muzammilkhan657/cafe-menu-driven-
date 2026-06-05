# cafe-menu-driven-
i just do coding using funtion
#include<iostream><br>
using namespace std;<br>
const int coffee = 200;<br>
const int sandwich = 500;<br>
const int cakes = 450;<br>
const int tea = 70;<br>
const int burgers = 300;<br>
void display(){<br>
    cout<<"--------------------"<<endl;<br>
	cout<<"Welcome to the cafe: "<<endl;<br>
	cout<<"--------------------"<<endl;<br>
	cout<<"---------------------------------"<<endl;<br>
	cout<<"|1.Press one to order coffee:     |"<<endl;<br>
	cout<<"|2.Press two two order sandwich:  |"<<endl;<br>
	cout<<"|3.Press three to order cakes:    |"<<endl;<br>
	cout<<"|4.Press four to order tea:       |"<<endl;<br>
	cout<<"|5.Press five to order burgers:   |"<<endl;<br>
	cout<<"|7.Press seven exit:              |"<<endl;<br>
	cout<<"----------------------------------"<<endl;<br>
}<br>
void price(){<br>
	cout<<"Coffee price: RS"<<coffee<<endl;<br>
	cout<<"Sandwich price: RS"<<sandwich<<endl;<br>
	cout<<"Cakes price: RS"<<cakes<<endl;<br>
	cout<<"Tea price: RS"<<tea<<endl;<br>
	cout<<"Burgers price: RS"<<burgers<<endl;<br>
}<br>
int main(){<br>
	int quantity;<br>
	int choice;<br>
	do{<br>
		display();<br>
		cin>>choice;<br>
		switch (choice){<br>
			case 1:<br>
				cout<<"enter the quantity to order coffee: "<<endl;<br>
				cin>>quantity;<br>
				cout<<"Your bill is: "<<quantity*coffee<<endl;<br>
				break;<br>
				case 2:<br>
				cout<<"enter the quantity to order sandwich: "<<endl;<br>
				cin>>quantity;<br>
				cout<<"Your bill is: "<<quantity*sandwich<<endl;<br>
				break;<br>
				case 3:<br>
				cout<<"enter the quantity to order cakes: "<<endl;<br>
				cin>>quantity;<br>
				cout<<"Your bill is: "<<quantity*cakes<<endl;<br>
				break;<br>
				case 4:<br>
				cout<<"enter the quantity to order tea: "<<endl;<br>
				cin>>quantity;<br>
				cout<<"Your bill is: "<<quantity*tea<<endl;<br>
				break;<br>
				case 5:<br>
				cout<<"enter the quantity to order burgers: "<<endl;<br>
				cin>>quantity;<br>
				cout<<"Your bill is: "<<quantity*burgers<<endl;<br>
				break;<br>
				case 6:<br>
				price();<br>
				break;<br>
				case 7:<br>
				cout<<"Thanks for coming: "<<endl;<br>
				break;<br>
				default:<br>
					cout<<"Invalid choice: "<<endl;<br>
		}<br>	
	}<br>
	while(choice!=7);
		
}<br>
