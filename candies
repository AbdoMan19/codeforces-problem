#include"bits/stdc++.h"
using namespace std;
int main(){
    auto t{0},i{0},n{0},a{0};
    cin>>t;
    vector<int>inputs;
    vector<string>outputs;
    while (i<t) {
        cin >> n;
        int h = 0;
        while (h < n) {
            cin >> a;
            inputs.push_back(a);
            h += 1;
        }
        sort( inputs.begin(), inputs.end() );
        if (inputs.size() == 1 && inputs[0] == 1) {
            outputs.push_back("yes");
        } else if (inputs[inputs.size()-1] - inputs[inputs.size()-2] == 1||inputs[inputs.size()-1] - inputs[inputs.size()-2] == 0) {
            outputs.push_back("yes");
        } else {
            outputs.push_back("no");
        }

        inputs.clear();
        i += 1;
    }
    for(auto l:outputs){
        cout<<l<<endl;
    }
    return 0;
}

