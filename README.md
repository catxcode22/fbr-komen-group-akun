# FB Marketplace Report Bot

Bot ini adalah solusi untuk me-report postingan berbau seks yang bikin risih di Facebook marketplace secara otomatis.

## Requirement

* NodeJS

## Instalasi

Clone repository ini:

```bash
git clone https://github.com/codex22/fbr-komen-group-akun.git
```

Lakukan cd ke root folder repo yang telah di clone, jalankan:

```bash
npm install
```

## Usage

Jalankan script init, dan jangan di close, biarkan jalan di shell:

```bash
node init
```

Jendela chromium akan terbuka, login ke akun FBmu, lalu arahkan ke halaman marketplace. Copy address websocket dari output run script diatas yang diawali dengan `ws://`.

Setelah itu buka window / tab shell baru, cd ke folder repo ini lagi, jalankan script run:

```bash
node run {websocketAddress}
```

Untuk menghentikan tinggal di close saja 2 shell yang menjalankan script tadi.
