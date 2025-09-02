LINK SPREADSHEETS = https://docs.google.com/spreadsheets/d/1WWg5R7jwTv3uaQ-2mzfnGxgmF--SwsK3JggGcfxUrGE/edit?gid=400415953#gid=400415953
LINK SHEETDB API = https://sheetdb.io/api/v1/7absym1gp66uj
Cara penggunaan Link API
{ 1. Copy link dari spreadsheet yang akan menjadi data
  2. Buka Link SheetDB API
  3. Klik tombol [+ Create New API]
  4. Pilih yang [Existing spreadsheet]
  5. Masukan Link Spreadsheet yang akan menjadi database
  6. Klik tobol [Create API]
  7. API berhasil dibuat, lalu copy link yang tertera pada API tersebut. Contoh linknya yang seperti ini [https://sheetdb.io/api/v1/7absym1gp66uj]
  8. Masukan Link tersebut pada source code bagian 
    [
      <script>
        const apiUrl = "https://sheetdb.io/api/v1/7absym1gp66uj";
        const tbody = document.querySelector("#data-table tbody");
        ]

}
SheetDB memiliki limit pemakaian, sehingga LINK API harus di update selalu. 
