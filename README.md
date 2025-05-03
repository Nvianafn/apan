# Demo BLIP (Bootstrapping Language Image Pre-training)
Demo ini dibuat untuk memenuhi tugas metodelogi penelitian informatika

Repo ini berisi kode untuk melakukan **Visual Question Answering (VQA)** menggunakan model **BLIP** dari Salesforce. Tujuan dari kode ini adalah untuk menjawab beberapa pertanyaan terkait dengan satu gambar menggunakan model pretrained BLIP.

**Hal yang harus disiapkan**
- `google colab` untuk code editor
- `transformers` untuk model dan processor dari Hugging Face
- `torch` untuk PyTorch
- `Pillow` untuk manipulasi gambar
- `json` untuk menangani data pertanyaan dalam format JSON

**Cara install**
  
  Untuk menginstal kebutuhan, jalankan perintah berikut di cmd:
pip install transformers torch Pillow

**Struktur folder**

pastikan struktur foldermu :

content/custom_dataset/berkebun.jpg & questions.json
