<div align="center">

  <img src="https://your-logo-url-here.png" alt="Aetherud Logo" width="180" />

  <h1>Aetherud</h1>

  <p>
    <strong>Hafif modüller, eter gibi bağlı bir bütün.</strong><br/>
    NATS tabanlı, schema-driven, Docker & Kubernetes destekli modüler entegrasyon SDK'sı.
  </p>

  <p>
    <a href="https://aetherud.com">
      <img src="https://img.shields.io/badge/website-aetherud.com-blue?style=for-the-badge&logo=vercel" alt="Website" />
    </a>
    <a href="https://github.com/aetherud/aetherud/stargazers">
      <img src="https://img.shields.io/github/stars/aetherud/aetherud?style=for-the-badge&color=yellow" alt="GitHub Stars" />
    </a>
    <a href="https://www.npmjs.com/package/aetherud">
      <img src="https://img.shields.io/npm/v/aetherud?style=for-the-badge&color=brightgreen" alt="npm" />
    </a>
    <a href="https://github.com/aetherud/aetherud/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/aetherud/aetherud?style=for-the-badge&color=purple" alt="License" />
    </a>
  </p>

</div>

<br />

## Aetherud Nedir?

Aetherud, **ayrık ama uyumlu modüller** oluşturmanızı sağlayan hafif ve güçlü bir SDK'dır.

- Modüllerini **TypeBox** ile şema tanımlayarak yaz  
- **http.get/post** ile diğer modüllere doğal çağrı yap  
- NATS ile mesajlaşma ve event-driven mimari hazır  
- Docker Compose veya Kubernetes ile **tek komut** ayağa kaldır  
- Otomatik validation, logging ve orchestrator desteği  

Kısaca: **Uğraşmadan modül yaz, uğraşmadan çalıştır.**

## Özellikler

- 🧩 **Decoupled ama Unified** – Modüller bağımsız, ama NATS ile tek bir sistem gibi davranır
- 📝 **Schema-driven** – TypeBox ile input/output otomatik validate
- 🚀 **Docker & Kubernetes hazır** – Tek komutla deploy (Compose veya K8s)
- ⚡ **NATS-powered** – JetStream destekli, yüksek performanslı mesajlaşma
- 🛠️ **CLI ile kolay başlangıç** – `npx aetherud init` ile 10 saniyede proje
- 🌐 **Self-hosted & Open-source** – Tamamen kontrol sende, ücret yok

## Başlangıç (Quick Start – 60 saniye)

```bash
# 1. Projeni oluştur
npx aetherud init my-awesome-project

# 2. Klasöre gir
cd my-awesome-project

# 3. Docker ile ayağa kaldır
aetherud up

# 4. Veya Kubernetes modunda
aetherud up --k8s
