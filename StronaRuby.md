---
layout: default
---

## Wprowadzenie do JavaSrcipt:

## 1.Zrozumienie podstaw:

```
Ruby to dynamiczny, obiektowy język programowania, 
który jest łatwy do nauki i używania. 
Jest często używany do tworzenia aplikacji internetowych, 
szczególnie z użyciem frameworka Ruby on Rails.
```

## 2.Zmienne i typy danych:

```
Zmienne w Ruby są dynamicznie typowane, co oznacza, 
że nie musisz określać ich typu przy deklaracji. Przykład:
```
```ruby
liczba = 10

tekst = "Witaj, Świecie!"
```

## 3.Funkcje:
```
Funkcje, nazywane metodami, są definiowane za 
pomocą słowa kluczowego `def`. Przykład:
```
```ruby
def witaj (imie)

  puts "Witaj, #{imie}!"

end

witaj("Jan")

```
## 4.Warunki:
```
Warunki w Ruby są podobne do tych w innych językach programowania. 
Używamy `if`, `elsif`i `else` do kontroliprzepływu. Przykład:
```
```ruby
liczba = 10

if liczba > 0

  puts "Liczba jest dodatnia."

elsif liczba == 0

  puts "Liczba wynosi zero." else puts "Liczba jest ujemna." end
```

## 5.Pętle:
```
Ruby oferuje różne sposoby tworzenia pętli, takie jak `while`, `until`i`for`.
Najczęściej używaną jest metoda `each` na tablicach. Przykład:
```
```ruby
5.times do i
puts "Liczba: #{i}"

end
```