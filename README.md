# SealedClassDemo

Sealed sınıflar kalıtım vermeyen sınıflardır. Bir sınıfın başka sınıflara kalıtım vermesini engellemek için sealed komutu kullanılır. Sealed classları bir çeşit güvenlik önlemi olarak düşünebiliriz. Yanlışlıkla türetilmeleri engellenmiş oluyor.

Bu komut kullanıldığında sınıfınızdan başka hiçbir sınıfa kalıtım alınamaz. Ancak, yeni türetilen bir değişken yardımıyla sınıfın metotları çağrılabilir.

Sealed komutunun kullanım şekli şöyledir:

```C#
sealed class Temel
 {
 // Program kod satırları
 }
```
