---
layout: default
---

## Wprowadzenie do JavaSrcipt:

## 1.Zrozumienie podstaw:

```
Swift to nowoczesny, szybki i bezpieczny język programowania stworzony przez Apple. 
Jest używany do tworzenia aplikacji na platformy iOS, macOS, watchOS i tvOS.
```
## 2.Zmienne i typy danych:

```
W Swift zmienne deklaruje się za pomocą `var`,
 a stałe za pomocą `let`. Przykład:
```
```swift
var liczba = 10 
let tekst = "Witaj, Świecie!"
```

## 3.Funkcje:
```
Funkcje w Swift są definiowane za pomocą 
słowa kluczowego `func`. Przykład:
```
```swift
func witaj (imie: String) {
 print("Witaj, \(imie)!") 
 }
witaj (imie: "Jan")
```
## 4.Warunki:
```
Warunki w Swift są podobne do tych w innych językach programowania. 
Używamy `if`, `else if`i `else` do kontroli przepływu. Przykład:
```
```swift
let liczba = 10

if liczba > 0 {

print("Liczba jest dodatnia.")

} else if liczba == 0 {

print("Liczba wynosi zero.")

} else {

print("Liczba jest ujemna.")

}
```

## 5.Pętle:
```
Swift oferuje różne sposoby tworzenia pętli, takie jak `for`, 
`while` i `repeat-while`. Przykład użycia pętli `for`:
```

```swift
for i in 0..<5 { 
print("Liczba: \(i)")

}
```