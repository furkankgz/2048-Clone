<h1 align="center"> 2048-Clone </h1>

<p align="center">
  <img src="https://user-images.githubusercontent.com/65050348/198876240-cba67657-fceb-4d98-a4c1-0a2a7f48e5bf.gif" alt="animated" />
</p>

<p align = "center">
<b> İlk olarak grid sistemini oluşturuyoruz. (4x4) <b> <br>
Grid oluşturulduktan sonra yapmamız gereken diğer adım grid içindeki sayı objelerini oluşturmak <br>
NumberController adlı script dosyası oluşturduk. <br>
Sayıların 2'nin katı olacağı şekilde print etmek istedik. <br>
Renklerin sayılara göre değişmesini istediğimiz için ScriptableObject tabanlı NumberColorData script dosyası oluşturduk. <br>
NumberColorData script dosyasını NumberController ile ilişkilendirdik. <br>
Number nesnemize tanımlamamız gereken dosyaları tanımladıktan sonra prefab haline getiriyoruz. <br>
NumberColorData script dosyamızdaki renk listemize renklerimizi ekledik. <br>
Bu kısımdan sonra yapmamız gereken bir sonraki durum sayılarımızı grid sistemindeki kutucuklara tam olarak oturacak şekilde spawn etmek ve hareket işlemini gerçekleştirmek. <br>
GameManager script dosyası oluşturduk. <br>
GameManager script dosyası içinde nesnemizin spawn kodunu yazdık. <br>
Grid sisteminde bir kutucuğa üst üste birçok kez spawn olmaması için GridManager script dosyamıza geliyoruz. <br>
GridManager script dosyasında grid sisteminde boş olan kutucukları bize gönderecek bir kod yazdık. <br><br>
GridManager; <br>

<p align="center">
  <img src="https://user-images.githubusercontent.com/65050348/198876548-bfc7f777-46e4-4b09-acb1-433a75d37a76.PNG" alt="animated" />
</p>
</p>
<p align = "center">
GameManager; <br>

<p align="center">
  <img src="https://user-images.githubusercontent.com/65050348/198876599-ab96c6b7-fdd4-4173-84ba-90ac0dbbc48d.PNG" alt="animated" />
</p> <br>
</p>

<p align = "center">
2048 oyununda genel olarak spawn olan sayılar ya "2" ya da "4" olarak spawn olurlar. Onu düzenledik. <br>

<p align="center">
  <img src="https://user-images.githubusercontent.com/65050348/198876670-c482da31-89f6-4179-9cfa-96e8f0d6161b.PNG" alt="animated" />
</p> <br>
</p>
<p align = "center">
Spawn olan sayıların hareket işlemini ekledik. <br>
Aynı olan sayıların merge işlemi yapıldı.
</p>

