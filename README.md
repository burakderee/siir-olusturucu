# 🪶 LLM İnce Ayar (Fine-Tuning) ile Şiir Üretimi

Bu proje, Doğal Dil İşleme (NLP) teknikleri ve Büyük Dil Modelleri (LLM) kullanılarak belirli bir şairin yapısal stilini, kelime dağarcığını ve ritmini analiz edip o tarzda özgün şiirler üretebilen kapsamlı bir makine öğrenmesi çalışmasıdır.

Çalışma, özellikle Orhan Veli Kanık'ın serbest ölçülü ve kendine has şiir yapısı referans alınarak kurgulanmış olup; farklı dil modeli mimarilerinin bu edebi üslubu ne kadar iyi öğrenebildiğini test etmektedir.

## 🚀 Proje Mimarisi ve Karşılaştırmalı Analiz

Proje, üç farklı açık kaynaklı dil modelinin ince ayar (fine-tuning) süreçlerini ve bu modelleri test edebileceğiniz bir arayüzü barındırmaktadır:

1. **`llama_fine_tuning.ipynb`:** LLaMA mimarisi kullanılarak şiir veri seti üzerinde gerçekleştirilen eğitim ve optimizasyon süreçleri.
2. **`qwen_fine_tuning.ipynb`:** Qwen modeli üzerine kurulan eğitim mimarisi ve stil adaptasyonu.
3. **`gpt2_fine_tuning.ipynb`:** Daha temel bir mimari olan GPT-2'nin veri setine uyarlanması ve diğer gelişmiş modellerle (LLaMA, Qwen) kıyaslanabilmesi için hazırlanan eğitim adımları.
4. **`arayuz.ipynb`:** Eğitilen modellerin çıktılarının test edilebildiği, kullanıcı ile etkileşime giren son kullanıcı arayüzü.

## 🛠️ Kullanılan Teknolojiler
- **Geliştirme Ortamı:** Google Colab
- **Makine Öğrenmesi & Derin Öğrenme:** PyTorch, Unsloth (Hızlı ve optimize LLM fine-tuning için)
- **Alan:** Doğal Dil İşleme (NLP), Üretken Yapay Zeka (Generative AI)

## 👨‍💻 Geliştirici
**Burak Dere**  
Kastamonu Üniversitesi - Bilgisayar Mühendisliği (3. Sınıf)
