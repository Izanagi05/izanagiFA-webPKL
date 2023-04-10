<template>

  <div>

    <div :class="isActive ? 'menu menuactivembl pt-0' : 'menu pt-0'">
      <div class="text-end pr-6 pt-6 ">
        <v-icon  @click="isActive=!isActive" size="30" color="white" >mdi-close</v-icon>
      </div>
      <ul  style="margin-top: 80px;">
      <li class="nav-itemmb "><a class="nxlink white--text text-decoration-none" href="#home"  @click="isActive=!isActive">Home</a></li>
        <li class="nav-itemmb "><a class="nxlink white--text text-decoration-none" @click="isActive=!isActive" href="#pendahuluan">Pendahuluan</a></li>
        <li class="nav-itemmb "><a class="nxlink white--text text-decoration-none" @click="isActive=!isActive" href="#sejarah">Sejarah</a></li>
        <li class="nav-itemmb "><a class="nxlink white--text text-decoration-none" @click="isActive=!isActive" href="#kegiatan">Kegiatan</a></li>
        <li class="nav-itemmb "><a class="nxlink white--text text-decoration-none" @click="isActive=!isActive" href="#kesimpulan">Kesimpulan</a></li>
        <li class="nav-itemmb "><a class="nxlink white--text text-decoration-none" @click="isActive=!isActive" href="#lampiran">Lampiran</a></li>

    </ul>
  </div>
    <nav class="navbar py-3" style="position: fixed; z-index:998; width: 100vw;">
      <div class="d-flex ">
        <div class="bardeks">
          <ul class="nav-link pr-10 ">
            <li class="nav-item "><a class="nxlink  text-decoration-none" href="#home">Home</a></li>
        <li class="nav-item "><a class="nxlink  text-decoration-none" href="#pendahuluan">Pendahuluan</a></li>
        <li class="nav-item "><a class="nxlink  text-decoration-none" href="#sejarah">Sejarah</a></li>
        <li class="nav-item "><a class="nxlink  text-decoration-none" href="#kegiatan">Kegiatan</a></li>
        <li class="nav-item "><a class="nxlink  text-decoration-none" href="#kesimpulan">Kesimpulan</a></li>
        <li class="nav-item "><a class="nxlink  text-decoration-none" href="#lampiran">Lampiran</a></li>

          </ul>
      </div>

        <div class="barmbl rounded  mr-8 mr-2" style="background: #f9a114; z-index: 2000;" >
          <v-app-bar-nav-icon  class="pa-0 appbarcolor " color="white"  variant="" @click="isActive=!isActive"></v-app-bar-nav-icon>
        </div>
      </div>
    </nav>
    <section id="home" class="home">
      <div class="alltekshome my-auto" >
        <div class="teks-1">
          Halo, Saya
        </div>
        <div class="teksnama font-weight-black">
          Izanagi Faris Aslam
        </div>
        <div class="tekssiswa">
          Siswa di SMKN 2 Kota Bekasi
        </div>
      </div>

    </section>
    <section id="pendahuluan" class="pendahuluan">
      <div class="textjdl text-center">
        Pendahuluan
      </div>
      <v-row class="justify-center mt-6">
        <v-col style="max-width: 500px;">
          <div class="latarbelakangjdl mb-5">
            Latar Belakang PRAKERIN
          </div>
          <div class="latarbelakangisi">
            <div class="p-0" >
              Setiap siswa/siswi lulusan Sekolah Menengah Kejuruan (SMK) dituntut untuk mempunyai suatu keahlian dan siap kerja, karena lulusan SMK biasanya belum diakui oleh pihak dunia/industri, oleh karena itu diadakan suatu program Pendidikan Sistem Ganda (PSG) yaitu dengan melaksanakan Praktik Kerja Industri (PRAKERIN) agar setiap siswa/siswi lulusan SMK mempunyai suatu pengalaman dalam dunia usaha sebelum memasuki dunia usaha tersebut secara nyata setelah lulus sekolah. Sesuai dengan hasil pengamatan dan penelitian Direktorat Pendidikan Menengah Kejuruan, pola penyelenggaraan di Sekolah Menengah Kejuruan (SMK) belum secara tegas dapat menghasilkan tamatan sebagaimana yang diharapkan. Hal tersebut dapat dilihat dari kondisi pembelajaran yang belum kondusif untuk menghasilkan tenaga kerja yang professional, karena keahlian professional seseorang tidak semata-mata diukur oleh penguasaan unsur pengetahuan dan teknik bekerja, tetapi harus dilengkapi dengan penguasaan kiat bekerja yang baik. Ada dua pihak yaitu lembaga pendidikan dan lapangan kerja  (industri/perusahaan atau instansi tertentu) yang secara bersama-sama menyelenggarakan suatu program keahlian kejuruan. Dengan demikian kedua belah pihak seharusnya terlibat dan bertanggung jawab mulai dari tahap perencanaan program, tahap penyelenggaraan, sampai penilaian dan penentuan kelulusan siswa/siswi.
            </div>
          </div>
        </v-col>
      </v-row>
    </section>
    <section id="sejarah" class="sejarah">
      <div class="textjdl text-center">
              Sejarah
            </div>
      <div>
        <v-row class="mt-6">
          <v-col>
            <div>
              <v-img :src='require(`~/assets/1652414410274.jpg`)' width="500px" alt=""></v-img>
            </div>
          </v-col>
          <v-col>
            <div class="sejarahjdl mb-5">
              PT. TRASPAC MAKMUR SEJAHTERA
            </div>
            <div class="isisejarah">
              <div class="">
                <div>
                adalah perusahaan yang membantu menciptakan budaya digital organisasi dengan peningkatan kompetensi digital SDM, perancangan kembali proses kerja berbasis digital, dan pemanfaatan optimal teknologi informasi Artificial intelligence, Internet of Things, Big Data.
              </div>
                <span class="font-weight-bold"> PT. TRASPAC MAKMUR SEJAHTERA </span>Berdiri tahun 1997 di Surabaya. Dengan bisnis utama dibidang pengembangan aplikasi perangkat lunak dan penyedia jasa layanan ICT. Aktifitas utama perusahaan adalah pengembangan software untuk riset produk aplikasi atau penyelesaian proyek.. Traspac adalah perusahaan yang bergerak dibidang pembuatan perangkat lunak. Sejak pertama berdiri, perusahaan ini secara khusus telah mengembangkan berbagai solusi e-government. Mengkaji dan melakukan penelitian tentang regulasi, tata laksana serta sistem kepemerintahan dan mempelajari teknologi serta pengembangan sumber daya manusia menjadi focus dari Traspac. Kompetensi Traspac adalah pengembangan solusi aplikasi guna membantu pemerintah dalam memberikan pelayanan publik yang lebih baik dan menjalankan pemerintahan serta melaksanakan pembangunan yang efektif.
              </div>
            </div>
          </v-col>
        </v-row>
      </div>
    </section>
    <section id="kegiatan" class="kegiatan">
      <div class="textjdl text-center">
              Kegiatan
            </div>
            <div class="kegiatan-content mt-6">
            <div class="textkegiatan ">
              <v-row class="justify-center text-center">

                <v-col style="max-width: 500px;">
                  Selama PRAKERIN di PT. TRASPAC MAKMUR SEJAHTERA, kami diberi projek untuk membuat website Toko Online. berikut adalah bagian saya dalam mengerjakan projek projek tersebut.
                </v-col>
              </v-row>
              </div>
              <div class="kartu-keg mt-5">
                <v-row class="pa-0 ma-0">
                  <v-col>


                  <div class="kartukgthv rounded-lg text-center pt-8 " >
                    <i class="ikon ma-0 mdi mdi-brush" style="font-size: 60px;"></i>
                    <v-card-title class="jdlkartu justify-center">
                      Desain UI
                  </v-card-title>
                  <v-card-text class="deskkartu">
                    Membuat desain website menggunakan Figma sebagai User Interface agar memungkinkan pengguna berinteraksi dengan aplikasi
                  </v-card-text>
                </div>

                  </v-col>
                  <v-col>
                    <div class="kartukgthv rounded-lg text-center pt-8 card" >
                  <i class="ikon ma-0 mdi mdi-cloud-tags" style="font-size: 60px;"></i>
                  <v-card-title class="jdlkartu justify-center">
                    API
                  </v-card-title>
                  <v-card-text class="deskkartu">
                    Membuat API untuk akses terhadap layanan atau data untuk memungkinkan sistem atau aplikasi untuk berkomunikasi dan berinteraksi
                  </v-card-text>
                </div>
                  </v-col>
                  <v-col>
                    <div class="kartukgthv rounded-lg rounded-lg text-center pt-8 card" >
                      <div class="isikrt">

                        <i class="ikon ma-0 mdi mdi-file-table-box" style="font-size: 60px;"></i>
                        <v-card-title class="jdlkartu justify-center">
                          CRUD
                        </v-card-title>
                        <v-card-text class="deskkartu">
                          Membuat CRUD data agar mempermudah pengolahan informasi atau data secara treatur dan berurutan
                        </v-card-text>
                      </div>
                    </div>
                  </v-col>
                </v-row>

              </div>
            </div>
    </section>
    <div id="kesimpulan" class="kesimpulan">
      <div class="textjdl text-center">
              Kesimpulan
            </div>
            <v-row class="justify-center mt-6">
        <v-col style="max-width: 500px;">
          <div class="latarbelakangjdl mb-5">
            Kesimpulan
          </div>
          <div class="latarbelakangisi">
            <div class="p-0">
                    Setelah penulis menjalankan Praktik Kerja Industri (PRAKERIN) di . TRASPAC MAKMUR SEJAHTERA selama 3 bulan, maka penulis dapat mengambil kesimpulan bahwa PRAKTIK KERJA INDUSTRI itu sangat penting bagi pelajar Sekolah Menengah Kejuruan karena secara langsung peserta diklat dapat terjun langsung ke lapangan, serta dituntut untuk bertanggung jawab atas apa yang telah dilaksanakannya.  PRAKERIN ini peserta pendidikan dan latihan dapat menilai dan menghargai kemampuan diri sendiri.

            </div>
          </div>
        </v-col>
      </v-row>
    </div>
    <section id="lampiran" class="lampiran">
      <div class="textjdl text-center mb-6 ">
              Lampiran
            </div>
