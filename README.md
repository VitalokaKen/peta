
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>KJPP Hari Utomo dan Rekan</title>
  <link rel="stylesheet" href="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/fontawesome-free/css/all.min.css">
  <link href="https://diy.magis.unwahas.ac.id/css/app.css" rel="stylesheet">
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"
    integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A=="
    crossorigin="" />
  <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"
    integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA=="
    crossorigin=""></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.5.1/chart.js"></script>
  <!-- jQuery -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/jquery/jquery.min.js"></script>
  <!-- Bootstrap 4 -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/bootstrap/js/bootstrap.bundle.min.js"></script>
  <!-- DataTables -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables/jquery.dataTables.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-bs4/js/dataTables.bootstrap4.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-responsive/js/dataTables.responsive.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-responsive/js/responsive.bootstrap4.min.js"></script>
</head>

<style>
  body {
    font-family: 'Montserrat', 'sans-serif';
  }
</style>
    <div class="content-wrapper">
      <!-- Main content -->
      <div class="content">
<div class="row mx-5 mt-3">
   <div class="col">
    <a href="GISKJPPHU.html" class="btn" style="background-color: #84C2D8; border-radius: 10px">Kembali</a>
   </div>
</div>
<div class="row mt-3 mx-5">
  <div class="col-sm-6">
    <div class="card">

      <div class="card-body">
        <h3 class="card-title">
          Peta
        </h3>
        <hr>
        <div id="map" style="width: 100%; height: 550px;"></div>
      </div>
    </div>
  </div>
  <div class="col-sm-6">
    <div class="card">
      <!-- /.card-header -->
      <div class="card-body">
        <h3 class="card-title">
      Gambar
        </h3>
        <hr>
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
          <ol class="carousel-indicators">
           <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          </ol>
          <div class="carousel-inner">
                        <div class="carousel-item active" data-bs-interval="2000">
				<img class="d-block w-100" src="OBJEK ANDRI.png" alt="First slide">
            </div>
                      </div>
          <a class="carousel-control-prev" href="OBJEK ANDRI.png" role="button" data-slide="prev">
            <span class="carousel-control-custom-icon" aria-hidden="true">
              <i class="fas fa-chevron-left"></i>
            </span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="OBJEK ANDRI.png" role="button" data-slide="next">
            <span class="carousel-control-custom-icon" aria-hidden="true">
              <i class="fas fa-chevron-right"></i>
            </span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
      <!-- /.card-body -->
    </div>
  </div>
</div>
<div class="row mt-3 mx-5">
  <div class="col-md-6 ">
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">Detail Objek</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
          <thead>
			 <tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td>Jalan Raya Teluk Gong No 9A			
Kelurahan Pejagalan, Kecamatan Penjaringan			
Kotamadya Jakarta Utara, Propinsi DKI Jakarta																												
			</td>
            </tr>
			 <tr>
              <td>Basis Nilai</td>
              <td>: </td>
              <td>Nilai Pasar dan Indikasi Nilai Likuidasi</td>
            </tr>
			<tr>
              <td>Tanggal Inspeksi</td>
              <td>: </td>
              <td>5 Juli 2022</td>
            </tr>
			<tr>
              <td>Tanggal Penilaian</td>
              <td>: </td>
              <td>5 Juli 2022</td>
            </tr>
			<tr>
              <td>Tahun Penilaian</td>
              <td>: </td>
              <td> 2022 </td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B008'15.8%22S+106%C2%B047'03.5%22E/@-6.1377157,106.7817271,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.137721!4d106.784302?entry=ttu">
 -6.137721, 106.784302												
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Rumah Tinggal</th>
            </tr>
           <tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td> 2.281 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td> 2.435 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp 52.116.230.000,-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp 21.800.000,-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <!-- /.card -->
 <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 1</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">

          <tbody>
			<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td>Jalan Raya Teluk Gong		
	</td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B008'18.7%22S+106%C2%B046'39.4%22E/@-6.1385227,106.7750351,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.138528!4d106.77761?entry=ttu">
-6.138528,106.77761						
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Gudang</th>
            </tr>
           <tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td>Agen Properti</td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td>0812 1062 1900</td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td> 799 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td> 500 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp 24.000.000.000,-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp 25.644.556,-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 2</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
          <tbody>
			<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td>Jalan Raya Teluk Gong		
	</td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B008'18.1%22S+106%C2%B046'49.7%22E/@-6.1383457,106.7778831,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.138351!4d106.780458?entry=ttu">
-6.138351, 106.780458				
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Gudang</th>
            </tr>
			<tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td>Agen Properti</td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td>0813 1116 0623</td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td> 1.700 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td> 247 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp 45.900.000.000,-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp 23.977.447,-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <!-- /.card -->
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 3</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
         <tbody>
			<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td>Jalan Raya Teluk Gong			
	</td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B008'19.8%22S+106%C2%B046'37.6%22E/@-6.1388307,106.7745301,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.138836!4d106.777105?entry=ttu">
-6.138836, 106.777105	
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Gudang</th>
            </tr>
           <tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td>Agen Properti</td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td>0877 0877 7082</td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td> 587 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td> 704 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp 20.000.000.000,-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp 27.336.286,-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</div>
  

<script>
  var peta1 = L.tileLayer('https://api.mapbox.com/styles/v1/{id}/tiles/{z}/{x}/{y}?access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NXVycTA2emYycXBndHRqcmZ3N3gifQ.rJcFIG214AriISLbB6B5aw', {
            attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, ' +
                '<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, ' +
                'Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
            id: 'mapbox/streets-v11'
        });
    
    
        var map = L.map('map', {
            center: [-7.9409693,110.5509868],
            zoom: 14,
            layers: [peta1],
        });
    
        var baseMaps = {
            "Grayscale": peta1,
           
        };
    
        L.control.layers(baseMaps).addTo(map);



        var iconsekolah = L.icon({
            iconUrl: 'OBJEK ANDRI.png',
            iconSize:     [300, 300],        
        });

		var informasi = '<table class="table table-bordered"> <tr><td colspan="2"><a href="https://www.google.com/maps/dir//-7.9409693,110.5509868" class="btn btn-sm btn-default">Rute</a></td></tr></body></table>';
         L.marker([-7.9409693,110.5509868],{icon: iconsekolah})
        // .bindPopup(L.popup({maxWidth:500}).setContent('<a href="https://www.google.com/maps/dir//-7.9409693,110.5509868" target="_blank">Rute Ke Lokasi</a>'))
		 .addTo(map);
</script>
      </div>
    </div>
  </div>
</body>
</html>
