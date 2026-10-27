# Emmet Nedir? — HTML & CSS'i Işık Hızında Yazmak

> **Ders:** Web Tasarımın Temelleri — Araştırma Ödevi (N° 04)  
> **Hazırlayan:** Yusuf Tabak  
> **Tarih:** 27 Ekim 2026

---

## 📄 Ödev Dosyaları ve Canlı Bağlantılar

| Format | Bağlantı | Açıklama |
| :--- | :--- | :--- |
| **📕 PDF Raporu (3 Sayfa)** | **[`emmet-nedir.pdf`](./emmet-nedir.pdf)** | Emmet'in çalışma mantığı, tarihçesi, 10 temel HTML operatörü, örtük etiketler ve CSS kısaltmaları |
| **🌐 Canlı İnteraktif Web Deneyimi** | **[tabakders.com.tr/odevler/04-emmet/](https://tabakders.com.tr/odevler/04-emmet/)** | Sıfırdan yazılmış JavaScript Emmet motoru, canlı Playground, AST ağacı, `Tab` editörü ve 9 seviyeli bulmaca oyunu |
| **📚 Tüm Ödev Arşivi (Lobi)** | **[tabakders.com.tr](https://tabakders.com.tr/)** | Dönem boyunca hazırlanan tüm interaktif ödevlerin kataloğu |

---

## ⚡ Özet: Emmet Nedir?

**Emmet** *(eski adıyla Zen Coding)*, CSS seçicilerine benzeyen kısa ifadeleri (*abbreviations*) tek bir `Tab` tuşuyla eksiksiz HTML ve CSS koduna dönüştüren açık kaynaklı bir geliştirici araç setidir.

```text
nav>ul>li.item$*3>a{Sayfa $}
```

Yukarıdaki **29 karakterlik** kısaltma yazılıp `Tab` tuşuna basıldığında Emmet aşağıdaki **158 karakterlik** HTML ağacını anında üretir (**%81 karakter tasarrufu**):

```html
<nav>
  <ul>
    <li class="item1"><a href="">Sayfa 1</a></li>
    <li class="item2"><a href="">Sayfa 2</a></li>
    <li class="item3"><a href="">Sayfa 3</a></li>
  </ul>
</nav>
```

---

## 🧭 PDF İçindekiler (3 Sayfa)

1. **Sayfa 1 — Tanım, Çalışma Mantığı ve Tarihçe**
   * Emmet nedir ve nasıl çalışır? (Parser → AST → HTML/CSS üretimi)
   * Neden Emmet kullanılır? *(Hız, Doğruluk, Bilişsel Odak, Evrensel Standart)*
   * Tarihçe: *Zen Coding (2008–2009, Vadim Makeev & Sergey Chikuyonok) → Emmet (2012) → VS Code Yerleşik Emmet 2.0 (2017) → Günümüz*
2. **Sayfa 2 — HTML Kısaltma Sözdizimi**
   * 10 Temel Operatör: `>` (Çocuk), `+` (Kardeş), `^` (Yukarı Çık), `*` (Çarpma), `()` (Gruplama), `#` (ID), `.` (Class), `[]` (Öznitelik), `{}` (Metin), `$` (Numaralandırma)
   * Bağlama Duyarlı Örtük Etiketler (*Implicit Tag Names*) ve Hazır Snippet'ler (`!`, `link:css`, `input:email`, `btn:s`, `lorem10`)
3. **Sayfa 3 — CSS Kısaltmaları, İleri Komutlar ve Kaynakça**
   * CSS Fuzzy Matching (`m10-20`, `d:f`, `jcsb`, `aic`, `w100p`, `bdrs50p`, `bd+`, `z10!`)
   * İleri Seviye Eylemler (*Wrap with Abbreviation*, *Balance*, *Go to Matching Pair*)
   * Altın Kurallar, VS Code `settings.json` İpuçları ve Resmi Kaynakça

---

## 🔗 Kaynaklar

* [Emmet Resmi Dokümantasyonu](https://docs.emmet.io/)
* [Emmet Resmi Cheat Sheet](https://docs.emmet.io/cheat-sheet/)
* [VS Code Emmet Rehberi](https://code.visualstudio.com/docs/languages/emmet)
* [emmetio/emmet GitHub Deposu](https://github.com/emmetio/emmet)

