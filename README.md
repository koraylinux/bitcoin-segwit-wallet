## Bitcoin Adres Üreticisi

#### Özellikler:

*  bech32, segwit (p2sh-p2wpkh) ve legacy (p2pkh) adresler üretimi
*  Çoklu adres üretimi
*  Özel anahtar detaylarını inceleme
*  Özel anahtar şifreleme ve şifre çözme (BIP38)
*  Hazır dizayn edilmiş temalar ile kağıt cüzdan yazdırma
*  BIP39 mnemonic seed üretimi
*  BIP39 mnemonic seed detaylarını inceleme
*  Tüm yazılım tek bir html dosyasına işlenir

#### Yönergeler

Soğuk cüzdan üreticisini çevrimiçi sadece demo amaçlı kullanın. Uzun vadeli kullanımlarınız için üreticinin GitHub sayfasına gidin ve bilgisayarınıza indirin. Üreticiyi çalıştırmadan önce bilgisayarınızın internet bağlantısını kesinlikle kesmenizi öneriyorum.

Yeterli sayıda cüzdan oluşturup yazdırdıktan sonra yazıcının belleğini temizleyin. Bunun için yazıcının fişini çekip 5 dakika kapalı tutmanız yeterlidir. Yazdırdığınız cüzdanlarla birlikte, dilerseniz pdf olarak kaydettiğiniz cüzdan dosyalarını da bir usb bellek içinde saklayabilirsiniz. Kaydettiğiniz PDF dosyalarınızı usb belleğe taşımadan internet bağlantınızı aktif hale getirmeyin. Dosyaları güvenli bir ortamda sakladığınızdan emin olun ve en yakınlarınızla dahi paylaşmayın. Bitcoin özel anahtarları kişiye özeldir ve asla paylaşılmamalıdır.

Genel Adres ödeme almak içindir. Dilediğiniz kadar kişiyle paylaşabilirsiniz ancak her ödeme için yalnızca 1 adres kullanmanızı tavsiye ediyorum. Ödemenizi alıp işinizi tamamladığınızda başka bir adres oluşturun. Böylece işlemleriniz başkaları tarafından takip edilemez ve mümkün olduğunca anonim kalırsınız.

Özel Anahtar coinlerinize ulaşmanın en basit yoludur, bu yüzden kesinlikle bir başkasının ulaşamayacağı yerde saklayın. Ayrıca soğuk cüzdan üreticisi size mnemonic seed vermediği için özel anahtarı kaybetmeniz durumunda coinlerinize de elveda demek zorunda kalırsınız. Kendi cüzdanınızdaki paraya ne kadar değer veriyorsanız, özel anahtara da aynı şekilde davranın.


#### Kullanılan kütüphaneler:
*  BigNumber (BN): https://github.com/indutny/bn.js
*  crypto-js: https://github.com/brix/crypto-js
*  QR code generator: https://github.com/kazuhikoarase/qrcode-generator
*  Scrypt: https://github.com/dchest/scrypt-async-js
*  setImmediate.js: https://github.com/YuzuJS/setImmediate