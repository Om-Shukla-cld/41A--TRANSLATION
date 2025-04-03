# 41A--TRANSLATION
my approach to solve this question

#include <bits/stdc++.h>
using namespace std;
 
int main() {
    string s,q;
    cin >> s>>q;
 
    reverse(s.begin(), s.end());  
 
    cout << (s == q ? "YES" : "NO") << endl;  // Compare and print result
    return 0;
}

//input =code
        =edoc

        output=="YES"
