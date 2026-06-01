<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pengumuman Kelulusan - SDN 1 Seruni Mumbul</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;700;800&family=Nunito:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary-color: #002b5b; /* Biru Tua Sekolah */
            --secondary-color: #b8860b; /* Emas */
            --bg-color: #f8fafc;
            --text-main: #334155;
            --white: #ffffff;
            --success: #10b981;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Nunito', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, var(--primary-color) 0%, #0a4282 100%);
            color: var(--white);
            padding: 50px 20px;
            text-align: center;
            border-bottom: 6px solid var(--secondary-color);
        }

        header h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        /* Main Container */
        .container {
            max-width: 900px;
            margin: -30px auto 40px;
            padding: 0 20px;
            flex-grow: 1;
            width: 100%;
        }

        /* Cards */
        .card {
            background: var(--white);
            border-radius: 12px;
            padding: 40px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.08);
            margin-bottom: 30px;
        }

        /* Login Section */
        #login-section {
            text-align: center;
            max-width: 600px;
            margin: 0 auto;
        }

        .icon-lg {
            font-size: 60px;
            color: var(--secondary-color);
            margin-bottom: 20px;
        }

        .input-group {
            margin-top: 30px;
        }

        input[type="text"] {
            width: 100%;
            padding: 16px 20px;
            font-size: 1.2rem;
            border: 2px solid #cbd5e1;
            border-radius: 8px;
            text-align: center;
            margin-bottom: 20px;
            font-family: 'Nunito', sans-serif;
            transition: all 0.3s ease;
        }

        input[type="text"]:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 4px rgba(0, 43, 91, 0.1);
        }

        .btn {
            background-color: var(--primary-color);
            color: var(--white);
            border: none;
            padding: 15px 40px;
            font-size: 1.1rem;
            font-weight: 700;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 1px;
            font-family: 'Montserrat', sans-serif;
            width: 100%;
        }

        .btn:hover {
            background-color: #0a4282;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 43, 91, 0.3);
        }

        #error-msg {
            color: #ef4444;
            font-weight: 600;
            margin-top: 15px;
            display: none;
            background: #fee2e2;
            padding: 10px;
            border-radius: 6px;
        }

        /* Result Section */
        #result-section {
            display: none;
            animation: slideUp 0.6s ease forwards;
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .student-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #f0f4f8;
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 30px;
            border-left: 6px solid var(--primary-color);
        }

        .student-name {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.6rem;
            color: var(--primary-color);
            margin-bottom: 5px;
        }

        .badge {
            background: var(--success);
            color: white;
            padding: 10px 25px;
            border-radius: 50px;
            font-weight: 800;
            font-size: 1.2rem;
            letter-spacing: 2px;
        }

        /* TKA Section */
        .section-title {
            font-family: 'Montserrat', sans-serif;
            color: var(--primary-color);
            font-size: 1.4rem;
            margin-bottom: 20px;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .tka-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-bottom: 40px;
        }

        .tka-box {
            border: 1px solid #e2e8f0;
            border-radius: 10px;
            padding: 25px;
            text-align: center;
            background: #ffffff;
        }

        .tka-box p.subject {
            color: #64748b;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 10px;
        }

        .tka-box .score {
            font-size: 2.8rem;
            font-weight: 800;
            color: var(--primary-color);
            font-family: 'Montserrat', sans-serif;
            line-height: 1;
        }

        .tka-box .predikat {
            color: var(--secondary-color);
            font-weight: 700;
            font-size: 1.1rem;
            margin-top: 5px;
        }

        /* Table */
        .table-responsive {
            overflow-x: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background: white;
            border-radius: 8px;
            overflow: hidden;
            border: 1px solid #e2e8f0;
        }

        th {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 16px;
            text-align: left;
            font-family: 'Montserrat', sans-serif;
            font-size: 1rem;
        }

        td {
            padding: 14px 16px;
            border-bottom: 1px solid #e2e8f0;
            color: var(--text-main);
            font-size: 1.05rem;
        }

        tr:nth-child(even) { background-color: #f8fafc; }
        
        .val-cell {
            text-align: center;
            font-weight: 600;
        }

        .row-total td {
            background-color: #002b5b;
            color: white;
            font-weight: 800;
            font-size: 1.15rem;
        }
        
        .row-total .val-cell {
            background-color: var(--secondary-color);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 30px;
            background: #001a38;
            color: #94a3b8;
            margin-top: auto;
        }

        @media (max-width: 768px) {
            .tka-grid { grid-template-columns: 1fr; }
            .student-header { flex-direction: column; text-align: center; gap: 15px; }
            header h1 { font-size: 1.8rem; }
        }
    </style>
</head>
<body>

    <header>
        <h1>SD NEGERI 1 SERUNI MUMBUL</h1>
        <p>Portal Pengumuman Kelulusan Kelas 6 Tahun Pelajaran 2025/2026</p>
    </header>

    <div class="container">
        <div class="card" id="login-section">
            <i class="fa-solid fa-user-graduate icon-lg"></i>
            <h2 style="font-family: 'Montserrat', sans-serif; color: var(--primary-color); margin-bottom: 10px;">Cek Hasil Kelulusan</h2>
            <p style="color: #64748b;">Silakan masukkan Nomor Induk Siswa Nasional (NISN) Anda untuk melihat rekapitulasi nilai dan status kelulusan.</p>
            
            <div class="input-group">
                <input type="text" id="nisn-input" placeholder="Masukkan NISN (Contoh: 0133758653)" maxlength="10">
                <button class="btn" onclick="cekData()"><i class="fa-solid fa-magnifying-glass"></i> Tampilkan Hasil</button>
            </div>
            <div id="error-msg"><i class="fa-solid fa-circle-exclamation"></i> NISN tidak ditemukan atau tidak valid. Silakan coba lagi.</div>
        </div>

        <div class="card" id="result-section">
            <div class="student-header">
                <div>
                    <p style="color: #64748b; font-size: 0.9rem; font-weight: 700; text-transform: uppercase;">Nama Lengkap Siswa</p>
                    <h3 class="student-name" id="res-nama">-</h3>
                    <p style="font-size: 1.1rem;"><strong>NISN:</strong> <span id="res-nisn">-</span></p>
                </div>
                <div class="badge" id="res-status">LULUS</div>
            </div>

            <h3 class="section-title"><i class="fa-solid fa-chart-bar" style="color: var(--secondary-color);"></i> Nilai Tes Kemampuan Akademik (TKA)</h3>
            <div class="tka-grid">
                <div class="tka-box">
                    <p class="subject">Bahasa Indonesia</p>
                    <div class="score" id="res-tka-indo">-</div>
                    <div class="predikat" id="res-pred-indo">-</div>
                </div>
                <div class="tka-box">
                    <p class="subject">Matematika</p>
                    <div class="score" id="res-tka-mtk">-</div>
                    <div class="predikat" id="res-pred-mtk">-</div>
                </div>
            </div>

            <h3 class="section-title"><i class="fa-solid fa-file-certificate" style="color: var(--secondary-color);"></i> Rincian Nilai Ijazah</h3>
            <div class="table-responsive">
                <table>
                    <thead>
                        <tr>
                            <th style="width: 10%;">No</th>
                            <th>Mata Pelajaran</th>
                            <th style="text-align: center; width: 25%;">Nilai</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td>1</td><td>Pendidikan Agama Islam dan Budi Pekerti (PAIBP)</td><td class="val-cell" id="val-1">-</td></tr>
                        <tr><td>2</td><td>Pendidikan Pancasila (PKn)</td><td class="val-cell" id="val-2">-</td></tr>
                        <tr><td>3</td><td>Bahasa Indonesia</td><td class="val-cell" id="val-3">-</td></tr>
                        <tr><td>4</td><td>Matematika</td><td class="val-cell" id="val-4">-</td></tr>
                        <tr><td>5</td><td>Ilmu Pengetahuan Alam dan Sosial (IPAS)</td><td class="val-cell" id="val-5">-</td></tr>
                        <tr><td>6</td><td>Seni Budaya</td><td class="val-cell" id="val-6">-</td></tr>
                        <tr><td>7</td><td>Pendidikan Jasmani, Olahraga, dan Kesehatan (PJOK)</td><td class="val-cell" id="val-7">-</td></tr>
                        <tr><td>8</td><td>Bahasa Inggris</td><td class="val-cell" id="val-8">-</td></tr>
                        <tr><td>9</td><td>Muatan Lokal (MULOK)</td><td class="val-cell" id="val-9">-</td></tr>
                        <tr class="row-total">
                            <td colspan="2" style="text-align: right;">RATA-RATA NILAI IJAZAH</td>
                            <td class="val-cell" id="val-avg">-</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            
            <button class="btn" style="margin-top: 40px; background-color: #64748b;" onclick="location.reload()">
                <i class="fa-solid fa-arrow-left"></i> Kembali / Cek NISN Lain
            </button>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 SD Negeri 1 Seruni Mumbul. Hak Cipta Dilindungi.</p>
    </footer>

    <script>
        // Database Array (Format: [NISN, NAMA, TKA_MTK, TKA_INDO, PAIBP, PKN, BINDO, MTK, IPAS, SB, PJOK, BING, MULOK, RATA])
        // Memasukkan seluruh 55 data siswa ke dalam memori
        const dbSiswa = [
            ["3136352448", "AKILA", "40.00 (Memadai)", "50.00 (Memadai)", "89,30", "86,53", "89,67", "84,45", "85,95", "84,08", "85,48", "84,55", "85,70", "86,19"],
            ["3134167925", "ANDI AQILA", "40.00 (Memadai)", "53.33 (Memadai)", "87,90", "84,43", "85,48", "80,72", "84,55", "83,27", "85,60", "83,50", "85,35", "84,53"],
            ["3134625925", "ANGGI NABILAH", "23.33 (Kurang)", "86.67 (Baik)", "83,95", "86,73", "82,57", "79,20", "82,90", "81,28", "81,75", "82,67", "84,88", "82,88"],
            ["3138645618", "AQIFA HALWA NAILA", "43.33 (Memadai)", "36.67 (Kurang)", "80,82", "79,32", "79,55", "78,73", "80,37", "80,95", "83,62", "79,08", "82,80", "80,58"],
            ["0135131449", "AQILA ZAHRANI", "36.67 (Memadai)", "46.67 (Kurang)", "83,50", "83,15", "83,73", "80,72", "84,07", "83,38", "83,27", "81,28", "85,82", "83,21"],
            ["0135947614", "BAIQ APRILIYANTI", "43.33 (Memadai)", "60.00 (Memadai)", "84,08", "84,55", "86,28", "82,00", "85,82", "84,08", "86,87", "82,80", "84,77", "84,58"],
            ["0142319180", "BAIQ ARIQA FATINA ARUMI", "36.67 (Memadai)", "53.33 (Memadai)", "88,83", "85,48", "90,00", "83,63", "86,98", "85,37", "85,58", "83,73", "85,00", "86,07"],
            ["3131794827", "BAIQ ZASKIA AULIA RAHMA", "46.67 (Memadai)", "66.67 (Memadai)", "85,93", "84,20", "85,70", "82,35", "86,28", "83,73", "85,47", "83,03", "85,35", "84,67"],
            ["3146258509", "BQ. YUMNA ALIFYA", "46.67 (Memadai)", "50.00 (Memadai)", "88,83", "86,65", "88,27", "83,52", "87,45", "84,32", "86,05", "84,88", "85,58", "86,17"],
            ["0133758653", "DANU ILMAN HIDAYAT", "56.67 (Baik)", "66.67 (Memadai)", "89,08", "89,10", "91,65", "92,57", "91,17", "85,48", "88,97", "86,42", "86,98", "89,05"],
            ["3146775517", "FANI AZHA MAURA", "43.33 (Memadai)", "63.33 (Memadai)", "85,70", "83,97", "86,05", "82,00", "85,23", "83,73", "86,75", "82,45", "84,77", "84,52"],
            ["3137539262", "GALUH ARTANU", "36.67 (Memadai)", "46.67 (Kurang)", "81,98", "82,80", "84,08", "80,83", "82,22", "80,72", "86,87", "79,78", "83,38", "82,52"],
            ["0127484641", "HAPASA MAHRENI", "40.00 (Memadai)", "70.00 (Memadai)", "87,67", "84,32", "85,48", "82,93", "85,93", "84,20", "87,10", "83,15", "85,35", "85,13"],
            ["0121359022", "INDANA FATINA", "43.33 (Memadai)", "53.33 (Memadai)", "80,93", "81,07", "83,03", "80,13", "82,10", "82,00", "85,47", "77,92", "84,42", "81,90"],
            ["3137454082", "JAIBAL SAZID INGGI", "43.33 (Memadai)", "40.00 (Kurang)", "80,93", "79,78", "80,60", "79,20", "80,02", "81,30", "86,17", "78,85", "83,03", "81,10"],
            ["3139395466", "LUSIANA SAPITRI", "26.67 (Kurang)", "46.67 (Kurang)", "80,82", "80,95", "80,95", "79,67", "79,78", "80,83", "84,30", "79,20", "82,92", "81,05"],
            ["3141938510", "M. KHAERUL AMAR", "36.67 (Memadai)", "26.67 (Kurang)", "80,93", "80,13", "80,72", "79,20", "79,78", "80,37", "85,58", "79,43", "82,68", "80,98"],
            ["3143369270", "M. ZHIKRULLAH", "40.00 (Memadai)", "40.00 (Kurang)", "80,23", "79,32", "79,55", "78,97", "79,55", "80,95", "86,17", "79,32", "82,68", "80,75"],
            ["3143642778", "MOH. ALPAROZI", "46.67 (Memadai)", "60.00 (Memadai)", "85,58", "83,97", "85,60", "82,23", "83,62", "83,03", "87,57", "83,03", "85,47", "84,46"],
            ["3134167130", "MUHAMAD RENALDI", "43.33 (Memadai)", "83.33 (Baik)", "90,00", "91,52", "93,15", "91,98", "90,58", "86,75", "88,15", "87,33", "86,05", "89,50"],
            ["3147655046", "MUNAWARAH", "16.67 (Kurang)", "46.67 (Kurang)", "84,53", "84,43", "84,20", "80,95", "84,77", "83,38", "86,63", "82,57", "85,35", "84,09"],
            ["3142290467", "NIAS KURNIASIH", "43.33 (Memadai)", "50.00 (Memadai)", "85,70", "83,73", "84,32", "81,07", "85,23", "83,50", "84,53", "80,47", "85,00", "83,73"],
            ["3138509476", "NOVAL KHAERUL IHWAN", "36.67 (Memadai)", "46.67 (Kurang)", "82,10", "80,37", "80,95", "79,20", "80,13", "80,13", "86,75", "79,55", "82,68", "81,32"],
            ["0136915320", "NUR SAKINAH", "36.67 (Memadai)", "53.33 (Memadai)", "84,77", "85,02", "85,25", "82,70", "85,47", "84,08", "86,87", "82,80", "85,35", "84,70"],
            ["3142063767", "NURUL AFSAH ANDINI", "33.33 (Memadai)", "30.00 (Kurang)", "84,18", "81,18", "83,27", "80,25", "81,75", "82,00", "86,05", "79,55", "84,53", "82,53"],
            ["3130669930", "RISKI BAYU MAULANA", "50.00 (Memadai)", "70.00 (Memadai)", "82,57", "81,53", "82,70", "80,13", "81,98", "80,95", "86,63", "78,50", "82,92", "81,99"],
            ["0131767691", "ZAKI ISWANDI", "26.67 (Kurang)", "60.00 (Memadai)", "87,57", "87,93", "88,52", "86,90", "86,88", "85,02", "87,57", "83,97", "85,58", "86,66"],
            ["0135291738", "ABIYYU AMMAR ISMAIL", "56.67 (Baik)", "46.67 (Kurang)", "84,20", "87,57", "84,28", "84,40", "87,22", "87,80", "89,18", "84,75", "88,05", "86,38"],
            ["0131834409", "AHZA DANIS", "30.00 (Kurang)", "46.67 (Kurang)", "82,33", "81,85", "79,32", "79,67", "81,05", "84,65", "83,03", "80,02", "86,28", "82,02"],
            ["0139667266", "ALIF AQILAL KUSMAYADI", "43.33 (Memadai)", "46.67 (Kurang)", "86,97", "87,93", "85,82", "86,75", "88,97", "89,57", "91,05", "87,10", "91,05", "88,36"],
            ["3136154633", "AQILA AZZAHRA", "26.67 (Kurang)", "66.67 (Memadai)", "85,45", "86,53", "84,20", "84,55", "85,82", "87,58", "87,67", "84,32", "87,78", "85,99"],
            ["3143320202", "AZRA MAULIDA", "40.00 (Memadai)", "53.33 (Memadai)", "84,78", "86,77", "84,30", "84,42", "86,98", "88,17", "85,85", "85,70", "90,03", "86,33"],
            ["0149791085", "BAIQ AISYAH PUTRI", "13.33 (Kurang)", "30.00 (Kurang)", "80,47", "82,32", "80,25", "79,67", "81,28", "84,65", "86,13", "80,25", "85,83", "82,32"],
            ["0146724571", "BAIQ APRILIYANI", "43.33 (Memadai)", "40.00 (Kurang)", "84,67", "86,87", "86,42", "87,12", "89,88", "88,50", "89,30", "87,58", "89,88", "87,80"],
            ["3141668880", "DHAIFI AZKAL HIMAMI", "33.33 (Memadai)", "43.33 (Kurang)", "87,20", "87,10", "85,47", "85,70", "87,80", "88,73", "91,53", "85,93", "87,47", "87,44"],
            ["3137925058", "DIKA PRAYUDHA", "30.00 (Kurang)", "80.00 (Baik)", "88,35", "84,88", "82,67", "83,37", "85,48", "86,52", "87,20", "85,12", "86,30", "85,54"],
            ["3143354763", "HABIB AKBAR ALFA REZA", "36.67 (Memadai)", "43.33 (Kurang)", "83,00", "85,00", "81,83", "82,77", "85,35", "85,93", "85,93", "82,77", "87,58", "84,46"],
            ["3143176899", "HAERUNISA", "36.67 (Memadai)", "36.67 (Kurang)", "84,90", "86,65", "83,82", "83,58", "88,37", "87,58", "86,40", "83,23", "88,28", "85,87"],
            ["3130448933", "HULWA KANZA RAMADANI BEG", "53.33 (Memadai)", "33.33 (Kurang)", "78,60", "80,47", "76,40", "75,58", "79,52", "80,82", "83,35", "76,17", "82,65", "79,28"],
            ["3130244018", "JIHAN RAUDATUL RAHMAN", "46.67 (Memadai)", "50.00 (Memadai)", "93,02", "90,23", "87,58", "88,52", "91,77", "90,93", "91,05", "87,12", "90,35", "90,06"],
            ["0148608842", "M. FARIS ZEIDAN", "63.33 (Baik)", "56.67 (Memadai)", "91,62", "90,35", "89,55", "91,07", "93,37", "91,05", "93,37", "89,67", "89,42", "91,05"],
            ["0139150753", "M.ABIZHAR FARABI", "40.00 (Memadai)", "53.33 (Memadai)", "91,27", "88,98", "87,58", "88,17", "91,05", "89,57", "93,13", "86,77", "90,82", "89,70"],
            ["0137845092", "MARSHA AYLA PUTRI", "50.00 (Memadai)", "40.00 (Kurang)", "84,17", "84,30", "83,02", "83,37", "86,77", "86,87", "86,30", "84,18", "88,37", "85,26"],
            ["3146108221", "MIRFAT ABIZAR", "50.00 (Memadai)", "56.67 (Memadai)", "83,03", "84,88", "82,18", "82,07", "87,32", "85,82", "86,42", "83,47", "88,83", "84,89"],
            ["3136629246", "MOH. JAKARIA BIN HASAN", "36.67 (Memadai)", "76.67 (Baik)", "83,95", "85,93", "83,02", "83,25", "85,83", "85,70", "86,42", "83,83", "86,87", "84,98"],
            ["3131850571", "NABIL FAIRUS", "30.00 (Kurang)", "50.00 (Memadai)", "82,33", "84,18", "82,30", "81,37", "84,07", "84,77", "85,70", "80,67", "87,67", "83,67"],
            ["0135942555", "NAJWA FIDDINA", "43.33 (Memadai)", "70.00 (Memadai)", "83,27", "84,43", "83,73", "83,27", "82,47", "86,53", "84,17", "84,43", "87,43", "84,41"],
            ["3141673269", "NISA ARDILA", "30.00 (Kurang)", "40.00 (Kurang)", "79,27", "82,32", "79,55", "79,43", "80,82", "83,72", "80,70", "79,90", "86,88", "81,40"],
            ["0134829783", "NURAN AZANI ADHA", "43.33 (Memadai)", "70.00 (Memadai)", "85,20", "86,63", "84,88", "85,23", "89,65", "87,68", "89,23", "84,77", "89,30", "86,95"],
            ["3133993009", "PUTRI KANZA OKTAFANI", "36.67 (Memadai)", "50.00 (Memadai)", "84,78", "86,75", "84,42", "84,88", "89,07", "87,22", "90,42", "85,35", "89,07", "86,88"],
            ["3138324884", "RAEFAL ANGGARAKSA", "40.00 (Memadai)", "33.33 (Kurang)", "81,43", "82,92", "79,32", "79,90", "80,93", "83,50", "84,07", "79,78", "85,35", "81,91"],
            ["0137090150", "RIDSAL PUTRA FIMAN PRATAMA", "56.67 (Baik)", "73.33 (Memadai)", "93,25", "91,75", "91,78", "92,13", "95,30", "91,98", "93,37", "93,30", "91,28", "92,68"],
            ["3135585722", "SUCI DARMA WANDA", "40.00 (Memadai)", "70.00 (Memadai)", "86,85", "88,52", "85,93", "87,22", "92,95", "90,03", "90,70", "87,10", "89,77", "88,79"],
            ["0159444169", "TAMA ARDIATMA", "66.67 (Baik)", "56.67 (Memadai)", "86,38", "88,98", "89,08", "89,90", "93,25", "89,33", "90,72", "87,68", "90,23", "89,51"],
            ["0136312004", "ZIO TANZILAL", "53.33 (Memadai)", "76.67 (Baik)", "91,62", "90,12", "88,85", "89,32", "93,08", "90,93", "93,02", "89,67", "90,12", "90,75"]
        ];

        // Eksekusi ketika tombol Enter ditekan pada input NISN
        document.getElementById("nisn-input").addEventListener("keypress", function(event) {
            if (event.key === "Enter") {
                event.preventDefault();
                cekData();
            }
        });

        function cekData() {
            const inputVal = document.getElementById('nisn-input').value.trim();
            const errorMsg = document.getElementById('error-msg');
            
            if (inputVal === "") {
                errorMsg.innerHTML = '<i class="fa-solid fa-circle-exclamation"></i> Harap masukkan NISN terlebih dahulu.';
                errorMsg.style.display = "block";
                return;
            }

            // Mencari siswa di dalam array (berdasarkan index ke-0 / NISN)
            const student = dbSiswa.find(s => s[0] === inputVal);

            if (student) {
                // Sembunyikan Error
                errorMsg.style.display = "none";

                // Mapping Data TKA B.Indo (Index 3)
                const indoSplit = student[3].split(' (');
                document.getElementById('res-tka-indo').innerText = indoSplit[0];
                document.getElementById('res-pred-indo').innerText = '(' + indoSplit[1];

                // Mapping Data TKA MTK (Index 2)
                const mtkSplit = student[2].split(' (');
                document.getElementById('res-tka-mtk').innerText = mtkSplit[0];
                document.getElementById('res-pred-mtk').innerText = '(' + mtkSplit[1];

                // Mapping Identitas
                document.getElementById('res-nama').innerText = student[1];
                document.getElementById('res-nisn').innerText = student[0];

                // Mapping Nilai Ijazah
                // Index Array -> 4: PAIBP, 5: PKN, 6: BINDO, 7: MTK, 8: IPAS, 9: SB, 10: PJOK, 11: BING, 12: MULOK, 13: Rata-Rata
                for (let i = 0; i < 9; i++) {
                    document.getElementById(`val-${i+1}`).innerText = student[4+i];
                }
                document.getElementById('val-avg').innerText = student[13];

                // Transisi Tampilan
                document.getElementById('login-section').style.display = 'none';
                document.getElementById('result-section').style.display = 'block';
            } else {
                // Munculkan pesan error jika NISN tidak ada di database
                errorMsg.innerHTML = '<i class="fa-solid fa-circle-exclamation"></i> NISN tidak ditemukan. Pastikan NISN yang dimasukkan sudah benar.';
                errorMsg.style.display = "block";
            }
        }
    </script>
</body>
</html>
