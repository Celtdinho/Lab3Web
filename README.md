# Lab3Web
```
Nama : Naufal Rafi Haryanto
Nim : 312410118
Kelas : TI.24.A1
```
---

## 1. Membuat List
Pada file **lab3_list.html** dibuat 3 jenis list:
- Ordered List
- Unordered List
- Description List

### Kode List
```html
<ol type="A" start="D">
  <li>Pemrograman Web</li>
  <li>Sistem Informasi</li>
  <li>Basis Data 2</li>
</ol>

<ul type="square">
  <li>Jaringan Komputer</li>
  <li>Struktur Data</li>
  <li>Algoritma & Pemrograman</li>
</ul>

<dl>
  <dt>Fakultas Teknik</dt>
  <dd>Teknik Industri</dd>
  <dd>Teknik Informatika</dd>
  <dd>Teknik Lingkungan</dd>
</dl>
```
### Hasil Kode

![Gambar](List.png)

---

## 2. Membuat Tabel

Pada file lab3_tabel.html dibuat tabel sederhana dan tabel dengan rowspan & colspan.

### Kode Tabel
```html
<table>
  <thead>
    <tr>
      <th>No.</th>
      <th>Fakultas</th>
      <th>Program Studi</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td rowspan="3">Teknik</td>
      <td>Teknik Informatika</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>Teknik Industri</td>
    </tr>
    <tr>
      <td>3.</td>
      <td>Teknik Lingkungan</td>
    </tr>
  </tbody>
</table>
```
![Gambar](Tabel.png)

---

## 3. Membuat Form

Pada file lab3_form.html dibuat form dengan:

Input text

Textarea

Radio button

Dropdown menu

Listbox multiple selection

Tombol submit

### Kode Form
```html
<p>
  <label for="jurusan">Jurusan</label>
  <select id="jurusan" name="jurusan">
    <option value="ti">Teknik Informatika</option>
    <option value="si">Sistem Informasi</option>
    <option value="mi">Manajemen Informatika</option>
    <option value="tk">Teknik Komputer</option>
  </select>
</p>

<p>
  <label for="hobi">Hobi</label>
  <select id="hobi" name="hobi[]" multiple>
    <option value="membaca">Membaca</option>
    <option value="musik">Musik</option>
    <option value="olahraga">Olahraga</option>
    <option value="traveling">Traveling</option>
    <option value="gaming">Gaming</option>
  </select>
</p>
```
![Gambar](List.png)

---


