⚛️ C-DFT Reaktivite Tanımlayıcıları Hesaplama Aracı



Bu araç, kuantum kimyasal hesaplamalarda sıklıkla kullanılan Yoğunluk Fonksiyonel Teorisi (DFT) yaklaşımlarını temel alarak, bir molekülün reaktivite özelliklerini (İyonlaşma Enerjisi, Kimyasal Potansiyel, Kimyasal Sertlik vb.) Hückel/Koopmans yaklaşımıyla hesaplamak için tasarlanmış basit bir web tabanlı hesaplayıcıdır.



🌟 Özellikler



HOMO ve LUMO Enerji Girişi: Molekülün Yüksek Dolu Moleküler Orbital (HOMO) ve En Düşük Boş Moleküler Orbital (LUMO) enerji değerlerini girerek hesaplama yapma imkanı.

Birim Seçeneği: Enerji birimini Elektronvolt (eV) veya Hartree olarak seçebilme ve otomatik dönüştürme özelliği.

Temel Reaktivite Parametreleri: Molekülün temel reaktivite tanımlayıcılarını hızlıca hesaplar.

Kullanılan Formüller: Hesaplamalarda kullanılan Koopmans yaklaşımı ve C-DFT formülleri açıkça belirtilmiştir.

Parametre Açıklamaları: Hesaplanan her bir özelliğin (Kimyasal Potansiyel, Sertlik vb.) kimyasal anlamı hakkında kısa açıklamalar mevcuttur.

Responsive Tasarım: Mobil ve masaüstü cihazlarda kullanıma uygun modern ve temiz arayüz.



🛠️ Nasıl Çalışır?



Bu hesaplayıcı, Hückel ve Koopmans teoremlerine dayalı olarak C-DFT (Conceptual Density Functional Theory) reaktivite parametrelerini tahmin eder.



Girdiler


Aracın çalışması için sadece iki temel bilgi gereklidir:


1\.  $E\_{\\text{HOMO}}$: En Yüksek Dolu Moleküler Orbital Enerjisi.

2\.  $E\_{\\text{LUMO}}$: En Düşük Boş Moleküler Orbital Enerjisi.



\### Kullanılan Temel Formüller



Moleküler reaktivite özellikleri, Koopmans yaklaşımı kullanılarak aşağıdaki şekilde hesaplanır:



| Parametre | Formül | Açıklama |



| İyonlaşma Enerjisi ($I$) | $$I \\approx -E\_{\\text{HOMO}}$$ | Elektron verme eğilimi. |

| Elektron İlgisi ($A$) | $$A \\approx -E\_{\\text{LUMO}}$$ | Elektron alma eğilimi. |

| Kimyasal Potansiyel ($\\mu$) | $$\\mu = \\frac{E\_{\\text{HOMO}} + E\_{\\text{LUMO}}}{2}$$ | Elektron transferi eğilimi. |

| Kimyasal Sertlik ($\\eta$) | $$\\eta = \\frac{E\_{\\text{LUMO}} - E\_{\\text{HOMO}}}{2}$$ | Elektron sayısındaki değişime direnç. |

| Kimyasal Yumuşaklık ($S$) | $$S = \\frac{1}{\\eta}$$ | Yüksek reaktivite ile ilişkilidir. |

| Elektronegatiflik ($\\chi$) | $$\\chi = -\\mu$$ | Elektronları çekme gücü. |

| Elektrofiliklik İndeksi ($\\omega$) | $$\\omega = \\frac{\\mu^2}{2\\eta}$$ | Elektrofilik gücün ölçüsü. |



> Not:Tüm hesaplamalar dahili olarak Elektronvolt (eV) birimine dönüştürülerek yapılır ve sonuçlar eV cinsinden sunulur.



🚀 Bu araç, tamamen istemci taraflı HTML, CSS ve JavaScript ile geliştirilmiştir, bu nedenle herhangi bir sunucu veya derleme adımı gerektirmez.



1\.  `CDFT_TR.html` dosyasını indirin.

2\.  Dosyayı herhangi bir modern web tarayıcısında (Chrome, Firefox, Edge vb.) açın.

3\.  Gerekli $E\_{\\text{HOMO}}$ ve $E\_{\\text{LUMO}}$ değerlerini girin.

4\.  Giriş birimini (eV veya Hartree) seçin.

5\.  "Reaktivite Özelliklerini Hesapla" butonuna tıklayın.



Anında sonuçlar, açıklayıcı başlıklar ve birimlerle birlikte eV cinsinden görüntülenecektir.



---



👨‍💻 Geliştirici: Emre Can Buluz (In Silico Design)


