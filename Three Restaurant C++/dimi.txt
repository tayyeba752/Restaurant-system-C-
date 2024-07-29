#include <iostream>
#include <windows.h>
#include <fstream>
using namespace std;
// ----------------------- group 1-------------------
class Deal{
	public:
		int price;
		void data(){
		
			cout<<"-----------!!!  enter the specified number to select the deals !!!-----------------"<<endl;
			cout<<"Deal 1:         2 Zinger Burgers, 2 Shawarma                            |  RS 1,200"<<endl;
			cout<<"Deal 2:          1 Large Pizza 13', 3 shakes                            |  RS 2,200 "<<endl;
			cout<<"Deal 3:              3 Shakes of any Flavour                            |  Rs 1,000"<<endl;
			cout<<"Deal 4:   1 Pettie Burger , 1 Zinger Burger , 1 Grilled Shawarma    	   |  Rs 950"<<endl;
			cout<<"Deal 5:         3 Zinger Burger , 3 cold coffee                         |  Rs 2,100"<<endl;
			cout<<"Deal 6:         3 Anda shami , 3 Shakes half                            |  Rs 1,000"<<endl;
			cout<<endl<<endl<<endl;	
		}
};
class Deal1:public Deal{
	public:
			void display(){
				int j;
				cout<<"select the shawarma flavour"<<endl;
					cout<<"student shawarma (1)"<<endl;
					cout<<"grilled shawarma (2)"<<endl;
					cout<<"zinger shawarma (3)"<<endl;
					cout<<"malai boti shawarma (4)"<<endl;
					cin>>j;
					switch(j){
					case 1:		
						cout<<"2 zinger burgers & 2 student shawarma has been placed"<<endl;
						int a;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>a;
						switch(a){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:							
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
						break;
					case 2:
						cout<<"2 zinger burgers & 2 grilled shawarma has been placed"<<endl;
						int b;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>b;
						switch(b){
						case 0:
							
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
						break;
						case 1:
							
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
						break;
						}
						break;
					case 3:
						cout<<"2 zinger burgers & 2 zinger shawarma has been placed"<<endl;
						int c;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>c;
						switch(c){
						case 0:
							
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
						case 1:
							
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
						break;
					case 4:
					
						cout<<"2 zinger burgers & 2 malai boti shawarma has been placed"<<endl;
						int d;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>d;
						switch(d){
						case 0:
						
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
						case 1:
						
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;					
					}
						break;
					
	  }
}
}; 
class Deal2:public Deal{
	public:
		void display(){
				cout<<" 1 large pizza 13', 3 shakes have been selected "<<endl;
				int j;
				cout<<"Select Pizza Flavour :"<<endl;
				cout<<"Supreme        (1)"<<endl;
				cout<<"Chicken Fajita (2)"<<endl;
				cout<<"Malai Boti     (3)"<<endl;
				cout<<"Chicken Tikka  (4)"<<endl;
				cout<<"B.B.Q pizza    (5)"<<endl;
				cin>>j;
				int i;
				cout<<"Select Shake's Flavour :"<<endl;
				cout<<"Cold Coffee     (1)"<<endl;
				cout<<"Oreo Shake      (2)"<<endl;
				cout<<"Nutella Shake   (3)"<<endl;
				cin>>i;
				if(j==1 && i==1){
				
					cout<<"1 Supreme Pizza 13', 3 Cold Coffee are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
			 		}	
				if(j==1 && i==2){
					
					cout<<"1 Supreme Pizza 13', 3 Oreo Shakes are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==1 && i==3){
				
					cout<<"1 Supreme Pizza 13', 3 Nutella shakes are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
			}
				if(j==2 && i==1){
					cout<<"1 Chicken Fajita Pizza 13', 3 Cold Coffee are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==2 && i==2){
					cout<<"1 Chicken Fajita 13', 3 Oreo Shakes are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==2 && i==3){
					cout<<"1 Chicken Fajita 13', 3 Nutella shakes are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==3 && i==1){
					cout<<"1 Malai Boti 13', 3 Cold Coffee are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==3 && i==2){
					cout<<"1 Malai Boti 13', 3 Oreo Shakes are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==3 && i==3){
					cout<<"1 Malai Boti 13', 3 Nutella shakes are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==4 && i==1){
					cout<<"1 Chicken Tikka 13', 3 Cold Coffee are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==4 && i==2){
					cout<<"1 Chikken Tikka 13', 3 Oreo Shakes are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==4 && i==3){
					cout<<"1 Chikken Tikka 13', 3 Nutella shakes are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==5 && i==1){
					cout<<"1 B.B.Q Pizza 13', 3 Cold Coffee are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==5 && i==2){
					cout<<"1 B.B.Q Pizza 13', 3 Oreo Shakes are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
				if(j==5 && i==3){
					cout<<"1 B.B.Q Pizza 13', 3 Nutella shakes are ready to purchase"<<endl;
					int k;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>k;
						switch(k){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				}
		}
		
};
class Deal3:public Deal{
	public:
		void display(){
			int k;
				cout<<"3 Shakes are ready to be placed "<<endl;
				cout<<"Select the flavour of Shakes:"<<endl;
				cout<<"Oreo Shake    (1)"<<endl;
				cout<<"Nutella Shake (2)"<<endl;
				cout<<"Banana Shake  (3)"<<endl;
				cout<<"Cold Coffee   (4)"<<endl;
				cout<<"Mango Shake   (5)"<<endl;
			cin>>k;
			switch(k){
				case 1:
					cout<<"Your 3 Oreo Shakes have been placed"<<endl;
					int a;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>a;
						switch(a){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
						break;
				case 2:
					cout<<"Your 3 Nutella Shakes have been placed"<<endl;
					int b;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>b;
						switch(b){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
						break;
				case 3:
					cout<<"Your 3 Banana Shakes have been placed"<<endl;
					int c;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>c;
						switch(c){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
						break;
				case 4:
					cout<<"Your 3 Cold Coffee have been placed"<<endl;
					int d;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>d;
						switch(d){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
						break;
				case 5:
					cout<<"Your 3 Mango Shakes have been placed"<<endl;
					int e;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>e;
						switch(e){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
						break;
			}
		}
};
class Deal4:public Deal{
	public:
		void display(){
			cout<<"Your 1 Pettie Burger , 1 Zinger Burger , 1 Grilled Shawarma is ready"<<endl;
			int a;
				cout<<"for home delivery press 0"<<endl;
				cout<<"for take away press 1"<<endl;
				cin>>a;
				switch(a){
					case 0:
					cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
					break;
					case 1:
					cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
					break;
						}
		}
};

class Deal5:public Deal{
	 public:
	 	int sum=0;
	int price;
	 	void display(){
	 		cout<<"Your 3 Zinger Burger , 3 Cold Coffee have been placed "<<endl;
	 		int a;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>a;
						switch(a){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
		 }
};
class Deal6:public Deal{
	public:
		void display(){
			int k;
			cout<<"Your 3 Anda Shami , 3 Half Shakes have been placed"<<endl;
			cout<<"Select the flavour of Shakes :"<<endl;
			cout<<"Cold Coffee    (1)"<<endl;
			cout<<"Oreo Shake     (2)"<<endl;
			cout<<"Nutella Shake  (3)"<<endl;
			cout<<"Bnana Shake    (4)"<<endl;
			cout<<"Mango Shake    (5)"<<endl;
			cin>>k;
			switch(k){
				case 1:
					cout<<"Your 3 Anda Shami , 3 Half Cold Coffee are ready"<<endl;
					int a;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>a;
						switch(a){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				break;
				case 2:
					cout<<"Your 3 Anda Shami , 3 Half Oreo Shakes are ready"<<endl;
					int b;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>b;
						switch(b){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				break;
				case 3:
				cout<<"Your 3 Anda Shami , 3 Half Nutella Shakes are ready"<<endl;
					int c;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>c;
						switch(c){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				break;
				case 4:
					cout<<"Your 3 Anda Shami , 3 Half Banana Shakes are ready"<<endl;
					int d;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>d;
						switch(d){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				break;
				case 5:
					cout<<"Your 3 Anda Shami , 3 Half Mango Shakes are ready"<<endl;
					int e;
						cout<<"for home delivery press 0"<<endl;
						cout<<"for take away press 1"<<endl;
						cin>>e;
						switch(e){
							case 0:
							cout<<"please pay the bill thanks for placing order your order will be delivered in 20 min"<<endl;
							break;
							case 1:
							cout<<"your order has been placed please recieve your order in 20 mins thanks"<<endl;
							break;
						}
				break;
			}
		}
};

class display:public Deal{
	public:
	int sum=0;
	int price;
	void show(){
		Deal d;
		d.data();
	}
	void show1(){
	
	char orderPlace = 'y';
	while(orderPlace == 'y' || orderPlace == 'Y')
	{
	
	int x;
	cin>>x;
	if(x==1){
		price=1200;
		Deal1 obj1;
		obj1.display();
		cout<<"your bill is"<<price<<endl;
	}	
	if(x==2){
		price=2200;
		Deal2 obj2;
		obj2.display();
		cout<<"your bill is "<<price<<endl;
	}	
	if(x==3){
		price=1000;
		Deal3 obj3;
		obj3.display();
		cout<<"your bill is "<<price<<endl;
	}
	if(x==4){
		price=950;
		Deal4 obj4;
		obj4.display();
		cout<<"your bill is "<<price<<endl;
	}
	if(x==5){
		price=2100;
		Deal5 obj5;
		obj5.display();
		cout<<"your bill is "<<price<<endl;
	}	
	if(x==6){
		price=1000;
		Deal6 obj6;
		obj6.display();
		cout<<"your bill is "<<price<<endl;
	}
	sum=sum+price;
	cout<<endl<<endl<<endl;
	cout<<"your total bill is:"<<sum;
	cout<<endl<<endl<<endl;
	Deal dl;
	dl.data();
	display a;
	cout<<"Do you want to place another order?  y :"<<endl;
	cout<<"Do you want to end orders ? n :"<<endl;
	cin>>orderPlace;
	}
}
};


// ----------------- group 2 -----------------
class Items{
	protected:
		int num1,a,b,sum=0;
		string name;
	public:
		Items();
		void LoginSignUp();
		void SignUp();
		void Login();
		
		int Menu();
		int ManuString();
		int elseFalse();
		
		int FastFood();
		int DesiFood();
		int TeaCofee();
		int manuElseFalse();
		int manuwrong();
		int addItem_Y_N();
};
// ------------- Constructor --------------
Items::Items(){
	cout<<" \n          \n                    @@__@@__@@__@@___  Welcome to TMUM RESTAURANT  ___@@__@@__@@__@@\n"<<endl;
	Items::LoginSignUp();
}

// ------------- Menu Function --------------
int Items::Menu(){
	
	int keys;
	cout << "                   ---------!!! What do you want to order !!!---------"<< endl;
	cout << "      1) Deals "<< endl;
	cout << "      2) Items "<< endl;
	cin >> keys;
	if(keys==1){
		// --------- DEALS ----------
			display a;
			a.show();
			a.show1();
	}else if(keys==2){
		// --------- DEALS ----------
			Items::ManuString();
	}
	

}

// ------------- Menu String --------------
int Items::ManuString(){
//	system("CLS")
	cout << "                 @@ ______ MENU LIST _______ @@              \n\n "<<endl;
	cout <<"What's you want to eat?\n"<<endl;
	cout <<"              1: **Fast food** code is 576"<<endl;
	cout <<"              2: **Dasi food** code is 898"<<endl;
	cout <<"              3: **Tea Cofee** code is 634"<<endl;
	
	cout<<"\n\n Type Code :  ";
	cin >> a;  
	if( a==576){
		Items::FastFood();	
	}else if(a==898){
		Items::DesiFood();
	}else if(a==634){
		Items::TeaCofee();
	}
	else{
		Items::manuElseFalse();
	}
}
int Items::FastFood(){
	cout<<"\n               ** 1ITEM **                       ** PRICE **      "<<endl;
		cout<<"               1:Yummy burger                          350           "<<endl;
		cout<<"               2:Spicyyyyyy shawarma        	        400			"<<endl;
		cout<<"               3:Teka full chezy pizza     	       1200			"<<endl;
		cout<<"               4:Grill fries                          100      	    "<<endl;
		cout << "\n			  5:Press 5 for back: ";
					cout << "\n\nAdd Items Into cart:- ";
					cin >> b;
					if(b==1){
						int p = 350;
						sum += p;
						Items::addItem_Y_N();
					}
					else if(b==2){
						int p=400;
						sum +=p;
						Items::addItem_Y_N();
					}
					else if(b==3){
						int p=1200;
						sum +=p;
						Items::addItem_Y_N();
					}
					else if (b==4){
						int p=1200;
						sum += p;
						Items::addItem_Y_N();
					}
					else if(b==5){	
					cout << "\n\n\n\n\n\n\n\n\n\n\n\n";
						Items::manuwrong();
					}
					else{
						cout<<"\n\n\n\n\n\n\n\n\n\n\nTry_Again put correct code------- \n\n\n:"<<endl;
						Items::manuwrong();
					}
}
void Items::LoginSignUp(){
	int key;
	cout << "1) SignUp " << endl;
	cout << "2) Login  " << endl;
	cin >> key;
	if(key==1){
		Items::SignUp();
		system("CLS");
		cout<<" \n          \n                    @@__@@__@@__@@___  Welcome to TMUM RESTAURANT  ___@@__@@__@@__@@\n"<<endl;
		cout << "\nNow login Please: ----";
		Items::Login();
	}else{
		Items::Login();
	}
}

void Items::SignUp(){
	// ------------------Default-PUT------------------
	int 	pass;
	string  name;
	cout << " put name: ";
	cin >> name ;
	cout << " put Password: ";
	cin >> pass;
		ofstream File_CP("textDefault.txt");
		File_CP << name;
		File_CP << pass ;
		File_CP.close();
		cout << "Name & Password set SUCCESSFULLY:--";
}
void Items::Login(){
	cout << "Type your Name & Password Here:-"<<endl;
	string name;
	int pass;	
	cout << "Your Name: ";
	cin >> name;
	cout << "Type Pass: ";
	cin >> pass;
	
		ofstream File_CP("textCheck.txt");
		File_CP << name;
		File_CP << pass ;
		File_CP.close();
	
 	//          _____ DEFAULT DATA GET _____
		string defaultGet;
		ifstream File_DG("textDefault.txt");
		while (getline (File_DG , defaultGet )){
			cout << endl;
		}
		File_DG.close();
	//          _____ CHECK DATA GET _____
		string checkGet;
		ifstream File_CG("textCheck.txt");
		while (getline (File_CG , checkGet )){
			cout << endl;	
		}
		File_CG.close();
	// ------------ APPLY-CONDITION-FOR-CHECH -----------------
		if(checkGet==defaultGet){
			cout << "You Have login Successfully:-\n";
				Items::Menu();
		}else{
			cout << "You Have Type wrong password and Name: -----";
		}			
}


int Items::DesiFood(){
			cout<<"\n\n\n        ** 1ITEM **                  		 ** PRICE **      "<<endl;
		cout<<"      1:Karai                		            1500         "<<endl;
		cout<<"      2:Malai bhoti        		            750			"<<endl;
		cout<<"      3:Tika Bhoti                                  900          "<<endl;
		
			cout << "\nAdd Items Into cart:- ";
					cin >> b;
					if(b==1){
						int p = 1500;
						sum += p;
						Items::addItem_Y_N();
					}
					else if(b==2){
						int p=750;
						sum +=p;
						Items::addItem_Y_N();
					}
					else if(b==3){
						int p=900;
						sum +=p;
						Items::addItem_Y_N();
					}else{
						Items::manuwrong();
					}
}
int Items::TeaCofee(){
	
		cout<<"\n\n\n        ** 1ITEM **                  			    ** PRICE **      "<<endl;
		cout<<"      1:Green Tea						80          "<<endl;
		cout<<"      2:Dhood patti						80          "<<endl;
		cout<<"      3:Cofee     	  					130          "<<endl;
		
		
			cout << "\nAdd Items Into cart:- ";
					cin >> b;
					if(b==1){
						int p =80;
						sum += p;
						Items::addItem_Y_N();
					}
					else if(b==2){
						int p=80;
						sum +=p;
						Items::addItem_Y_N();
					}
					else if(b==3){
						int p=130;
						sum +=p;
						Items::addItem_Y_N();
					}
					else{
						Items::manuwrong();
					}
}
int Items::manuElseFalse(){
	cout<<"\n\nput correct code"<<endl;
	Items::ManuString();
}
int Items::manuwrong(){
	Items::ManuString();
}
int Items::elseFalse(){
	cout << "\n\n\n\n\nTry Again " << endl;
	Items::Menu();
}
int Items::addItem_Y_N(){
	cout<<"sum is = "<<sum;
	cout<< "\nWant to add more items: (y/n) \n";
	char c;
	cin >> c;
	if(c=='y' ){
		Items::ManuString();
	}else if(c=='n'){
		cout << "Hey! "<< name << " your total bill is = " << sum << endl;		
		ofstream File("text.txt");
		File << name << "s' total bill = " << sum << endl;
		File.close();
	}
}

int main(){
	Items a;
}



