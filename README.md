# TextBasedGame-4
#include<iostream>
#include<ctime>
using namespace std;

void Monster

		int main(1) {
		char input;
		cout << "Its cold, and you must escape.Good luck!" << endl << endl;



		int main() {
			int currency =
		
		string inventory[10];
		 int health = 100;
		 int money = 100;

		#include<iostream>
		using namespace std;


		void shop();
		void monster();
		void Battle; 

	case 2://bedroom
		monster(); //function call
		cout << "you're in the blue bedroom" << endl;
		cout << "uou can go (n)orth" << endl;
		cin >> input;

		if (input == "n")
			room = 1;

		else
			cout << "sorry, I don't understand" << endl;
		break 


	int main() {
		//local varibles
		int room = 1;
		string input = "a"
		int turns = 0;

		while (input != "q"&& turns < 20 && health > 0) { //GAME LOOP------------------
			//print inventory 
			cout << "Your Inventory";
			for (int i = 0; i < 5; i++)
				cout << inventory = [i] << "";
			cout << endl << endl;

			cout << "It is turn " << turns << endl;
			cout << "You have" << 20 - turns "turns left." << endl; 
			turns++;
			
			cout << "Your health:" << health << endl << endl;

			switch (room) {
			
			void monster() {
				int num = rand() % 100 + 1;
				if (num < 20)//20% chance 
					cout << "a skeleton appears" << endl;
				health -= 3;
				cout << "the skeleton hits you for 3 damage" << endl;
				Battle(40);
			}
			else if (num < 50) {//30% chance
			cout << " a zombie appears" << endl;
			Battle(50);
		} 
			else if (num < 50) {
			  cout 
		cout <<  "it is turn " << turns << endl;
		cout << "You have " << 20 - turns << "turns left." << endl;
		turns++;
	    //print health
		cout << " Your health:" << health << endl;
		cout << " You have" << money <<"rupees" endl << endl



				cout << "Thanks for playing!" << endl; 

				void monster() {
					int num = rand() % 100 + 1;
					if (num < 20)
						cout << "a skeleton appears" << endl
					else if (num < 50)
						cout << "a zombie appears" << endl;
					else if (num < 75)
						cout << "a spider appears" << endl;
					else
						cout << "the room is empty." << endl;


						void shop() {
						//remember to add "string inventory[10]" to your gobal variables up top!
						string input; //local to shop 
						do {
							cout << "Hi, welcome to my shop!" << end1;
							cout << "Enter k for key ($30), p for potion (50), 1 for lamp($80)" << endl;
							cout << "q to quit" << endl;
							cin >> input;
							if (input == "k") {
								inventory[0] = "key";
								cout << "you got a key" << endl;
								money -= 30; //take away money
							}
							else
								cout << "you don't have enough money!" << endl;
						}
							else if (input == "p") {
								inventory[0] = "lamp";
								cout << "you got a lamp!" << endl;
							}
						} while (input != "q");
					} 

                //Battle system definition 
				//1. have the monster hurt the player, have the player hurt the monster 
				//2. check if player has a weapon, if so, upgrade attack 1v1
				//3. pass the monster type, have different attacks for each monster
				//4. give the player choices to fight, magic or run(chance)
				//5. drop an item when monster dies
				void Battle(int MonsterHealth) {
					int damage;
					while (health > 0 && MonsterHealth > 0) {
						//the monster attacks
						if (inventory[6] == "shield")
							damage = rand() % 10;
						cout << "your shield blocks some of the damage!" << endl;
					}
					else {
						damage = rand() % 20;
						health -= damage;//take the damage
						cout << "the monster hurts you for " << damage << " damage." << endl;



						//player attacks monster
						if (inventory[5] == "sword") {
							cout << "you slice the enemy with your sword!" << endl;
							damage = rand() % 50 + 20;
						}
						else {
							damage = rand() % 40;
							cout << " you hit the monster with your first fist" << end;
						}//end battle loop

						damage = rand() % 20;
						cout << "the monster hurts you for " << damage << " damage." << endl;
						health -= damage;//take the damage
						//end battle loop

						if (MonsterHealth <= 0) {
							cout << "you destroyed the monster" << endl;
						}
						else cout << "you died." << endl;


						int main() {
							srand(time(NULL));
							while (1) {
								Monster();
								system("pause");
							}
						} 

						void NPC(int x) {
							int num;
							if (x == 1) {//----------------------------------------------------
								cout << "you encountereda friendly squirrel.!" << endl << endl;
								num = rand() % 3;
								if (num == 0) 
									cout << "Hi, nice weather today, ey!" << endl;								
								else if (num <= 0) {
									cout << "I like your shoes!" << endl;
								else if (num <= 1) {
								


								}
								else if (num <= 90) {//-------------------------------------
										cout << "beware of the spider!" << endl << endl;


								else if (num <= 90) {//-------------------------------------
										cout << "beware of the spider!" << endl << endl;
								}
							}


					


				
