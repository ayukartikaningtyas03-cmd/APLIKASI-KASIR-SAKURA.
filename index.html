<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KASIR HEBAT SALSABILA - Main Kasir TK & PAUD</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600;700&family=Nunito:wght@600;800;900&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            pink: '#FF6B9B',
                            yellow: '#FFC837',
                            blue: '#4E65FF',
                            green: '#00E676',
                            purple: '#9C27B0',
                            orange: '#FF9800'
                        }
                    },
                    fontFamily: {
                        fredoka: ['Fredoka', 'sans-serif'],
                        nunito: ['Nunito', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Fredoka', cursive, sans-serif;
            background-color: #F0F4F8;
            background-image: radial-gradient(#E2E8F0 1.5px, transparent 1.5px);
            background-size: 24px 24px;
            user-select: none;
        }
        .btn-bounce {
            transition: transform 0.1s ease, box-shadow 0.1s ease;
        }
        .btn-bounce:active {
            transform: scale(0.92);
        }
        .pulse-subtle {
            animation: pulse-animation 2s infinite;
        }
        @keyframes pulse-animation {
            0% { transform: scale(1); }
            50% { transform: scale(1.03); }
            100% { transform: scale(1); }
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #F1F5F9;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb {
            background: #CBD5E1;
            border-radius: 10px;
        }
    </style>
</head>
<body class="min-h-screen text-slate-800 flex flex-col justify-between">

    <!-- Header Utama -->
    <header class="bg-gradient-to-r from-pink-500 via-purple-500 to-indigo-600 text-white p-4 shadow-lg sticky top-0 z-30">
        <div class="max-w-6xl mx-auto flex flex-wrap justify-between items-center gap-2">
            <div class="flex items-center gap-3">
                <div class="bg-yellow-400 text-pink-600 p-3 rounded-2xl shadow-inner text-2xl font-black rotate-[-3deg]">
                    🛒
                </div>
                <div>
                    <h1 class="text-2xl sm:text-3xl font-black tracking-wide drop-shadow text-yellow-300">
                        KASIR HEBAT SALSABILA
                    </h1>
                    <p class="text-xs sm:text-sm font-semibold opacity-90 text-pink-100">
                        Belajar Jual Beli TK B & PAUD (Penjumlahan & Pengurangan)
                    </p>
                </div>
            </div>

            <!-- Kontrol Audio, Kelola Barang Guru & Reset -->
            <div class="flex items-center gap-2">
                <button onclick="openTeacherModal()" class="bg-yellow-400 hover:bg-yellow-300 text-purple-900 font-extrabold py-2 px-3 sm:px-4 rounded-xl flex items-center gap-2 shadow btn-bounce text-xs sm:text-sm">
                    <i class="fas fa-edit"></i>
                    <span>Kelola Barang (Guru)</span>
                </button>
                <button id="voiceToggleBtn" onclick="toggleVoice()" class="bg-white/20 hover:bg-white/30 text-white font-bold py-2 px-3 rounded-xl flex items-center gap-1.5 border border-white/30 backdrop-blur-sm btn-bounce text-xs sm:text-sm">
                    <i id="voiceIcon" class="fas font-black fa-volume-up text-yellow-300"></i>
                    <span id="voiceStatus">Suara: ON</span>
                </button>
                <button onclick="resetKasir()" class="bg-red-500 hover:bg-red-600 text-white font-bold py-2 px-3 rounded-xl flex items-center gap-1.5 shadow btn-bounce text-xs sm:text-sm">
                    <i class="fas fa-rotate-right"></i>
                    <span>Ulangi</span>
                </button>
            </div>
        </div>
    </header>

    <!-- Konten Utama -->
    <main class="max-w-6xl mx-auto w-full p-3 sm:p-6 grid grid-cols-1 lg:grid-cols-12 gap-6 items-start flex-grow">

        <!-- Bagian Kiri: Rak Barang Toko (7 Kolom di LG) -->
        <section class="lg:col-span-7 bg-white p-4 sm:p-6 rounded-3xl shadow-xl border-4 border-pink-200">
            <div class="flex items-center justify-between mb-3 pb-2 border-b-2 border-dashed border-pink-200">
                <h2 class="text-xl sm:text-2xl font-extrabold text-pink-600 flex items-center gap-2">
                    <span class="text-2xl">🍰</span> Pilih Barang Belanjaan:
                </h2>
                <span class="text-xs sm:text-sm font-bold bg-pink-100 text-pink-600 px-3 py-1 rounded-full">
                    Sentuh barang untuk beli!
                </span>
            </div>

            <!-- Tab Filter Kategori Barang -->
            <div class="flex flex-wrap gap-1.5 mb-4 pb-2 border-b border-slate-100" id="categoryFilterContainer">
                <button onclick="filterCategory('all')" id="cat-btn-all" class="cat-filter-btn active bg-pink-500 text-white text-xs font-black py-1.5 px-3 rounded-xl transition shadow btn-bounce">
                    🌟 Semua
                </button>
                <button onclick="filterCategory('alattulis')" id="cat-btn-alattulis" class="cat-filter-btn bg-slate-100 text-slate-700 hover:bg-slate-200 text-xs font-bold py-1.5 px-3 rounded-xl transition btn-bounce">
                    ✏️ Alat Tulis
                </button>
                <button onclick="filterCategory('snack')" id="cat-btn-snack" class="cat-filter-btn bg-slate-100 text-slate-700 hover:bg-slate-200 text-xs font-bold py-1.5 px-3 rounded-xl transition btn-bounce">
                    🍿 Jajan & Snack
                </button>
                <button onclick="filterCategory('buah')" id="cat-btn-buah" class="cat-filter-btn bg-slate-100 text-slate-700 hover:bg-slate-200 text-xs font-bold py-1.5 px-3 rounded-xl transition btn-bounce">
                    🍎 Buah
                </button>
                <button onclick="filterCategory('mainan')" id="cat-btn-mainan" class="cat-filter-btn bg-slate-100 text-slate-700 hover:bg-slate-200 text-xs font-bold py-1.5 px-3 rounded-xl transition btn-bounce">
                    🧸 Mainan
                </button>
                <button onclick="filterCategory('sembako')" id="cat-btn-sembako" class="cat-filter-btn bg-slate-100 text-slate-700 hover:bg-slate-200 text-xs font-bold py-1.5 px-3 rounded-xl transition btn-bounce">
                    🥚 Sembako
                </button>
            </div>

            <!-- Grid Daftar Barang -->
            <div id="itemsGrid" class="grid grid-cols-2 sm:grid-cols-3 gap-3 sm:gap-4">
                <!-- Diisi secara dinamis lewat JS -->
            </div>
        </section>

        <!-- Bagian Kanan: Kalkulator Mesin Kasir & Pembayaran (5 Kolom di LG) -->
        <section class="lg:col-span-5 flex flex-col gap-5">
            
            <!-- Layar Mesin Kasir -->
            <div class="bg-slate-900 text-white p-5 rounded-3xl shadow-2xl border-4 border-slate-700 relative overflow-hidden">
                <div class="flex justify-between items-center mb-2">
                    <span class="text-xs font-bold text-emerald-400 uppercase tracking-widest flex items-center gap-1">
                        <span class="w-2 h-2 rounded-full bg-emerald-400 animate-ping"></span> MESIN KASIR HEBAT
                    </span>
                    <span id="itemCountBadge" class="bg-indigo-600 text-xs font-bold px-2.5 py-0.5 rounded-full text-indigo-100">
                        0 Barang
                    </span>
                </div>

                <!-- Visual Layar Hitung Penjumlahan -->
                <div class="bg-slate-800 p-3 rounded-2xl mb-3 border border-slate-700">
                    <div class="text-xs text-slate-400 mb-1 font-semibold">Proses Penjumlahan:</div>
                    <div id="additionFormulaDisplay" class="text-sm sm:text-base font-mono font-bold text-yellow-300 min-h-[1.5rem] break-all leading-tight">
                        0
                    </div>
                </div>

                <!-- Display Total Belanja -->
                <div class="flex justify-between items-end bg-slate-950 p-4 rounded-2xl border border-slate-800 shadow-inner">
                    <span class="text-slate-400 font-bold text-sm">TOTAL HARGA:</span>
                    <span id="totalDisplay" class="text-3xl sm:text-4xl font-black text-emerald-400 tracking-wider">
                        Rp 0
                    </span>
                </div>
            </div>

            <!-- Keranjang Belanjaan (Daftar & Pengurangan) -->
            <div class="bg-white p-4 sm:p-5 rounded-3xl shadow-xl border-4 border-indigo-200">
                <h3 class="text-lg font-bold text-indigo-700 mb-3 flex items-center justify-between border-b pb-2">
                    <span><i class="fas fa-shopping-basket text-indigo-500 mr-2"></i>Keranjang Belanja:</span>
                    <span class="text-xs text-slate-500 font-normal">Kurangi pakai tombol <b class="text-red-500">(-)</b></span>
                </h3>

                <div id="cartList" class="max-h-48 overflow-y-auto space-y-2 pr-1 mb-3">
                    <div id="emptyCartMessage" class="text-center py-6 text-slate-400 font-bold text-sm">
                        Belum ada barang di keranjang.<br>Ayo pilih barang lezat & seru di sebelah!
                    </div>
                </div>

                <!-- Bagian Pembayaran / Pengurangan Uang -->
                <div class="mt-4 pt-3 border-t-2 border-dashed border-indigo-100">
                    <div class="flex justify-between items-center mb-2">
                        <h4 class="text-sm font-extrabold text-slate-700 flex items-center gap-1">
                            💵 Masukkan Uang Pembayaran:
                        </h4>
                        <button onclick="resetPaymentMoney()" class="text-xs bg-red-100 hover:bg-red-200 text-red-600 font-bold px-2 py-0.5 rounded-lg btn-bounce">
                            <i class="fas fa-undo mr-1"></i>Reset Uang
                        </button>
                    </div>

                    <!-- Pilihan Pecahan Uang Mainan (Ditambah Akumulatif) -->
                    <div class="grid grid-cols-3 gap-2 mb-2">
                        <button onclick="addMoney(1000)" class="money-btn bg-emerald-100 hover:bg-emerald-200 border-2 border-emerald-400 text-emerald-800 font-black py-2 rounded-xl text-xs sm:text-sm shadow-sm btn-bounce">
                            + Rp 1.000
                        </button>
                        <button onclick="addMoney(2000)" class="money-btn bg-slate-200 hover:bg-slate-300 border-2 border-slate-400 text-slate-800 font-black py-2 rounded-xl text-xs sm:text-sm shadow-sm btn-bounce">
                            + Rp 2.000
                        </button>
                        <button onclick="addMoney(5000)" class="money-btn bg-yellow-100 hover:bg-yellow-200 border-2 border-yellow-500 text-yellow-900 font-black py-2 rounded-xl text-xs sm:text-sm shadow-sm btn-bounce">
                            + Rp 5.000
                        </button>
                        <button onclick="addMoney(10000)" class="money-btn bg-purple-100 hover:bg-purple-200 border-2 border-purple-400 text-purple-900 font-black py-2 rounded-xl text-xs sm:text-sm shadow-sm btn-bounce">
                            + Rp 10.000
                        </button>
                        <button onclick="addMoney(20000)" class="money-btn bg-teal-100 hover:bg-teal-200 border-2 border-teal-400 text-teal-900 font-black py-2 rounded-xl text-xs sm:text-sm shadow-sm btn-bounce">
                            + Rp 20.000
                        </button>
                        <button onclick="addMoney(50000)" class="money-btn bg-blue-100 hover:bg-blue-200 border-2 border-blue-400 text-blue-900 font-black py-2 rounded-xl text-xs sm:text-sm shadow-sm btn-bounce">
                            + Rp 50.000
                        </button>
                    </div>

                    <!-- Tombol Uang Pas Pilihan Cepat -->
                    <div class="mb-3">
                        <button onclick="setExactMoney()" class="w-full bg-indigo-500 hover:bg-indigo-600 text-white font-black py-2 px-3 rounded-xl text-xs sm:text-sm shadow btn-bounce flex items-center justify-center gap-1.5">
                            🎯 Bayar Uang Pas (Rp <span id="exactMoneyLabel">0</span>)
                        </button>
                    </div>

                    <!-- Ringkasan Bayar & Kembalian -->
                    <div class="bg-indigo-50 p-3.5 rounded-2xl border-2 border-indigo-200 space-y-2 mb-4">
                        <div class="flex justify-between items-center text-sm font-bold text-slate-700">
                            <span>1. Total Belanja:</span>
                            <span id="summaryTotalDisplay" class="text-indigo-700 font-black text-base">Rp 0</span>
                        </div>
                        <div class="flex justify-between items-center text-sm font-bold text-slate-700">
                            <span>2. Uang Diterima Kasir:</span>
                            <span id="paidDisplay" class="text-emerald-600 font-black text-base">Rp 0</span>
                        </div>
                        <div class="flex justify-between items-center text-sm font-bold text-slate-700 pt-1.5 border-t border-indigo-200">
                            <span>3. Uang Kembalian:</span>
                            <span id="changeDisplay" class="text-pink-600 font-black text-lg">Rp 0</span>
                        </div>
                        <!-- Rumus Visual Pengurangan -->
                        <div id="mathExplanation" class="text-xs font-bold text-indigo-900 bg-white p-2 rounded-xl border border-indigo-200 text-center shadow-inner pt-1.5 mt-2 hidden">
                            <!-- Penjelasan Pengurangan -->
                        </div>
                    </div>

                    <!-- Tombol Selesai Bayar -->
                    <button id="payBtn" onclick="processPayment()" disabled class="w-full bg-slate-300 text-slate-500 font-black py-3.5 px-4 rounded-2xl text-base shadow-lg transition-all btn-bounce flex items-center justify-center gap-2">
                        <span>BAYAR SEKARANG</span>
                        <i class="fas fa-check-circle"></i>
                    </button>
                </div>
            </div>
        </section>
    </main>

    <!-- Modal Struk Bukti Belanja & Bintang Hadiah -->
    <div id="receiptModal" class="fixed inset-0 bg-black/60 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white rounded-3xl max-w-md w-full p-6 shadow-2xl border-4 border-yellow-400 text-center relative animate-bounce-short">
            <div class="w-16 h-16 bg-yellow-400 text-white rounded-full flex items-center justify-center text-3xl font-black mx-auto -mt-12 shadow-lg border-4 border-white">
                ⭐
            </div>
            <h3 class="text-2xl font-black text-pink-600 mt-2">HEBAT BANGET! 🎉</h3>
            <p class="text-sm font-bold text-slate-600">Transaksi Belanja Selesai!</p>

            <!-- Tampilan Struk Kasir -->
            <div class="bg-amber-50 border-2 border-dashed border-amber-300 p-4 rounded-2xl my-4 text-left font-mono text-sm shadow-inner space-y-2">
                <div class="text-center font-bold text-slate-800 border-b border-amber-200 pb-1">
                    --- STRUK KASIR HEBAT ---
                </div>
                <div id="receiptItems" class="space-y-1 text-xs text-slate-700 py-1">
                    <!-- Detail Barang Struk -->
                </div>
                <div class="border-t border-amber-200 pt-2 space-y-1 text-xs font-bold">
                    <div class="flex justify-between text-slate-800">
                        <span>Total Belanja:</span>
                        <span id="receiptTotal">Rp 0</span>
                    </div>
                    <div class="flex justify-between text-emerald-700">
                        <span>Uang Bayar:</span>
                        <span id="receiptPaid">Rp 0</span>
                    </div>
                    <div class="flex justify-between text-pink-600 text-sm font-black border-t border-amber-200 pt-1">
                        <span>Sisa Kembalian:</span>
                        <span id="receiptChange">Rp 0</span>
                    </div>
                </div>
            </div>

            <!-- Pesan Pujian Anak -->
            <p id="receiptVoiceText" class="text-xs font-bold text-indigo-600 bg-indigo-50 p-2.5 rounded-xl mb-4">
                "Terima kasih sudah belajar berhitung kasir!"
            </p>

            <button onclick="closeReceipt()" class="w-full bg-gradient-to-r from-pink-500 to-purple-600 hover:from-pink-600 hover:to-purple-700 text-white font-black py-3 px-6 rounded-2xl shadow-lg btn-bounce text-base">
                MAIN LAGI YUK! 🚀
            </button>
        </div>
    </div>

    <!-- Modal Kelola Barang Guru (Tambah & Edit Harga / Icon) -->
    <div id="teacherModal" class="fixed inset-0 bg-black/60 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white rounded-3xl max-w-xl w-full p-5 sm:p-6 shadow-2xl border-4 border-indigo-400 text-left relative max-h-[90vh] flex flex-col">
            <div class="flex justify-between items-center pb-3 border-b border-slate-200">
                <h3 class="text-xl font-black text-indigo-700 flex items-center gap-2">
                    <span>✏️</span> Kelola Barang & Harga (Menu Guru)
                </h3>
                <button onclick="closeTeacherModal()" class="text-slate-400 hover:text-red-500 font-bold text-2xl">
                    &times;
                </button>
            </div>

            <!-- Form Tambah Barang Baru -->
            <div class="my-3 p-3.5 bg-indigo-50 border border-indigo-200 rounded-2xl">
                <h4 class="text-xs font-black text-indigo-900 uppercase tracking-wider mb-2">➕ Tambah Barang Baru:</h4>
                <div class="grid grid-cols-1 sm:grid-cols-12 gap-2 text-xs">
                    <input type="text" id="newItemName" placeholder="Nama Barang" class="sm:col-span-3 p-2 rounded-xl border border-slate-300 font-bold focus:outline-none focus:border-indigo-500">
                    <input type="number" id="newItemPrice" placeholder="Harga" class="sm:col-span-3 p-2 rounded-xl border border-slate-300 font-bold focus:outline-none focus:border-indigo-500" step="1000">
                    <select id="newItemCategory" class="sm:col-span-2 p-2 rounded-xl border border-slate-300 font-bold bg-white focus:outline-none focus:border-indigo-500">
                        <option value="alattulis">✏️ Alat Tulis</option>
                        <option value="snack">🍿 Jajan & Snack</option>
                        <option value="buah">🍎 Buah</option>
                        <option value="mainan">🧸 Mainan</option>
                        <option value="sembako">🥚 Sembako</option>
                    </select>
                    <select id="newItemIcon" class="sm:col-span-2 p-2 rounded-xl border border-slate-300 font-bold bg-white focus:outline-none focus:border-indigo-500">
                        <optgroup label="✏️ Alat Tulis">
                            <option value="✏️">✏️ Pensil Warna</option>
                            <option value="📚">📚 Buku Tulis</option>
                            <option value="📏">📏 Penggaris</option>
                            <option value="🧹">🧹 Penghapus</option>
                            <option value="🎒">🎒 Tas Sekolah</option>
                            <option value="🖍️">🖍️ Crayon</option>
                            <option value="✂️">✂️ Gunting</option>
                            <option value="👝">👝 Kotak Pensil</option>
                        </optgroup>
                        <optgroup label="🍿 Jajan & Snack">
                            <option value="🍩">🍩 Donat</option>
                            <option value="🍫">🍫 Cokelat</option>
                            <option value="🍦">🍦 Es Krim</option>
                            <option value="🍬">🍬 Permen</option>
                            <option value="🍪">🍪 Biskuit</option>
                            <option value="🧃">🧃 Susu Kotak</option>
                            <option value="🍮">🍮 Puding</option>
                            <option value="🍟">🍟 Kentang Goreng</option>
                            <option value="🍿">🍿 Popcorn</option>
                            <option value="🥤">🥤 Minuman</option>
                        </optgroup>
                        <optgroup label="🍎 Buah-Buahan">
                            <option value="🍎">🍎 Apel</option>
                            <option value="🍌">🍌 Pisang</option>
                            <option value="🍊">🍊 Jeruk</option>
                            <option value="🍉">🍉 Semangka</option>
                            <option value="🍇">🍇 Anggur</option>
                            <option value="🍓">🍓 Stroberi</option>
                            <option value="🍍">🍍 Nanas</option>
                        </optgroup>
                        <optgroup label="🧸 Mainan">
                            <option value="🏎️">🏎️ Mobil Balap</option>
                            <option value="🧸">🧸 Boneka Beruang</option>
                            <option value="🪀">🪀 Yoyo</option>
                            <option value="⚽">⚽ Bola Plastik</option>
                            <option value="🧩">🧩 Balok Mainan</option>
                            <option value="🤖">🤖 Robot</option>
                            <option value="🎈">🎈 Balon</option>
                        </optgroup>
                        <optgroup label="🥚 Sembako">
                            <option value="🥚">🥚 Telur Ayam</option>
                            <option value="🍞">🍞 Roti Tawar</option>
                            <option value="🌾">🌾 Beras</option>
                            <option value="🍾">🍾 Minyak Goreng</option>
                            <option value="🧂">🧂 Gula Pasir</option>
                            <option value="🫖">🫖 Teh Celup</option>
                            <option value="🍜">🍜 Mie Instan</option>
                            <option value="🧀">🧀 Keju</option>
                            <option value="🥛">🥛 Susu Botol</option>
                        </optgroup>
                    </select>
                    <button onclick="addNewItem()" class="sm:col-span-2 bg-emerald-500 hover:bg-emerald-600 text-white font-black py-2 px-3 rounded-xl shadow btn-bounce text-xs">
                        Tambah
                    </button>
                </div>
            </div>

            <!-- Daftar Barang Saat Ini -->
            <div class="flex-grow overflow-y-auto my-2 pr-1 space-y-2 max-h-60" id="teacherItemsList">
                <!-- Diisi via JS -->
            </div>

            <div class="pt-3 border-t border-slate-200 flex justify-between items-center gap-2">
                <button onclick="resetDefaultItems()" class="bg-slate-200 hover:bg-slate-300 text-slate-700 font-bold py-2 px-3 rounded-xl text-xs btn-bounce">
                    <i class="fas fa-undo mr-1"></i> Reset ke Bawaan
                </button>
                <button onclick="closeTeacherModal()" class="bg-indigo-600 hover:bg-indigo-700 text-white font-extrabold py-2 px-5 rounded-xl text-xs sm:text-sm btn-bounce">
                    Selesai & Simpan
                </button>
            </div>
        </div>
    </div>

    <!-- Footer Keterangan -->
    <footer class="bg-slate-200 text-slate-600 text-center py-3 px-4 text-xs font-bold border-t border-slate-300">
        Kasir Hebat Salsabila &copy; Media Pembelajaran PAUD & TK B
    </footer>

    <script>
        // Master Data Default Items
        const DEFAULT_ITEMS = [
            // Alat Tulis Sekolah
            { id: 'pensil', name: 'Pensil Warna', price: 1000, icon: '✏️', category: 'alattulis', color: 'bg-yellow-100 border-yellow-300 text-yellow-800' },
            { id: 'buku', name: 'Buku Tulis', price: 3000, icon: '📚', category: 'alattulis', color: 'bg-blue-100 border-blue-300 text-blue-700' },
            { id: 'penggaris', name: 'Penggaris', price: 2000, icon: '📏', category: 'alattulis', color: 'bg-teal-100 border-teal-300 text-teal-800' },
            { id: 'penghapus', name: 'Penghapus', price: 1000, icon: '🧹', category: 'alattulis', color: 'bg-pink-100 border-pink-300 text-pink-700' },
            { id: 'crayon', name: 'Crayon Lukis', price: 5000, icon: '🖍️', category: 'alattulis', color: 'bg-orange-100 border-orange-300 text-orange-800' },
            { id: 'tas', name: 'Tas Sekolah', price: 10000, icon: '🎒', category: 'alattulis', color: 'bg-indigo-100 border-indigo-300 text-indigo-800' },
            
            // Jajan & Snack
            { id: 'donat', name: 'Donat Cokelat', price: 2000, icon: '🍩', category: 'snack', color: 'bg-amber-100 border-amber-300 text-amber-800' },
            { id: 'cokelat', name: 'Cokelat Manis', price: 3000, icon: '🍫', category: 'snack', color: 'bg-red-100 border-red-300 text-red-800' },
            { id: 'eskrim', name: 'Es Krim Lezat', price: 4000, icon: '🍦', category: 'snack', color: 'bg-rose-100 border-rose-300 text-rose-800' },
            { id: 'permen', name: 'Permen Buah', price: 1000, icon: '🍬', category: 'snack', color: 'bg-purple-100 border-purple-300 text-purple-800' },
            { id: 'biskuit', name: 'Biskuit Susu', price: 2000, icon: '🍪', category: 'snack', color: 'bg-yellow-100 border-yellow-300 text-yellow-800' },
            { id: 'susu', name: 'Susu Kotak', price: 3000, icon: '🧃', category: 'snack', color: 'bg-sky-100 border-sky-300 text-sky-800' },

            // Buah-Buahan
            { id: 'apel', name: 'Apel Merah', price: 2000, icon: '🍎', category: 'buah', color: 'bg-red-100 border-red-300 text-red-700' },
            { id: 'pisang', name: 'Pisang Manis', price: 1000, icon: '🍌', category: 'buah', color: 'bg-yellow-100 border-yellow-300 text-yellow-800' },
            { id: 'jeruk', name: 'Jeruk Segar', price: 2000, icon: '🍊', category: 'buah', color: 'bg-orange-100 border-orange-300 text-orange-800' },
            { id: 'semangka', name: 'Semangka', price: 5000, icon: '🍉', category: 'buah', color: 'bg-emerald-100 border-emerald-300 text-emerald-800' },

            // Mainan Anak
            { id: 'mobil', name: 'Mobil Balap', price: 5000, icon: '🏎️', category: 'mainan', color: 'bg-red-100 border-red-300 text-red-800' },
            { id: 'boneka', name: 'Boneka Beruang', price: 10000, icon: '🧸', category: 'mainan', color: 'bg-amber-100 border-amber-300 text-amber-800' },
            { id: 'yoyo', name: 'Yoyo Putar', price: 3000, icon: '🪀', category: 'mainan', color: 'bg-green-100 border-green-300 text-green-800' },
            { id: 'bola', name: 'Bola Plastik', price: 2000, icon: '⚽', category: 'mainan', color: 'bg-slate-100 border-slate-300 text-slate-800' },

            // Sembako
            { id: 'telur', name: 'Telur Ayam', price: 2000, icon: '🥚', category: 'sembako', color: 'bg-amber-100 border-amber-300 text-amber-800' },
            { id: 'roti', name: 'Roti Tawar', price: 4000, icon: '🍞', category: 'sembako', color: 'bg-yellow-100 border-yellow-300 text-yellow-800' },
            { id: 'beras', name: 'Beras Super', price: 10000, icon: '🌾', category: 'sembako', color: 'bg-emerald-100 border-emerald-300 text-emerald-800' },
            { id: 'minyak', name: 'Minyak Goreng', price: 5000, icon: '🍾', category: 'sembako', color: 'bg-yellow-100 border-yellow-300 text-yellow-800' },
            { id: 'gula', name: 'Gula Pasir', price: 3000, icon: '🧂', category: 'sembako', color: 'bg-sky-100 border-sky-300 text-sky-800' },
            { id: 'teh', name: 'Teh Celup', price: 2000, icon: '🫖', category: 'sembako', color: 'bg-emerald-100 border-emerald-300 text-emerald-800' }
        ];

        // Global State Variables
        let AVAILABLE_ITEMS = JSON.parse(JSON.stringify(DEFAULT_ITEMS));
        let cart = [];
        let totalAmount = 0;
        let paidAmount = 0;
        let changeAmount = 0;
        let currentCategory = 'all';
        let voiceEnabled = true;

        // Web Audio API untuk Efek Suara Bip Kasir
        let audioCtx = null;
        function playBeepSound(freq = 800, type = 'sine', duration = 0.1) {
            try {
                if (!audioCtx) {
                    audioCtx = new (window.AudioContext || window.webkitAudioContext)();
                }
                if (audioCtx.state === 'suspended') {
                    audioCtx.resume();
                }
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                osc.type = type;
                osc.frequency.setValueAtTime(freq, audioCtx.currentTime);
                gain.gain.setValueAtTime(0.15, audioCtx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.0001, audioCtx.currentTime + duration);
                osc.connect(gain);
                gain.connect(audioCtx.destination);
                osc.start();
                osc.stop(audioCtx.currentTime + duration);
            } catch (e) {
                console.log("Audio not supported or blocked", e);
            }
        }

        // Suara Kemenangan / Transaksi Berhasil
        function playSuccessSound() {
            setTimeout(() => playBeepSound(523.25, 'triangle', 0.12), 0);
            setTimeout(() => playBeepSound(659.25, 'triangle', 0.12), 120);
            setTimeout(() => playBeepSound(783.99, 'triangle', 0.25), 240);
        }

        // Tts Narator Bahasa Indonesia
        function speakText(text) {
            if (!voiceEnabled) return;
            if ('speechSynthesis' in window) {
                window.speechSynthesis.cancel();
                const utterance = new SpeechSynthesisUtterance(text);
                utterance.lang = 'id-ID';
                utterance.rate = 0.95;
                utterance.pitch = 1.1;
                window.speechSynthesis.speak(utterance);
            }
        }

        // Filter Kategori Barang
        function filterCategory(category) {
            currentCategory = category;
            
            // Highlight Button Active
            document.querySelectorAll('.cat-filter-btn').forEach(btn => {
                btn.className = "cat-filter-btn bg-slate-100 text-slate-700 hover:bg-slate-200 text-xs font-bold py-1.5 px-3 rounded-xl transition btn-bounce";
            });

            const activeBtn = document.getElementById(`cat-btn-${category}`);
            if (activeBtn) {
                activeBtn.className = "cat-filter-btn active bg-pink-500 text-white text-xs font-black py-1.5 px-3 rounded-xl transition shadow btn-bounce";
            }

            playBeepSound(600, 'sine', 0.08);
            renderItemsGrid();
        }

        // Render Grid Rak Barang
        function renderItemsGrid() {
            const grid = document.getElementById('itemsGrid');
            grid.innerHTML = '';

            const filteredItems = currentCategory === 'all' 
                ? AVAILABLE_ITEMS 
                : AVAILABLE_ITEMS.filter(item => item.category === currentCategory);

            if (filteredItems.length === 0) {
                grid.innerHTML = `
                    <div class="col-span-full text-center py-8 text-slate-400 font-bold text-sm">
                        Belum ada barang di kategori ini.
                    </div>
                `;
                return;
            }

            filteredItems.forEach(item => {
                const card = document.createElement('div');
                card.className = `${item.color || 'bg-slate-50 border-slate-200 text-slate-800'} border-3 border-b-4 rounded-2xl p-3 flex flex-col items-center justify-between shadow-md hover:shadow-lg cursor-pointer btn-bounce transition-all relative group overflow-hidden`;
                card.onclick = () => addToCart(item.id);

                card.innerHTML = `
                    <div class="text-4xl sm:text-5xl my-1 transform group-hover:scale-110 transition-transform duration-200">
                        ${item.icon}
                    </div>
                    <div class="text-center w-full mt-1">
                        <div class="font-black text-xs sm:text-sm truncate w-full" title="${item.name}">${item.name}</div>
                        <div class="inline-block bg-white/80 backdrop-blur-sm px-2 py-0.5 rounded-lg text-xs font-black text-slate-800 mt-1 shadow-sm border border-slate-200">
                            Rp ${item.price.toLocaleString('id-ID')}
                        </div>
                    </div>
                    <div class="mt-2 bg-pink-500 hover:bg-pink-600 text-white font-extrabold text-[10px] sm:text-xs py-1 px-3 rounded-xl w-full text-center shadow">
                        + BELI
                    </div>
                `;
                grid.appendChild(card);
            });
        }

        // Tambah Barang ke Keranjang Belanja (Dengan Suara Penjumlahan)
        function addToCart(itemId) {
            const item = AVAILABLE_ITEMS.find(i => i.id === itemId);
            if (!item) return;

            playBeepSound(900, 'sine', 0.08);

            const prevTotal = totalAmount;

            const existingIndex = cart.findIndex(c => c.id === itemId);
            if (existingIndex > -1) {
                cart[existingIndex].qty += 1;
            } else {
                cart.push({ ...item, qty: 1 });
            }

            calculateCartTotal();
            renderCartList();

            // Narasi Suara Penjumlahan Harga
            if (prevTotal === 0) {
                speakText(`Beli ${item.name}, harga ${formatRupiahText(item.price)}.`);
            } else {
                const textPrev = formatRupiahText(prevTotal, false);
                const textItemPrice = formatRupiahText(item.price, false);
                const textNewTotal = formatRupiahText(totalAmount, true);
                speakText(`Beli ${item.name}. ${textPrev} ditambah ${textItemPrice}, sama dengan ${textNewTotal}.`);
            }
        }

        // Kurangi/Hapus Barang dari Keranjang Belanja (Dengan Suara Pengurangan)
        function removeFromCart(itemId) {
            const index = cart.findIndex(c => c.id === itemId);
            if (index === -1) return;

            playBeepSound(400, 'sine', 0.1);
            const item = cart[index];
            const prevTotal = totalAmount;
            const itemPrice = item.price;
            const itemName = item.name;

            if (cart[index].qty > 1) {
                cart[index].qty -= 1;
            } else {
                cart.splice(index, 1);
            }

            calculateCartTotal();
            renderCartList();

            // Narasi Suara Pengurangan Harga
            if (totalAmount === 0) {
                speakText(`Kurangi ${itemName}. Keranjang belanja sekarang kosong.`);
            } else {
                const textPrev = formatRupiahText(prevTotal, false);
                const textPrice = formatRupiahText(itemPrice, false);
                const textNewTotal = formatRupiahText(totalAmount, true);
                speakText(`Kurangi ${itemName}. ${textPrev} dikurangi ${textPrice}, sisa ${textNewTotal}.`);
            }
        }

        // Hitung Total Penjumlahan Keranjang Belanja
        function calculateCartTotal() {
            totalAmount = cart.reduce((sum, item) => sum + (item.price * item.qty), 0);
            updatePaymentDisplay();
        }

        // Render Tampilan Keranjang & Rumus Penjumlahan Kasir
        function renderCartList() {
            const cartListEl = document.getElementById('cartList');
            const formulaDisplayEl = document.getElementById('additionFormulaDisplay');
            const totalDisplayEl = document.getElementById('totalDisplay');
            const itemCountBadgeEl = document.getElementById('itemCountBadge');

            const totalItemCount = cart.reduce((sum, item) => sum + item.qty, 0);
            itemCountBadgeEl.innerText = `${totalItemCount} Barang`;

            if (cart.length === 0) {
                cartListEl.innerHTML = `
                    <div id="emptyCartMessage" class="text-center py-6 text-slate-400 font-bold text-sm">
                        Belum ada barang di keranjang.<br>Ayo pilih barang lezat & seru di sebelah!
                    </div>
                `;
                formulaDisplayEl.innerText = '0';
                totalDisplayEl.innerText = 'Rp 0';
                return;
            }

            cartListEl.innerHTML = '';
            let formulaParts = [];

            cart.forEach(item => {
                const subtotal = item.price * item.qty;
                for (let i = 0; i < item.qty; i++) {
                    formulaParts.push(`${item.price.toLocaleString('id-ID')}`);
                }

                const row = document.createElement('div');
                row.className = 'flex items-center justify-between bg-indigo-50/70 p-2 rounded-2xl border border-indigo-100 text-xs sm:text-sm font-bold';
                row.innerHTML = `
                    <div class="flex items-center gap-2 flex-grow truncate">
                        <span class="text-xl">${item.icon}</span>
                        <div class="truncate">
                            <div class="font-extrabold text-slate-800 truncate">${item.name}</div>
                            <div class="text-[10px] text-indigo-600">Rp ${item.price.toLocaleString('id-ID')} x ${item.qty}</div>
                        </div>
                    </div>
                    <div class="flex items-center gap-2 flex-shrink-0">
                        <span class="font-black text-indigo-900">Rp ${subtotal.toLocaleString('id-ID')}</span>
                        <button onclick="removeFromCart('${item.id}')" class="bg-red-500 hover:bg-red-600 text-white font-black w-7 h-7 rounded-xl flex items-center justify-center shadow btn-bounce text-sm">
                            -
                        </button>
                    </div>
                `;
                cartListEl.appendChild(row);
            });

            formulaDisplayEl.innerText = formulaParts.join(' + ') + ` = ${totalAmount.toLocaleString('id-ID')}`;
            totalDisplayEl.innerText = `Rp ${totalAmount.toLocaleString('id-ID')}`;
        }

        // Menambah Uang Pembayaran secara Akumulatif
        function addMoney(amount) {
            playBeepSound(600, 'sine', 0.1);

            if (totalAmount === 0) {
                speakText("Pilih barang belanjaan dulu ya sebelum bayar!");
                return;
            }

            paidAmount += amount;
            updatePaymentDisplay();

            if (paidAmount < totalAmount) {
                const kurang = totalAmount - paidAmount;
                speakText(`Uang diterima ${formatRupiahText(paidAmount)}. Masih kurang ${formatRupiahText(kurang)} lagi.`);
            } else {
                changeAmount = paidAmount - totalAmount;
                if (changeAmount === 0) {
                    speakText(`Uang diterima ${formatRupiahText(paidAmount)}. Pas, tidak ada kembalian!`);
                } else {
                    speakText(`Uang diterima ${formatRupiahText(paidAmount)}. Kembaliannya ${formatRupiahText(changeAmount)}.`);
                }
            }
        }

        // Fungsi Membayar dengan Uang Pas
        function setExactMoney() {
            if (totalAmount === 0) {
                speakText("Pilih barang belanjaan dulu ya!");
                return;
            }
            playBeepSound(700, 'sine', 0.1);
            paidAmount = totalAmount;
            updatePaymentDisplay();
            speakText(`Bayar dengan uang pas ${formatRupiahText(paidAmount)}.`);
        }

        // Reset Uang Pembayaran Kembali ke 0
        function resetPaymentMoney() {
            playBeepSound(300, 'triangle', 0.1);
            paidAmount = 0;
            updatePaymentDisplay();
            speakText("Uang pembayaran diulang dari nol.");
        }

        // Update UI & Kalkulasi Pengurangan Uang Kembalian
        function updatePaymentDisplay() {
            document.getElementById('summaryTotalDisplay').innerText = `Rp ${totalAmount.toLocaleString('id-ID')}`;
            document.getElementById('paidDisplay').innerText = `Rp ${paidAmount.toLocaleString('id-ID')}`;
            document.getElementById('exactMoneyLabel').innerText = totalAmount.toLocaleString('id-ID');

            const payBtn = document.getElementById('payBtn');
            const mathExp = document.getElementById('mathExplanation');

            if (totalAmount > 0 && paidAmount >= totalAmount) {
                changeAmount = paidAmount - totalAmount;
                document.getElementById('changeDisplay').innerText = `Rp ${changeAmount.toLocaleString('id-ID')}`;
                
                // Aktifkan Tombol Bayar
                payBtn.disabled = false;
                payBtn.className = "w-full bg-gradient-to-r from-emerald-500 to-green-600 hover:from-emerald-600 hover:to-green-700 text-white font-black py-3.5 px-4 rounded-2xl text-base shadow-xl btn-bounce flex items-center justify-center gap-2 pulse-subtle cursor-pointer";

                // Tampilkan konsep pengurangan matematika anak
                mathExp.classList.remove('hidden');
                mathExp.innerHTML = `🧮 <b>Rumus Pengurangan:</b><br>Rp ${paidAmount.toLocaleString('id-ID')} (Uang) - Rp ${totalAmount.toLocaleString('id-ID')} (Total) = <b class="text-pink-600">Rp ${changeAmount.toLocaleString('id-ID')} (Kembalian)</b>`;
            } else {
                changeAmount = 0;
                document.getElementById('changeDisplay').innerText = `Rp 0`;
                payBtn.disabled = true;
                payBtn.className = "w-full bg-slate-300 text-slate-500 font-black py-3.5 px-4 rounded-2xl text-base shadow-lg cursor-not-allowed flex items-center justify-center gap-2";
                
                if (paidAmount > 0 && paidAmount < totalAmount) {
                    const sisaKurang = totalAmount - paidAmount;
                    mathExp.classList.remove('hidden');
                    mathExp.innerHTML = `⚠️ <b>Uang Masih Kurang:</b><br>Kurang <b class="text-red-600">Rp ${sisaKurang.toLocaleString('id-ID')}</b> lagi`;
                } else {
                    mathExp.classList.add('hidden');
                }
            }
        }

        // Proses Pembayaran dan Cetak Struk Bukti
        function processPayment() {
            if (paidAmount < totalAmount || totalAmount === 0) return;

            playSuccessSound();

            // Isi Detail Struk
            const receiptItemsEl = document.getElementById('receiptItems');
            receiptItemsEl.innerHTML = '';

            cart.forEach(item => {
                const line = document.createElement('div');
                line.className = 'flex justify-between';
                line.innerHTML = `
                    <span>${item.icon} ${item.name} x${item.qty}</span>
                    <span>Rp ${(item.qty * item.price).toLocaleString('id-ID')}</span>
                `;
                receiptItemsEl.appendChild(line);
            });

            document.getElementById('receiptTotal').innerText = `Rp ${totalAmount.toLocaleString('id-ID')}`;
            document.getElementById('receiptPaid').innerText = `Rp ${paidAmount.toLocaleString('id-ID')}`;
            document.getElementById('receiptChange').innerText = `Rp ${changeAmount.toLocaleString('id-ID')}`;

            let finalSpeechText = "";
            if (changeAmount === 0) {
                finalSpeechText = `Hore! Transaksi selesai. Total belanja ${formatRupiahText(totalAmount)}. Uang pas! Terima kasih sudah belajar!`;
            } else {
                finalSpeechText = `Hore! Transaksi selesai. Total belanja ${formatRupiahText(totalAmount)}, dibayar ${formatRupiahText(paidAmount)}, kembaliannya ${formatRupiahText(changeAmount)}. Kamu pintar sekali!`;
            }
            
            document.getElementById('receiptVoiceText').innerText = `"${finalSpeechText}"`;

            // Tampilkan Modal Struk
            document.getElementById('receiptModal').classList.remove('hidden');
            speakText(finalSpeechText);
        }

        // Tutup Modal Struk
        function closeReceipt() {
            document.getElementById('receiptModal').classList.add('hidden');
            resetKasir();
        }

        // Reset Aplikasi
        function resetKasir() {
            cart = [];
            totalAmount = 0;
            paidAmount = 0;
            changeAmount = 0;
            calculateCartTotal();
            renderCartList();
            playBeepSound(500, 'sine', 0.1);
            speakText("Kasir siap melayani belanja baru!");
        }

        function openTeacherModal() {
            renderTeacherItemsList();
            document.getElementById('teacherModal').classList.remove('hidden');
        }

        function closeTeacherModal() {
            document.getElementById('teacherModal').classList.add('hidden');
            renderItemsGrid();
            calculateCartTotal();
            renderCartList();
        }

        function renderTeacherItemsList() {
            const listEl = document.getElementById('teacherItemsList');
            listEl.innerHTML = '';

            AVAILABLE_ITEMS.forEach((item) => {
                const itemRow = document.createElement('div');
                itemRow.className = 'flex items-center justify-between bg-slate-50 p-2.5 rounded-2xl border border-slate-200 gap-2';
                itemRow.innerHTML = `
                    <div class="flex items-center gap-2 flex-grow">
                        <span class="text-2xl">${item.icon}</span>
                        <span class="font-extrabold text-xs sm:text-sm text-slate-800">${item.name}</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <span class="text-xs font-bold text-slate-500">Rp</span>
                        <input type="number" value="${item.price}" step="1000" onchange="updateItemPrice('${item.id}', this.value)" class="w-20 p-1 rounded-lg border border-slate-300 font-extrabold text-xs text-center focus:outline-none focus:border-indigo-500">
                        <button onclick="deleteTeacherItem('${item.id}')" class="bg-red-100 hover:bg-red-200 text-red-600 font-black p-2 rounded-xl text-xs btn-bounce" title="Hapus Barang">
                            <i class="fas fa-trash"></i>
                        </button>
                    </div>
                `;
                listEl.appendChild(itemRow);
            });
        }

        function updateItemPrice(id, newPrice) {
            const price = parseInt(newPrice);
            if (isNaN(price) || price < 0) return;
            const item = AVAILABLE_ITEMS.find(i => i.id === id);
            if (item) {
                item.price = price;
            }
        }

        function deleteTeacherItem(id) {
            if (AVAILABLE_ITEMS.length <= 1) {
                speakText("Minimal harus ada 1 barang di toko!");
                return;
            }
            AVAILABLE_ITEMS = AVAILABLE_ITEMS.filter(i => i.id !== id);
            cart = cart.filter(i => i.id !== id);
            renderTeacherItemsList();
        }

        function addNewItem() {
            const nameInput = document.getElementById('newItemName');
            const priceInput = document.getElementById('newItemPrice');
            const categorySelect = document.getElementById('newItemCategory');
            const iconSelect = document.getElementById('newItemIcon');

            const name = nameInput.value.trim();
            const price = parseInt(priceInput.value);
            const category = categorySelect.value;
            const icon = iconSelect.value;

            if (!name) {
                speakText("Masukkan nama barang terlebih dahulu!");
                return;
            }
            if (isNaN(price) || price <= 0) {
                speakText("Masukkan harga barang yang valid!");
                return;
            }

            const id = 'custom_' + Date.now();
            const colors = [
                'bg-pink-100 border-pink-300 text-pink-700',
                'bg-blue-100 border-blue-300 text-blue-700',
                'bg-yellow-100 border-yellow-300 text-yellow-800',
                'bg-emerald-100 border-emerald-300 text-emerald-800',
                'bg-purple-100 border-purple-300 text-purple-700',
                'bg-amber-100 border-amber-300 text-amber-800',
                'bg-rose-100 border-rose-300 text-rose-700'
            ];
            const color = colors[Math.floor(Math.random() * colors.length)];

            AVAILABLE_ITEMS.push({ id, name, price, icon, category, color });

            nameInput.value = '';
            priceInput.value = '';

            renderTeacherItemsList();
            speakText(`Barang ${name} berhasil ditambahkan!`);
        }

        function resetDefaultItems() {
            AVAILABLE_ITEMS = JSON.parse(JSON.stringify(DEFAULT_ITEMS));
            renderTeacherItemsList();
            speakText("Daftar barang dikembalikan ke semula.");
        }

        // Toggle Suara On/Off
        function toggleVoice() {
            voiceEnabled = !voiceEnabled;
            const statusEl = document.getElementById('voiceStatus');
            const iconEl = document.getElementById('voiceIcon');

            if (voiceEnabled) {
                statusEl.innerText = "Suara: ON";
                iconEl.className = "fas fa-volume-up text-yellow-300";
                speakText("Suara diaktifkan");
            } else {
                statusEl.innerText = "Suara: OFF";
                iconEl.className = "fas fa-volume-mute text-slate-300";
                if ('speechSynthesis' in window) window.speechSynthesis.cancel();
            }
        }

        // Helper Membaca Angka Rupiah ke Teks Narasi Bahasa Indonesia Natural
        function formatRupiahText(angka, includeRupiah = true) {
            const rupiahSuffix = includeRupiah ? " rupiah" : "";
            if (angka === 0) return "nol" + rupiahSuffix;
            if (angka === 1000) return "seribu" + rupiahSuffix;
            if (angka === 2000) return "dua ribu" + rupiahSuffix;
            if (angka === 3000) return "tiga ribu" + rupiahSuffix;
            if (angka === 4000) return "empat ribu" + rupiahSuffix;
            if (angka === 5000) return "lima ribu" + rupiahSuffix;
            if (angka === 6000) return "enam ribu" + rupiahSuffix;
            if (angka === 7000) return "tujuh ribu" + rupiahSuffix;
            if (angka === 8000) return "delapan ribu" + rupiahSuffix;
            if (angka === 9000) return "sembilan ribu" + rupiahSuffix;
            if (angka === 10000) return "sepuluh ribu" + rupiahSuffix;
            if (angka === 11000) return "sebelas ribu" + rupiahSuffix;
            if (angka === 12000) return "dua belas ribu" + rupiahSuffix;
            if (angka === 13000) return "tiga belas ribu" + rupiahSuffix;
            if (angka === 14000) return "empat belas ribu" + rupiahSuffix;
            if (angka === 15000) return "lima belas ribu" + rupiahSuffix;
            if (angka === 20000) return "dua puluh ribu" + rupiahSuffix;
            if (angka === 25000) return "dua puluh lima ribu" + rupiahSuffix;
            if (angka === 30000) return "tiga puluh ribu" + rupiahSuffix;
            if (angka === 50000) return "lima puluh ribu" + rupiahSuffix;
            if (angka === 100000) return "seratus ribu" + rupiahSuffix;

            return `${angka.toLocaleString('id-ID')}` + rupiahSuffix;
        }

        // Inisialisasi Saat Halaman Dimuat
        window.onload = function() {
            renderItemsGrid();
            renderCartList();
            
            // Salam Pembuka Kasir Hebat Salsabila
            setTimeout(() => {
                speakText("Selamat datang di Kasir Hebat Salsabila! Pilih alat tulis dan makanan untuk mulai belajar.");
            }, 500);
        };
    </script>
</body>
</html>
