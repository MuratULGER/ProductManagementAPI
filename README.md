
# ProductManagementAPI

ProductManagementAPI, ASP.NET Core kullanılarak geliştirilen, katmanlı mimariye sahip bir ürün yönetim API'sidir.  
Entity Framework Core ile InMemory Database üzerinde çalışır ve Swagger UI ile kolayca test edilebilir.

## Özellikler
- Ürün ekleme, listeleme, güncelleme, silme (CRUD işlemleri)
- Katmanlı mimari: API, Application, Domain, Infrastructure
- Entity Framework Core (InMemory veritabanı kullanımı)
- Swagger UI dokümantasyonu
- Temiz ve ölçeklenebilir kod yapısı

## Kullanılan Teknolojiler
- ASP.NET Core 8
- Entity Framework Core 8
- Swagger / OpenAPI
- Katmanlı Mimari

## Başlangıç

1. Projeyi klonlayın:
   ```bash
   git clone https://github.com/kendi-repo-linkin/ProductManagementAPI.git
   ```

2. API projesine geçin:
   ```bash
   cd ProductManagementAPI/ProductManagementAPI.API
   ```

3. Uygulamayı çalıştırın:
   ```bash
   dotnet run
   ```

4. Tarayıcınızdan Swagger arayüzüne erişin:
   ```
   https://localhost:{port}/swagger
   ```

## API Endpointleri

| Metod | URL | Açıklama |
|:-----:|:---:|:--------:|
| GET    | /api/products       | Tüm ürünleri getirir |
| GET    | /api/products/{id}  | Id'ye göre ürün getirir |
| POST   | /api/products       | Yeni ürün oluşturur |
| PUT    | /api/products/{id}  | Ürünü günceller |
| DELETE | /api/products/{id}  | Ürünü siler |

## Geliştirici

**Murat ÜLGER**  
ASP.NET Core, Entity Framework Core, Katmanlı Mimari Uzmanı

- GitHub: [github.com/muratulger](https://github.com/muratulger)  
- Mail: [murat.ulger@yandex.com](mailto:murat.ulger@yandex.com)

---

> Bu proje, ileriye dönük daha büyük freelance işler ve portföy çalışmaları için örnek bir altyapı sağlamaktadır.
