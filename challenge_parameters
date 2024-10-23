# exercice1
#include <iostream>
#include <vector>

void testFunction(std::vector<int> params) {
    std::cout << "Function called with " << params.size() << " parameters." ;
}

int main() {
    try {
        std::vector<int> params;
        int count = 1;

        while (true) {
            params.push_back(count);  
            testFunction(params);     
            count *= 3;               
        }
    } catch (const std::bad_alloc& e) {
        std::cerr << "Memory allocation error: " << e.what() << std::endl;
    }

    return 0;
}

