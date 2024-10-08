While ve Do-While arasındaki fark pratiği :
// While Döngüsü

// While döngüsünde koşul sağlandığı zaman çalışır.Eğer ilk adımda koşul sağlanmıyorsa döngü çalışmaz

`Console.Write("Lütfen limit için değer giriniz : ");
int limit = Convert.ToInt32(Console.ReadLine());//kullanıcıdan limit değeri ister
int sayac = 0;
while (sayac <= limit) // koşulu döngünün başında kontrol eder.
{
    Console.WriteLine(" Ben bir Patika'lıyım.");
    sayac++;
}

//Do-While Döngüsü

//Do-while döngüsünden koşul sonda kontrol edildiği için yani koşul yanlış dahi olsa döngü en az bir kez çalışır.
Console.Write("Lütfen limit için değer giriniz : ");
int limit1 = Convert.ToInt32(Console.ReadLine());
int sayac1 = 0;

do 
{
    Console.WriteLine(" Ben bir Patika'lıyım.");
    sayac++;

}while (sayac1 <= limit1);//koşul kontrolü yapılır.`
