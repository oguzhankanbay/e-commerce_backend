# E-Ticaret Websitesi Projesi

Bu proje, Node.js ve Express.js kullanılarak geliştirilmiş bir e-ticaret websitesidir. Proje, Stripe ödeme sistemi, kullanıcı kimlik doğrulama işlemi, kupon kullanımı gibi çeşitli özellikler içermektedir.

## Özellikler

- **Stripe Ödeme Sistemi**: Güvenli ödeme işlemleri için Stripe entegrasyonu.
- **Kimlik Doğrulama**: Kullanıcıların kayıt olması, giriş yapması ve çıkış yapması için kimlik doğrulama işlemi.
- **Kupon Kullanımı**: İndirimli alışveriş yapmak için kupon kodlarının kullanılabilirliği.

## Başlangıç

Bu adımlar, projeyi yerel makinenizde çalıştırmak için gereken adımları içerir.

3. **Çevre Değişkenlerini Ayarlayın**:
- Projenin kök dizininde `.env` adında bir dosya oluşturun.
- `.env` dosyasına aşağıdaki çevre değişkenlerini ekleyin:
  ```
  STRIPE_SECRET_KEY=your_stripe_secret_key
  SESSION_SECRET=your_session_secret
  MONGODB_URI=your_mongodb_uri
  ```
4. **Uygulamayı Başlatın**:
npm install
npm start
