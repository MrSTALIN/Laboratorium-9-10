#include<iostream>
#include "stdafx.h"
#include "bazowa.h"
#include "pochodna.h"

using namespace std;

string PL(const char * text)
{
	string result;
	for (; *text; text++)
		switch (*text)
	{
		case 'ą': result += static_cast < char >(0xa5); break;
		case 'ć': result += static_cast < char >(0x86); break;
		case 'ę': result += static_cast < char >(0xa9); break;
		case 'ł': result += static_cast < char >(0x88); break;
		case 'ń': result += static_cast < char >(0xe4); break;
		case 'ó': result += static_cast < char >(0xa2); break;
		case 'ś': result += static_cast < char >(0x98); break;
		case 'ż': result += static_cast < char >(0xbe); break;
		case 'ź': result += static_cast < char >(0xab); break;
		case 'Ą': result += static_cast < char >(0xa4); break;
		case 'Ć': result += static_cast < char >(0x8f); break;
		case 'Ę': result += static_cast < char >(0xa8); break;
		case 'Ł': result += static_cast < char >(0x9d); break;
		case 'Ń': result += static_cast < char >(0xe3); break;
		case 'Ó': result += static_cast < char >(0xe0); break;
		case 'Ś': result += static_cast < char >(0x97); break;
		case 'Ż': result += static_cast < char >(0xbd); break;
		case 'Ź': result += static_cast < char >(0x8d); break;
		default: result += *text; break;
	}
	return result;
}

int _tmain(int argc, _TCHAR* argv[])
{
	bazowa b;
	pochodna p;

	b.pochodze();
	p.pochodze();

	bazowa * bptr = &p;
	bptr->pochodze(); 

	getchar();
	cout<< PL ("Nciśnij co kolwiek, aby wyjść z konosli");
	getchar();
}
