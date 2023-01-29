```c++
#include <Windows.h>
#include <string>

int main()
{
	std::cout << "\n\n" << R"(
	 ,_     _
	 |\\_,-~/
	/ _  _ |    ,--.
	(  @  @ )   / ,-'          1. Name
	 \  _T_/-._( (
	 /         `. \            2. Specialties
	|         _  \ |
	\ \ ,  /      |            3. Contact
	 || |-_\__   /
	((_/`(____,-'
	)" << '\n';

	std::cout << ("\n	?: ");

    int option;
    	case 1:
		std::cout << ("    browlete    ");
		std::cin >> username;
		break;
    case 2:
		std::cout << ("    none yet :(    ");
		std::cin >> Specialties;
		break;
	case 3:
		std::cout << ("    browlete#1126    ");
		std::cin >> Discord;
		std::cout << ("\n    steamcommunity.com/id/browlete    ");
		std::cin >> steam;
		break;
	default:
		std::cout << ("\n\n Invalid Selection");
		Sleep(3000);
		exit(0);
	}
}
```
