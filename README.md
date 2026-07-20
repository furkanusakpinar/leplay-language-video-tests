<div align="center">
  <h1>Leplay: AI-Powered Language Learning</h1>
  <p>Learn English through highly curated, perfectly translated YouTube movie and TV show clips.</p>

  [![React](https://img.shields.io/badge/React-18.x-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
  [![Vite](https://img.shields.io/badge/Vite-4.x-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev/)
  [![Groq](https://img.shields.io/badge/Llama_3.3-AI-FF4A00?style=for-the-badge)](https://groq.com)
</div>

<br />

## 📌 Overview

**Leplay**, kullanıcıların YouTube videolarındaki doğal ve akıcı diyalogları dinleyerek İngilizce öğrenmelerini sağlayan modern ve etkileşimli bir dil öğrenme platformudur. Klasik "Leplay" deneyimini yeniden yaratırken, arka planda çalışan otomatize bir **Yapay Zeka (AI) İşleme Boru Hattı (Processing Pipeline)** ile süreci güçlendirir.

Manuel olarak sahne ayıklamak ve çeviri yapmak yerine, arka plan işlemcisi **Groq üzerindeki Llama 3.3** modelini çok aşamalı bir yapıda kullanarak en uygun, kısa ve etkili sahneleri tespit eder; bunları kusursuz bir şekilde çevirir ve test soruları için akıllıca yanlış seçenekler (distractors) üretir.

![Preview](src/assets/sitedenss.png)

---

## ✨ Features

- 🤖 **Automated Scene Extraction**: Herhangi bir YouTube URL'sini yapıştırın; yapay zeka altyazıları otomatik olarak tarar ve dil öğrenimi için en uygun 1-2 cümlelik sahneleri ayıklar.
- 🌐 **Flawless Localization**: Groq AI, adeta bir Netflix altyazı editörü gibi çalışarak hiçbir cümleyi atlamadan doğal ve deyimsel (idiomatic) Türkçe çeviriler sunar.
- 🎯 **Clever Distractors**: Kullanıcının kavrama yeteneğini test etmek için orijinal seçeneğe benzeyen ancak anlamı değiştiren mantıklı çeldiriciler oluşturur.
- ⏱️ **Perfect Video Sync**: YouTube IFrame Player API ile doğrudan entegrasyon sayesinde videolar, sahnenin bittiği milisaniyede otomatik olarak duraklatılır.
- 🎨 **Premium UI/UX**: React ve Framer Motion ile inşa edilmiş; glassmorphism, akıcı animasyonlar ve responsive karanlık mod (dark-mode) tasarımına sahiptir.

---

## 🚀 Getting Started

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları takip edin.

### 1. Prerequisites
- **Node.js**: Sisteminizde Node.js (v18 veya üzeri) yüklü olduğundan emin olun.
- **Groq API Key**: Otomatik video işleme sistemi Llama 3.3 modelini kullanır. Groq'tan ücretsiz bir API anahtarı almanız gerekmektedir.

### 2. Groq AI Setup
Otomatik video işleme boru hattının çalışması için Groq gereklidir:
1. [Groq Console](https://console.groq.com/) adresine gidin ve bir hesap oluşturun.
2. Sol menüden **API Keys** bölümüne geçin.
3. **Create API Key** butonuna tıklayarak yeni bir anahtar oluşturun ve kopyalayın.

### 3. Project Setup

Projeyi klonladıktan veya indirdikten sonra, terminal üzerinden proje klasörüne gidin ve gerekli bağımlılıkları yükleyin:

```bash
# Bağımlılıkları yükleyin
npm install
