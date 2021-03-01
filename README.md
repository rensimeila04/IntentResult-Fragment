# IntentResult-Fragment


<p align="center">
  <a <code><img width="25%" src="https://github.com/rensimeila04/IntentResult-Fragment/blob/master/screenrecord1.gif"></code>
  </a>
</p>

## Fragment
<p> Fragment adalah salah satu bagian dari User Interface selain Activity. Bentuknya pun hampir sama dengan Activity, di mana ia memiliki class untuk kode logika dan tampilan XML. Bedanya yaitu kelasnya extends (inherit) ke Fragment dan tidak perlu didaftarkan ke dalam AndroidManifest.xml. 
</p>

<p align="center">
  <a <code><img width="25%" src="https://github.com/rensimeila04/IntentResult-Fragment/blob/master/fragment.gif"></code>
  </a>
</p>

## Fragment Lifecycle
<p>Fragment memiliki daur hidup sendiri dan bergantung penuh pada daur hidup activity dimana ia ditanamkan. Berikut ada beberapa <em>state</em> yang perlu kita ketahui sebelum menggunakan fragment.</p>
<ul><li><strong>Resumed</strong><br>Fragment bisa dilihat ketika activity sedang berjalan.</li><li><strong>Paused</strong>Ketika ada activity lain yang menutupi sebagian dari activity dimana fragment ditambahkan. Yang dimaksud menutupi sebagian adalah ketika activity-nya tidak tertutup sepenuhnya oleh activity lain. Jadi masih ada bagian dari activity yang masih bisa dilihat di layar.</li><li><strong>Stopped</strong><br>Ketika fragment tidak kelihatan di layar. Bisa jadi karena activity dimana fragment itu ditambahkan berhenti atau bahkan fragment itu sendiri sudah dihapus dari activity. Pada kondisi ini fragment masih hidup dengan semua informasinya. Akan tetapi sudah tidak kelihatan di layar dan akan dihancurkan.</li></ul>
<p>Skema di bawah ini menunjukkan <em>callback method</em> apa saja yang akan dipanggil di dalam fragment ketika terjadi perubahan pada sebuah activity.</p>

<p align="center">
  <a <code><img width="25%" src="https://developer.android.com/images/fragment_lifecycle.png?hl=id"></code>
  </a>
</p>

<p>Skema di atas menunjukkan bahwa perubahan <em>state</em> dari sebuah activity akan mempengaruhi <em>life cycle</em> dari sebuah <em>fragment</em>. Ini karena fragment merupakan komponen view yang bisa ditambahkan (<em>embed</em>) ke dalam activity.</p>

<h2> In App <h2>
<p align="center">
  <a <code><img width="25%" src="https://github.com/rensimeila04/IntentResult-Fragment/blob/master/ss1.jpg"></code>
  </a>
  <a <code><img width="25%" src="https://github.com/rensimeila04/IntentResult-Fragment/blob/master/ss2.jpg"></code>
  </a>
</p>
<p align="center">
  <a <code><img width="10%" src="https://www.vectorlogo.zone/logos/java/java-ar21.svg"></code>
  </a>
  <a <code><img width="10%" src="https://www.vectorlogo.zone/logos/android/android-ar21.svg"></code>
  </a>
 </p>
