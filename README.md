# pat2-subtask2

#include <iostream>
using namespace std;
int main(){
    string message;
    string morse;

    // Morse code array	
    string code[26] =
    {
        ".-", "-...", "-.-.", "-..", ".", "..-.",
        "--.", "....", "..", ".---", "-.-", ".-..",
        "--", "-.", "---", ".--.", "--.-", ".-.",
        "...", "-", "..-", "...-", ".--", "-..-",
        "-.--", "--.."
    };
 cout << "Enter message in English (A-Z characters only): ";
    getline(cin, message);

    for(int i = 0; i < message.length(); i++)
    {
        char ch = message[i];

    return 0;
}
