---
layout: default
---

## Wprowadzenie do JavaSrcipt:

## 1.Zrozumienie podstaw:

```
C++ to wszechstronny język programowania ogólnego przeznaczenia,
 który jest często używany do tworzenia aplikacji systemowych, 
 oprogramowania inżynieryjnego i gier
```

## 2.Zmienne i typy danych:

```
Zmienne w C++ są używane do przechowywania danych. 
Deklarujesz zmienną, podając jej typ oraz nazwę. Na przykład:
```
```php
int liczba = 10;
double przecinek = 3.14;
char znak = 'A';
std::string tekst = "Witaj, Świecie!";
```

## 3.Funkcje:
```
Funkcje w C++ są używane do organizowania kodu w bloki, które 
mogą być wielokrotnie wywoływane. Przykład prostej funkcji: 
```
```php
#include <iostream>

void witaj(std::string imie) {
    std::cout << "Witaj, " << imie << "!" << std::endl;
}

int main() {
    witaj("Jan");
    return 0;
}
```
## 4.Warunki:
```
Warunki w C++ pozwalają na wykonywanie różnych operacji 
w zależności od spełnienia określonych warunków. 
Użyj instrukcji warunkowych if, else if i else. Przykład:
```
```php
#include <iostream>

int main() {
    int liczba = 10;

    if (liczba > 0) {
        std::cout << "Liczba jest dodatnia." << std::endl;
    } else if (liczba == 0) {
        std::cout << "Liczba wynosi zero." << std::endl;
    } else {
        std::cout << "Liczba jest ujemna." << std::endl;
    }

    return 0;
}
```

## 5.Pętle:
```
Pętle pozwalają na wielokrotne wykonywanie określonych operacji.
 W C++ masz pętle for, while i do...while. Przykład:
```
```php
#include <iostream>

int main() {
    for (int i = 0; i < 5; i++) {
        std::cout << "Liczba: " << i << std::endl;
    }

    return 0;
}
```