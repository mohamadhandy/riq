# React Interview Questions

- [Apa itu React?](#apa-itu-react)
- [Apa fitur yang ditawarkan react?](#apa-fitur-yang-ditawarkan-react)
- [Kenapa react itu ada?](#kenapa-react-itu-ada)
- [Maksud dari component based itu apa?](#maksud-dari-component-based-itu-apa)
- [Apa itu state dan JSX](#apa-itu-state-dan-jsx)
- [Apa bedanya functional component dan class component?](#apa-bedanya-functional-component-dan-class-component)

## Apa itu React?

React merupakan library javascript untuk membuat User Interface

## Fitur React?
1. React itu deklaratif karena react hanya butuh deklarasi tampilan aplikasinya seperti apa, untuk manipulasi DOM itu sudah urusan react. Cara mendeklarasikan tampilan aplikasinya seperti apa yaitu menggunakan state.
2. Component based
3. Learn once write everywhere. 

## Kenapa React itu ada?

Sebelum react muncul, ketika aplikasi semakin kompleks sangat sulit untuk me manage/mengelola flow data karena belum ada framework yang menggunakan component based, ketika menggunakan component based flow data menjadi efisien karena memperbarui dan me-render hanya komponen yang diperlukan ketika datanya berubah.

## Maksud dari component based itu apa?

React itu membuat tampilan di susun berdasarkan component. Bisa di ibaratkan seperti menyusun lego blocks kecil-kecil untuk bisa menghasilkan bentuk yang kompleks. Untuk membuat component itu ada 2 format functional component dan class component kedua format ini ditulis menggunakan state dan jsx. 

## Apa itu state dan JSX?

State adalah wadah untuk menyimpan data yang akan di render atau muat ulang ketika ada perubahan data. Kalau JSX itu sintaks ekstensi javascript jadi facebook nambahin fungsionalitasnya javascript untuk bisa di padukan dengan html, nah ini gunanya untuk membuat component.

## Apa bedanya functional component dan class component?

1. Yang pertama syntax, kalau functional component itu javascript function biasa yang menerima props sebagai argumen kemudian mereturn atau mengembalikan react element. Kalau class component kita butuh keyword extends untuk mendapatkan atribut dari class React.Component dan membuat render method yang mengembalikan react element.
2. Harus dijelasin state dan lifecyclenya
