<div align="center">
  <h1>AICLUB Tools</h1>
  <p><strong>Data katalog &amp; tempat usul tool AI open source — dirangkum bahasa Indonesia.</strong></p>

  <p>
    <a href="https://aiclub.ai.id/tools/"><img src="https://img.shields.io/badge/Live-aiclub.ai.id%2Ftools-FFD23F?style=for-the-badge&labelColor=111111" alt="Katalog live"></a>
    <a href="https://github.com/AIClub-ai-id/tools/issues"><img src="https://img.shields.io/badge/Usul%20Tool-Buka%20Issue-7AB8FF?style=for-the-badge&labelColor=111111" alt="Usul tool baru"></a>
  </p>
</div>

Repo ini adalah sumber data untuk katalog [aiclub.ai.id/tools](https://aiclub.ai.id/tools/) — kumpulan tools AI open source pilihan, dirangkum dalam bahasa Indonesia untuk pengguna Indonesia: developer, UMKM, dan kreator.

## Isi Repo

| File | Fungsi |
|---|---|
| `tools.json` | Data utama katalog: nama, repo, kategori, deskripsi ID, link. Katalog membaca file ini. |
| `README.md` | Dokumentasi & panduan kontribusi (file ini). |

## Usul Tool Baru

Buka [Issue baru](https://github.com/AIClub-ai-id/tools/issues) dengan judul: `USUL: Nama Tool`

Format isi:

1. **Nama + link repo GitHub** tool-nya
2. **Kenapa layak**: manfaat nyata untuk pengguna Indonesia (1-3 kalimat)
3. **Kategori**: `developer` / `umkm` / `kreator`
4. **Bahasa**: dokumentasi Indonesia / Inggris / keduanya

### Syarat diterima

- Open source (kode bisa dilihat publik)
- Aktif dirawat (ada aktivitas commit beberapa bulan terakhir)
- Relevan: AI / automation / produktivitas
- Bukan klon tanpa nilai tambah

Tool yang lulus kurasi ditambahkan ke katalog dengan kredit ke pengusulnya.

## Struktur `tools.json`

```json
{
  "name": "Nama Tool",
  "repo": "owner/repository",
  "category": "developer | umkm | kreator",
  "description_id": "Deskripsi singkat bahasa Indonesia",
  "url": "https://situs-resmi-jika-ada"
}
```

Statistik (stars, forks, update terakhir) diambil live dari GitHub API oleh katalog — tidak perlu diisi manual.

## Komunitas

- Channel: [t.me/aiclub_id](https://t.me/aiclub_id)
- Grup diskusi: [t.me/aiclubidchat](https://t.me/aiclubidchat)
- Situs: [aiclub.ai.id](https://aiclub.ai.id/)

---

<div align="center">
  <sub>Gratis, tanpa iklan — didukung komunitas.</sub>
</div>
