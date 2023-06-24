<p align="center"><img src="https://img.shields.io/badge/IMTIAZ%20-GERMAIN-blue?style=for-the-badge&logo=appveyor" height="50"></p>
<p align="center"><img src="https://img.shields.io/github/issues/AitzazImtiaz/ImtiazGermain?style=social&logo=appveyor"><img src="https://img.shields.io/github/forks/AitzazImtiaz/ImtiazGermain?style=social&logo=appveyor"> <img src="https://img.shields.io/github/stars/AitzazImtiaz/ImtiazGermain?style=social&logo=appveyor"><img src="https://img.shields.io/badge/License%20-B%20License-blue?style=social&logo=appveyor"> <img src="https://img.shields.io/twitter/url?url=https%3A%2F%2Fgithub.com%2FAitzazImtiaz%2FImtiazGermain"></p>

<img align="right" src="https://github.com/AitzazImtiaz/Public-Images/blob/main/Untitled%20design.png" width="350" height="250">

ImtiazGermain is a C++ library, that will be used as a security feature in the cryptographical core of B Consortium, in dedication to mathematician Sophie Germain. The library being elementary in nature in the C++ ``long long`` limitation fits limited numbers until an overflow error occurs. Another limitation to consider is the use of OS limitations to be Windows Operating System of Windows 10+.

An implementation of the following code to check Germain prime of number 11 is as follows:
```
// using the .lib file

#include <iostream>
#include "ImtiazGermain.h"

using namespace std;

int main(){
  unsigned long long number;
  number = 11;
  if (ImtiazGermain::Germain::PrimeCheck(number) == true and ImtiazGermain::Germain::IsGermain(number) == true){
    cout << "A Germain prime!";
  } else{
    cout << "No!";
  }
  return 0;
}
```
Imtiaz Germain Prime is a recent discovery of 2022, which is add-on extension to Germain primes. To find Imtiaz Germain primes, here is an algorithm:
```
1. Take a Safe prime
2. Apply 2p + 1 on it to obtain a composite number
3. Apply 2p + 1 once more to obtain a prime number
```
Here is the implementation:
```
// using the .lib file

#include <iostream>
#include "ImtiazGermain.h"

using namespace std;

int main(){
  unsigned long long number;
  number = 11;
  if (ImtiazGermain::Germain::PrimeCheck(number) == true and ImtiazGermain::ImtiazGermain::IsImtiazGermain(number) == true){
    cout << "A Germain prime!";
  } else{
    cout << "No!";
  }
  return 0;
}
```
The following [guide](https://www.learncpp.com/cpp-tutorial/a2-using-libraries-with-visual-studio-2005-express/) is recommended when installing this library on Visual Studio.
