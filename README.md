Snake Game

Proje Açıklaması
Bu proje, Java kullanılarak geliştirilen klasik bir yılan oyunu uygulamasıdır. Oyuncular, yılanı yön tuşlarıyla kontrol ederek ekrandaki yiyecekleri yemeye çalışırlar. Her yiyecek yendikçe yılanın boyu uzar ve oyunun amacı, yılanın kendisine veya ekranın kenarlarına çarpmasını önlemektir.

Özellikler

Yılan Hareketi: Yılanın yönü, ok tuşları ile değiştirilir ve yılanın başı hareket ederken, gövdesi takip eder.

Yiyecek: Yiyecek rastgele bir konumda belirir. Yılan bu yiyeceği yediğinde, yılanın uzunluğu artar ve yeni bir yiyecek yerleştirilir.

Çarpışma: Yılanın kendisine veya ekranın kenarlarına çarpması durumunda oyun biter.

Skor: Yılanın uzunluğu skor olarak gösterilir.

Gereksinimler

Java Development Kit (JDK): Projeyi derlemek ve çalıştırmak için Java JDK 8 veya üstü gereklidir.

Swing Kütüphanesi: GUI bileşenlerini kullanmak için Java Swing kütüphanesi gereklidir.

Kurulum ve Çalıştırma

Kodun Yüklenmesi:

Kodunuzu bir Java IDE (IntelliJ IDEA, Eclipse vb.) ya da bir metin düzenleyiciye yapıştırın ve dosyayı SnakeGame.java olarak kaydedin.

Derleme:

Komut satırını açın ve dosyanın bulunduğu dizine gidin.

Java dosyasını derlemek için şu komutu çalıştırın:

javac SnakeGame.java

Çalıştırma:

Derlenmiş sınıf dosyasını çalıştırmak için şu komutu kullanın:

java SnakeGame

Kullanım

Yılanı Kontrol Etme:

Yılanı yukarı, aşağı, sola veya sağa hareket ettirmek için ok tuşlarını kullanın.

Yiyecek Yeme:

Yılanın yiyeceği yemesiyle yılanın uzunluğu artar. Yiyecekler rastgele yerleştirilir.

Oyun Sonu:

Yılan kendisine veya ekranın kenarlarına çarptığında oyun sona erer ve toplam skor (yılanın uzunluğu) ekranda gösterilir.

Kod Açıklamaları

Tile Class: Oyun tahtasındaki her bir hücreyi temsil eder. x ve y koordinatları içerir.

SnakeGame Class: Ana oyun mantığını içerir. Yılanın hareketi, yiyecek yerleşimi, çarpışma kontrolü ve oyun döngüsünü yönetir.

paintComponent(Graphics g): Oyun ekranını çizmek için kullanılır.

draw(Graphics g): Yılanı, yiyeceği ve oyunun grid çizgilerini çizer.

move(): Yılanın hareketini günceller ve çarpışmaları kontrol eder.

collision(Tile tile1, Tile tile2): İki Tile nesnesinin çarpışıp çarpışmadığını kontrol eder.

actionPerformed(ActionEvent e): Her döngüde oyunun güncellenmesini sağlar.

keyPressed(KeyEvent e): Klavye tuşlarına basıldığında yılanın yönünü değiştirir.

İletişim

Sorularınız veya geri bildirimleriniz için benimle iletişime geçebilirsiniz:

E-posta: alitokmak3535@gmail.com

GitHub: AlITOKMAK35 - https://github.com/AlITOKMAK35 -
