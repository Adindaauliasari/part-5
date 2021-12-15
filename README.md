#include "ncurses"

using namespace std;

int main(){

initscr();

    char Nama [20], Alamat[20], hobi[20];
	
	
	getstr(Nama);
	getstr(Alamat);
	getstr(hobi);
	
	
        printw ("\n");
	printw ("Nama    :%s \n", Nama );
	printw ("Alamat  :%s \n", Alamat );
    printw ("hobi    :%s \n", hobi );
    
	refresh();
	
	getch();
	
	endwin();
}
