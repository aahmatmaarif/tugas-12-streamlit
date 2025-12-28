import streamlit as st
import pandas as pd

st.title("Tugas Pertemuan 12")

st.header("Penerapan Dasar Streamlit")

st.subheader("Nama User: aahmatmaarif")

st.caption("Data yang ditampilkan merupakan data simulasi untuk keperluan pembelajaran.")

st.write("""
Aplikasi web ini dibuat menggunakan Streamlit sebagai media pembelajaran
untuk memahami cara menampilkan berbagai komponen antarmuka sederhana.
Melalui aplikasi ini, pengguna dapat melihat contoh penggunaan teks,
tabel data, potongan kode, serta grafik interaktif.
""")

st.code("""
data = {
    'Kategori': ['Alpha', 'Beta', 'Gamma', 'Delta'],
    'Nilai': [72, 88, 81, 95]
}

df = pd.DataFrame(data)
""", language="python")

data = {
    'Kategori': ['Alpha', 'Beta', 'Gamma', 'Delta'],
    'Nilai': [72, 88, 81, 95]
}

df = pd.DataFrame(data)

st.subheader("Tabel Data Penilaian")
st.dataframe(df)

st.subheader("Grafik Nilai Kategori")
st.bar_chart(df.set_index("Kategori"))
