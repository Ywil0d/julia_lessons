# Julia Lessons
![Julia](https://img.shields.io/badge/Language-Julia-9558B2?style=for-the-badge&logo=julia)
![Level](https://img.shields.io/badge/Level-Beginner-success?style=for-the-badge)
![Purpose](https://img.shields.io/badge/Purpose-Education-blue?style=for-the-badge)

Julia, **yüksek performanslı**, **dinamik** ve özellikle  
**bilimsel hesaplama, veri analizi ve mühendislik** alanlarında kullanılan güçlü bir programlama dilidir.
Python kadar kolay ama C kadar hızlı olmasıdır.

### İlk Cümlemiz
Julia'da geleneğimizi yerine getirelim:

```
println("Merhaba Dünya")
```
### Değişkenler ve Veri Tipleri

Python'daki gibi türünü tanıtmadan değişkenler oluşturulabilir.
```
x = 42       # Integer
y = 3.14     # Float
name = "Julia" # String

println("x: $x, y: $y, name: $name")
```
### Döngüler ve Koşullar
#### Döngü
```
for i in 1:5
    println("i: $i")
end
```

#### Koşul
```
if x > 50
    println("x büyük 50'den")
else
    println("x küçük veya eşit 50'ye")
end
```
### Fonksiyonlar
```
function toplama(a, b)
    return a + b
end

println(toplama(5, 3))  # 8
```

### Matematiksel Hesaplamalar
```
f(x) = (2 * x + 5) * 2
println(f(40))
```

### Grafik - Ağırlıklı Grafik Örneği
Julia’da ağırlıklı grafikler için ***Graphs.jl*** ve ***SimpleWeightedGraphs.jl*** paketleri kullanılır.
```
using Graphs
using SimpleWeightedGraphs

# 4 düğümlü ağırlıklı grafik
g = SimpleWeightedGraph(4)

add_edge!(g, 1, 2, 3.0)
add_edge!(g, 2, 3, 5.0)
add_edge!(g, 3, 4, 2.0)
add_edge!(g, 4, 1, 4.0)
```

<img width="399" height="264" alt="resim" src="https://github.com/user-attachments/assets/c89ed2af-b0e1-4d89-8c4a-f564109d55f7" />
&nbspㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ
‎<img width="600" height="400" alt="6fd4b7057b8c22063af20d50898e06edbc421be4" src="https://github.com/user-attachments/assets/c6311959-a6ea-4510-aaf7-97caf90947d3" />

