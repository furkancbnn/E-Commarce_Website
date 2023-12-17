# E-Commarce_Website

![](e-commarce-new.gif)

**Kitap Listesi ve Sepet İşlevselliği Açıklaması**

Bu JavaScript kodu, bir kitap listesini görüntüleme ve sepete ekleme işlevselliği sağlar. Ayrıca, kullanıcıların kitap türlerine göre filtreleme yapabilmesine olanak tanır. Aşağıda, kodun temel işlevselliğini ve önemli bölümlerini açıklayan bir açıklama yer almaktadır:

1. **Global Değişkenler:**
    ```javascript
    let bookList = [],
        basketList = [];
    ```
   - `bookList`: Tüm kitapları içeren bir dizi.
   - `basketList`: Sepetteki kitapları içeren bir dizi.

2. **toastr Ayarları:**
    ```javascript
    toastr.options = { ... };
    ```
   - `toastr`: Kullanıcıya bilgilendirme mesajları gösteren bir kütüphanedir.
   - Bu kısımda, toastr'ın görünüm ve davranış ayarları yapılmıştır.

3. **Modal Göster/Gizle Fonksiyonu:**
    ```javascript
    const toggleModal = () => { ... };
    ```
   - Sepet modalını görüntülemek veya gizlemek için kullanılır.

4. **Kitap Verilerini Alma Fonksiyonu:**
    ```javascript
    const getBooks = () => { ... };
    ```
   - "products.json" dosyasından kitap verilerini alır.

5. **Yıldız Oluşturma Fonksiyonu:**
    ```javascript
    const createBookStars = (starRate) => { ... };
    ```
   - Kitapların yıldızlarını oluşturur.

6. **Kitap Kartları HTML Oluşturma Fonksiyonu:**
    ```javascript
    const createBookItemsHtml = () => { ... };
    ```
   - Kitap listesini HTML olarak oluşturur.

7. **Kitap Türleri HTML Oluşturma Fonksiyonu:**
    ```javascript
    const createBookTypesHtml = () => { ... };
    ```
   - Kitap türlerini filtreleme için HTML olarak oluşturur.

8. **Kitapları Filtreleme Fonksiyonu:**
    ```javascript
    const filterBooks = (filterEl) => { ... };
    ```
   - Kitapları belirli bir türe göre filtreler.

9. **Sepet İçeriğini Listeleme Fonksiyonu:**
    ```javascript
    const listBasketItems = () => { ... };
    ```
   - Sepetteki kitapları HTML olarak oluşturur ve görüntüler.

10. **Kitapı Sepete Ekleme Fonksiyonu:**
    ```javascript
    const addBookToBasket = (bookId) => { ... };
    ```
   - Belirli bir kitabı sepete ekler.

11. **Sepet İçeriğinden Kitabı Kaldırma Fonksiyonu:**
    ```javascript
    const removeItemToBasket = (bookId) => { ... };
    ```
   - Belirli bir kitabı sepetten kaldırır.

12. **Sepet İçeriğinde Kitap Miktarını Azaltma Fonksiyonu:**
    ```javascript
    const decreaseItemToBasket = (bookId) => { ... };
    ```
   - Belirli bir kitabın sepet içindeki miktarını azaltır.

13. **Sepet İçeriğinde Kitap Miktarını Artırma Fonksiyonu:**
    ```javascript
    const increaseItemToBasket = (bookId) => { ... };
    ```
   - Belirli bir kitabın sepet içindeki miktarını artırır.

14. **Kitap Listesi ve Filtreleme Butonlarını Oluşturma Fonksiyonu:**
    ```javascript
    setTimeout(() => { ... }, 100);
    ```
   - Sayfa yüklendikten sonra kitap listesini ve filtreleme butonlarını oluşturur.

## Kullanılan Teknolojiler

# HTML + CSS + JavaScript + Bootstrap + Jquery + Toastr

Bu kodlar, kitapları görüntülemek, filtrelemek ve sepete eklemek için temel bir altyapı sağlar. Projenin gereksinimlerine göre özelleştirilebilir.
