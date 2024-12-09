
# Micro-Frontend Project - Container Package

Bu proje, **Micro-Frontend** mimarisi kullanılarak oluşturulmuş bir **Container** modülüdür. Bu doküman, projenin nasıl çalıştığını, nasıl kurulacağını ve geliştirme ortamında nasıl kullanılacağını açıklamaktadır.

## Proje Yapısı

Bu modül, aşağıdaki teknolojileri kullanır:

- **React**: UI geliştirme için.
- **Webpack Module Federation**: Micro-frontend'leri entegre etmek için.
- **Babel**: Modern JavaScript kodlarını derlemek için.

---

## Kurulum

Projeyi yerel ortamınıza klonladıktan sonra gerekli bağımlılıkları yüklemek için aşağıdaki komutu çalıştırın:

```bash
npm install
```

---

## Geliştirme Ortamı

Geliştirme modunda projeyi çalıştırmak için:

```bash
npm start
```

Bu komut, projenin geliştirme sunucusunu başlatır ve varsayılan olarak `http://localhost:8080` adresinde çalışır.

---

## Üretim Ortamı

Projeyi üretim için derlemek için:

```bash
npm run build
```

Bu komut, projeyi optimize eder ve `dist/` dizininde statik dosyalar oluşturur.

---

## Katkıda Bulunma

Katkıda bulunmak için aşağıdaki adımları izleyebilirsiniz:

1. Bu projeyi fork edin.
2. Yeni bir dal oluşturun (`git checkout -b feature/yenilik`).
3. Değişikliklerinizi yapın ve commit edin (`git commit -m 'Yeni bir özellik eklendi'`).
4. Dalınızı push edin (`git push origin feature/yenilik`).
5. Bir **Pull Request** oluşturun.

---

## Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
