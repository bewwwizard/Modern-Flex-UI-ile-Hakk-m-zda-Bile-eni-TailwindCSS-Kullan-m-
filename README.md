Modern Flex UI

Bu proje, modern bir HTML ve TailwindCSS yapısı kullanarak tasarlanmış bir "Hakkımızda" bileşenini içerir. Bileşen, responsive bir tasarım sunarak hem masaüstü hem de mobil cihazlarda kusursuz bir görünüm sağlar.

Kullanılan Teknolojiler

HTML5: Yapı iskeleti oluşturulmuştur.

TailwindCSS: Stil vermek için kullanılmıştır. Flexbox ve grid sistemleri ile modern bir görünüm sağlanmıştır.

Özellikler

Responsive Tasarım: Tüm ekran boyutlarında uyumlu.

Modern Görünüm: Yuvarlatılmış köşeler, gölge efektleri ve tipografi detayları.

Kolay Özelleştirme: TailwindCSS sınıfları ile kolayca değiştirilebilir.

Bileşen Yapısı

1. Görsel Alanı

Görsel, yuvarlatılmış köşeler ve gölge efektleriyle merkeze yerleştirilmiştir.

Mobil cihazlarda tam genişlikte, masaüstünde yarım genişlikte gösterilir.

2. Metin Alanı

"Hakkımızda" başlığı üstte küçük bir şerit olarak vurgulanır.

Büyük ve kalın yazı tipleriyle modern bir başlık tasarımı sunar.

Alt metin açıklayıcı bir paragraf olarak tasarlanmıştır.

Kullanım

TailwindCSS Kurulumu: Bu projeyi kullanmak için TailwindCSS kütüphanesini yükleyin.

TailwindCSS yükleme talimatları için resmi dokümantasyonu ziyaret edebilirsiniz.

HTML Kopyalama: Aşağıdaki kodu projenize ekleyin:

<section class="flex flex-col md:flex-row items-center max-w-screen-xl mx-auto py-10 px-4 space-y-6 md:space-y-0 md:space-x-8">
  <div class="w-full md:w-1/2 flex justify-center">
    <img src="https://i.imgur.com/WbQnbas.png" alt="About us" class="rounded-lg shadow-lg object-cover">
  </div>
  <div class="w-full md:w-1/2">
    <div class="text-center md:text-left">
      <p class="text-sm text-gray-500 uppercase tracking-widest border-b-2 border-indigo-600 inline-block mb-4">
        Hakkımızda
      </p>
      <h2 class="text-3xl md:text-4xl font-extrabold text-gray-900 leading-tight">
        Şirketimiz Hakkında <span class="text-indigo-600">Bilgi</span>
      </h2>
      <p class="mt-4 text-gray-700 leading-relaxed">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid, commodi
        doloremque, fugiat illum magni minus nisi nulla numquam obcaecati placeat quia, repellat tempore
        voluptatum.
      </p>
    </div>
  </div>
</section>

Özelleştirme: TailwindCSS sınıflarını ihtiyacınıza göre düzenleyin.

Lisans

Bu proje MIT lisansı altında sunulmaktadır. Daha fazla bilgi için LICENSE dosyasına bakınız.

