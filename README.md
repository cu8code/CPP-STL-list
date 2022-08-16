# everything about CPP STL;

## Constructors

```cpp
#include <bits/stdc++.h>
#include <iostream>

struct node {
  std::string adress;
  float roll_number;
  node(std::string adress_, float roll_number_) {}
};

int main() {
  node a = node("some", 90);
  return 0;
}
```

## struct;

```cpp
#include <bits/stdc++.h>
#include <iostream>

struct node {
  std::string adress;
  float roll_number;
};

int main() {
  node a;
  a.adress = "baba";
  a.roll_number = 90;
  return 0;
}
```

## Fuking NameSpaces;

```cpp
#include <iostream>

namespace rag {
  int b = 90;
  int getName(){
    return 90 * b;
  }
}

int main(){
  std::cout << rag::getName(); // output is 8100
  return 0;
}
```

## to create a vectors;

```cpp
#include <vector>
int main(){
  std::vector<int> A;
  return 0;
}
```

## to create string;

```cpp
#include <bits/stdc++.h>
int main(){
  std::string B;
  return 0;
}
```

## print some thigh;

```cpp
#include <iostream>

int main(){
  std::cout << "ome";
  return 0;
}
```
