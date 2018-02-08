# 11849---CD

#include <iostream>

#include <bits/stdc++.h>

using namespace std;

int main()
{

    int u , c;

    while(cin >> u >> c && u && c)
    {

        set<int> s;
        for(int i=0 ,num /*intialized over here */;i<(u+c) ;i++)
        {
            cin >> num;
            s.insert(num);
        }
        cout << ((u+c)- s.size()) << endl;
    }
    return 0;
}
