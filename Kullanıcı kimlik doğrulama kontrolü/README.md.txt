Kullanıcı Kimlik Doğrulama Kontrolü:
Bu basit Python uygulaması, kullanıcı adı (username), parola (password) ve doğrulama durumu (is_verified) bilgilerini kontrol ederek girişin başarılı olup olmadığını belirler.

Çalışma Mantığı:
Program üç koşulu aynı anda kontrol eder:
-username boş değil
-password boş değil
-is_verified değeri True
Tüm şartlar sağlanırsa:Login successful
Herhangi biri sağlanmazsa:Login failed

Not:
Bu kod yalnızca eğitim amaçlıdır. Gerçek bir sistemde:
Parolalar şifrelenmeli
Kullanıcı bilgileri dış kaynaktan alınmalı
Güvenli kimlik doğrulama yöntemleri kullanılmalıdır
