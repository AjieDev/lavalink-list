<div align="center">
<a href="https://free.lavalink.rf.gd/list">
  <img src="https://cdn-cf.ajieblogs.eu.org/img/1727676032086.png" alt="logo" width="80"/>
</a>
<h3 align="center">
Lavalink List
</h3>
<p align="center">
    Daftar Lavalink publik gratis 
    <br />
    <br />
    <a href="https://free.lavalink.rf.gd/list">Halaman Peramban</a>
    .
    <a href="https://github.com/AjieDev/lavalink-list/pulls">Buat Permintaan Pull</a>
  </p>
</div>

<div align="center"> <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/AjieDev/lavalink-list?style=for-the-badge"> <a href="https://dsc.gg/ajidevserver"><img alt="Discord - AjieDev" src="https://img.shields.io/discord/993867537337024565?label=Discord&logo=discord&style=for-the-badge"></a></div>

[EN](README.md) | [ID](docs/README_id-ID.md)

**Perhatian:** Untuk dukungan, pertanyaan, lihat di [Discord](https://dsc.gg/ajidevserver).



# Menambahkan node baru
1. Fork repositori ini
2. Edit file nodes.json dan tambahkan node kamu sesuai yang ada di contoh
3. Buat permintaan pull

### contoh nodes.json
```json
[
    {
        "unique-id": "nodes-v4",
        "identifier": "My Node v4", 
        "host": "lavalink1.example.com",
        "port": 2333, 
        "password": "youshallnotpass",
        "secure": false,
        "version": "v4"
    }
]

```
- `unique-id` - id unik dari node kamu (contoh: nodes-v4) (Catatan: harus menggunakan huruf kecil dan ganti spasi - )
- `identifier` - identifikasi dari node kamu (contoh: My Node v4)
- `host` - host dari node kamu (bisa berupa subdomain atau domain maupun IP)
- `port` - Port dari node kamu
- `password` - Sandi dari node kamu (sandi bawaan adalah youshallnotpass)
- `secure` - apakah node kamu menggunakan SSL atau tidak (true atau false)
- `version` - Versi dari node kamu (versi lavalink rest api) (v3 atau v4)

# Catatan

- Layanan statistik berkemungkinan untuk untuk mengirim spam ke endpoint statistik dan info kamu (berdasarkan dengan sebarapa banyak orang yang membuka halaman peramban), jika kamu memiliki firewall atau batasan limitasi, kamu bisa menambahkan IP berikut kedalam daftar putih kamu:

```
2a06:98c0:3600::103
```

- Node akan di tandai sebagai ofline jika tidak dapat terhubung selama 3 detik
- Server atau node yang tidak aktif mungkin akan di hapus agar tidak menimbulkan kelambatan status 

# Contributors

<a href="https://github.com/AjieDev/lavalink-list/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=AjieDev/lavalink-list" />
</a>
