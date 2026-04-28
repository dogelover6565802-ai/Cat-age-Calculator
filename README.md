# Cat-age-Calculator
This is a cat age calculator and also my first project. I'm putting on GitHub!It is in lang C++.

#include <iostream>
int main() {
  
  /*This is code to calculate the age of a cat in human years containing a special message 
  if its 10 or more years old or a asburd number */
 
  int catage;
  int cattotal;
 
  std::cout<<"Input cat age to find the age of your furry friend in human years. ";
  std::cin>>catage;
  
  if (catage == 1){
    std::cout<< "Your cat is 15 human years old.";
}
else if (catage==2){
  std::cout<<"Your cat is 24 human years old";
}
else if(catage>=3){
  cattotal = (catage-2)*4+24;
  std::cout<<"Your cat is "<<cattotal<<" human years old";
}
else if(catage >= 10) {
  std::cout<<"Your cat is old at a whopping "<<cattotal<<" in human years";
}
else if(catage >= 35) {
  std::cout<<"Say WALLAHI BRO^2";
}

}
