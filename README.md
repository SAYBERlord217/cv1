  <!DOCTYPE html>
  <html lang="en">
    <head>
      <style>
        .jumbotron {
          padding-top: 5rem;
          background-color: bisque;
        }
        #projects {
          background-color: #ffeedf;
        }
        section {
          padding-top: 5rem;
        }
        .egarbagong{
          list-style: none ;/*untuk menghilangkan titik*/
          display: flex ;/*agar tampilan sejajar*/
          gap: 1rem;/*jarak*/
        }
      </style>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Curriculum Vitae</title>
      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous" />
      <!--Fungsi bootstrap di atas Mengatur tampilan elemen seperti tabel, tombol, dan form.-->

    </head>
    <body style="background-color: blanchedalmond">
      <nav class="navbar navbar-expand-lg navbar-dark navbar fixed-top" style="background-color: #571b04">
        <!--navbar-expand-lg: Navbar bisa di-collapse (dilipat) di layar kecil.navbar-dark: Mengatur warna teks navbar menjadi putih.-->
        <div class="container">
          <a class="navbar-brand" href="#">M.Syahid I</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" href="#home">Home</a>
            </li>
                <li class="nav-item">
                <a class="nav-link" href="#about">About Me</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#Education">Education</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#Contacts">Contacts</a>
              </li>
              <li class="nav-item">
                  <a class="nav-link" href="#Find Me">Find Me</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <section id="home" class="jumbotron text-center">
        <img src="img/comics.jpg" alt="M.Syahid" width="200" height="210" class="rounded-circle" /><!--gunakan class="rounded-circle",untuk mengatur bingkai-->
        <h1 class="display-4">M.Syahid</h1>
        <p class="lead">Software Engginer | Developer</p>
      </section>

      <section id="about">
          <div class="container mt-4">
          
                <div class="row">
                  <!--<div class="col-md-4"><img src="https://via.placeholder.com/200" class="img-fluid rounded-circle" alt="Foto Profil" /></div>-->
                  <div class="col-md-8">
                    <h2>Muhammad Syahid Islamy</h2>
                    <h4>Kelas:</h4>
                    <p>Email:</p>
                    <p>Alamat:</p>
                    <p>Telepon:</p>
                    <p>Keahlian: Pengembang perangkat lunak berpengalaman dengan keahlian dalam HTML, CSS, JavaScript, React, dan Bootstrap.</p>
                  </div>
                </div>

      <div class="section-title">Perkenalan Diri</div>
        <div>
          <h4>Tonton video perkenalan diri saya</h4>
          <iframe width="100%" height="315" src="https://www.youtube.com/embed/YOUR_VIDEO_ID"></iframe>
        </div>
      </section>
      <br>
      <br>

      <section id="Education">
          <div class="container mt-4">
              <h4>Pengalaman Organisasi</h4>
          <table class="table table-bordered">
            <!--table: Membuat tabel dengan desain Bootstrap standar.table-bordered: Menambahkan border di setiap sel tabel.-->
              <thead>
                <tr>
                  <th>Tahun</th>
                  <th>Peran</th>
                  <th>Deskripsi</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>2022</td>
                  <td>Anggota Osis</td>
                  <td>Mengkoordinasi kegiatan sekolah.</td>
                
              </tbody>
            </table>
            <br><br>      
            <h4>Riwayat Pendidikan</h4>
            <table class="table table-bordered">
              <thead>
                <tr>
                  <th>Nama Sekolah</th>
                  <th>Tahun</th>
                  <th>Deskripsi</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>Sekolah Dasar ABC</td>
                  <td>2014-2020</td>
                  <td>Dasar-dasar pendidikan.</td>
                </tr>
                
              </tbody>
            </table>
          </div>

      </section>
      <br>
      <!--Contacts-->
      <section id="Contacts">
          <div class="container">
            <div class="row text-center mb-3">
              <div class="col">
                <h2>Contact Me</h2>
              </div>
            </div>
            <div class="row justify-content-center">
              <div class="col-md-6"></div>
              <!--col md8,untuk mengatur textfield agar tidak terlalu panjang-->
              <form>
                <!--textfield Email-->
                <div class="mb-3">
                  <label for="email" class="form-label">Email</label>
                  <input type="email" class="form-control" id="Email" aria-describedby="emai" />
                </div>
                <!--textfield Nama-->
                <div class="mb-3">
                  <label for="name" class="form-label">Masukkan Nama Lengkap Anda</label>
                  <input type="text" class="form-control" id="name" aria-describedby="name" />
                </div>
    
                <!--Text Area-->
                <div class="mb-3">
                  <label for="Textarea" class="form-label">Catatan</label>
                  <textarea class="form-control" id="Textarea" rows="3"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
                <!--kegunaan dari btn-primary Memberikan warna biru pada tombol.-->
              </form>
              <br />
            </div>
          </div>
        </section>
        <br>
        <section id="Find Me">
          <div class="container mt-4">
          <h3>Kontak dan Media Sosial</h3>
          <ul class="egarbagong">
            <li>       
              <a href="https://wa.me/+62889224097" ><img src="img/wa.jpg" style="height: 40px;" style="width: 40px;" alt=""></a>
          <br>
        </li>

        <li>
          <a href="https://Instagram.com/katasandi9653"><img src="img/ig2.jpg" style="height: 40px;" style="width: 40px;" alt=""></a>
          <br>
        </li>

        <li>
          <a href="https://www.facebook.com"><img src="img/fb.jpg" style="height: 40px;" style="width: 40px;" alt=""></a>
          <br>
        </li> 
        </ul>
          <br>
          </div>
      </section>
      <br>

      <!--Footer-->
      <!--pb atau padding break berguna untuk mengatur jarak-->
      <footer class="text-center pb-5" style="background-color: #571b04; text-white">
          <!--class="text-white" digunakan untuk memutihkan link-->
          <!--fw atau font-white-wight-bold digunakan untuk menebalkan--> 
          <p class="text-white">Created By <a href="https://www.gmail.com" class="text-white">Syahid</a></p>
        </footer>
        <!--Akhir Footer-->
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    </body>
  </html>
