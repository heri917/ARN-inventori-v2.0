# ARN Inventory • Stok & Part

Build lengkap berbasis spesifikasi ARN Inventory yang telah dikunci. Struktur runtime flat, tanpa subfolder, dan ditujukan untuk GitHub Pages.

## Data master
`master-data.json` berisi hasil ekstraksi master LCD, Battery, Tempered Glass, dan opening stock yang diberikan. Part master otomatis di-seed ke aplikasi. Part/kategori baru dapat ditambah manual.

## Supabase
`supabase-schema.sql` adalah fondasi backend. `supabase-config.js` sengaja tidak berisi key. Isi dengan URL dan publishable/anon key project ARN Store Part Stock sebelum mengaktifkan koneksi Supabase. Jangan pernah memasukkan service_role key ke browser.
