Randevu Sistemi v2 (Legacy) 🗓️
Bu proje, ilk randevu sistemi çalışmamın üzerine inşa ettiğim, "daha iyi nasıl yaparım?" sorusuna cevap aradığım gelişim aşamasıdır. İlk versiyondaki eksikleri fark edip, daha standartlara uygun bir yapı kurmaya çalıştığım bir ara duraktır.

🔄 v1'den Farkları ve Geliştirmeler
İlk versiyona kıyasla bu projede şu kritik değişiklikleri yaptım:

Deployment Hazırlığı: Port yönetimini process.env.PORT ile dinamik hale getirdim. Bu sayede uygulamayı sadece yerelde değil, bulut sunucularda (Heroku, Render vb.) çalışabilir kıldım.

Modern JavaScript: Veri çekme işlemlerinde async/await yapısına geçerek asenkron süreçleri daha okunaklı ve güvenli hale getirdim.

API Güvenliği ve CORS: Sunucu tarafında cors middleware'ini kullanarak API isteklerini standartlara uygun şekilde yapılandırdım.

Dosya Organizasyonu: Statik dosyaları (public/) ve sunucu mantığını birbirinden ayırarak daha derli toplu bir klasör mimarisine geçtim.

🛠️ Teknolojiler
Backend: Node.js, Express.js

Frontend: HTML5, CSS3, JavaScript (ES6+ Fetch API)

Middleware: CORS
