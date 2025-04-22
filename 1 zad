#include <iostream>
#include <string>

class StringManipulator {
    public:
    static std :: string insertSpaces(const std::string& input){
        std::string result;
        for (char c : input) {
            result += c;
            result += ' ';
        }
        if (!result.empty()) {
            result.pop_back();
        }
        return result;
    }
};
int main(){
    std::string text;
    std::cout <<"Введи текст:";
    std::getline(std::cin,text);
    
    std::string result =  StringManipulator::insertSpaces(text);
    std::cout <<"Результаты:" << result <<std::endl;
    
    return 0;
}
