# Sybil attack: kenapa project benci multi-akun

## Inti
Sybil attack = satu orang bikin ratusan/ribuan wallet palsu biar kelihatan seperti
banyak user asli, lalu serok porsi airdrop lebih besar. Project benci ini karena
token jatuh ke farmer, bukan user beneran — harga dump, metrik palsu.

## Cara project mendeteksi
- **Analisis sumber dana**: 100 wallet didanai dari 1 address dalam waktu singkat = cluster
- **Clustering perilaku**: puluhan wallet eksekusi urutan transaksi identik dalam window sempit
- **Umur & histori wallet**: wallet berumur 1 hari dengan 1 transaksi = merah
- Kasus nyata: Optimism diskualifikasi 17.000 address; satu entitas pakai 14.000 wallet di airdrop aPriori

## Kenapa farmer jujur ikut kena
False positive itu nyata. Danai 5 wallet dari 1 akun exchange di hari yang sama,
di mata algoritma kamu tidak beda dari mini-farm. Project terima false positive
demi menekan dilusi — banding hampir tidak ada.

## Pelajaran
Main bersih, satu identitas satu aktivitas yang konsisten. Konsolidasi reward ke
satu address sesaat setelah claim = pola paling gampang kena flag.

Sumber:
- https://dev.to/basisdesk/what-are-airdrops-and-points-programs-eligibility-sybils-and-taxes-34kh
- https://cointelegraph.com/news/token-airdrops-targeted-farm-accounts-sybil-attacks
- https://coinmarketcap.com/community/articles/68c0585561452246d6bbb368/