<v-row class=" justify-center">
<v-col style="max-width: 800px;">
  <v-carousel  hide-delimiters  cycle show-arrows-on-hover>
    <v-carousel-item v-for="(foto, i) in allfoto" :key="i"  cover>
      <v-img :src="require(`~/assets/lampiran/${foto.src}`)"></v-img>
    </v-carousel-item>
  </v-carousel>
</v-col>
</v-row>
          </section>
    <footer class="text-center"> <span class=""> Created by <a href="https://instagram.com/za.frs.slm?igshid=YmMyMTA2M2Y=">Izanagi Faris Aslam</a> | © 2023</span></footer>
  </div>
  </template>

  <script>
  export default {
    mounted() {
      document.addEventListener('scroll', function() {
  // sticky navbar on scroll script
  if (scrollY > 20) {
    document.querySelector('.navbar').classList.add('sticky');
  } else {
    document.querySelector('.navbar').classList.remove('sticky');
  }
});
    },
    data() {
      return {
        allfoto:[
          {src:'1.jpg',},
          {src:'2.jpg',},
          {src:'3.jpg',},
          {src:'4.jpg',},
          {src:'5.jpg',},
          {src:'7.png',},
          {src:'8.png',},
          {src:'9.png',},
          {src:'10.png',},
          {src:'11.png',},
          {src:'12.png',},
        ],
        isActive:false,
      }
    },
    methods: {
      aktif(){
       var d= document.getElementById("menu")
       d.classList.add('menuactivembl')
      }
    },
  }
  </script>
