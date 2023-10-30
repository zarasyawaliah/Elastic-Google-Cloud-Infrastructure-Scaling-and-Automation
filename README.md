# 6 Elastic-Google-Cloud-Infrastructure-Scaling-and-Automation
- load balancer : 
1. Cloud CDN
2. SSL Proxy
3. TCP proxy
4. Network load Balancing
5. Internal load Balancing

- manage service
  1. big query
  2. dataprep
  3. dataprop
  4. dataflow
# 7 Getting Started with Google Kubernetes Engine
-Temporary Compute Engine VM
Command-line access to the instance through a browser
5 GB of persistent disk storage ($HOME dir)
Preinstalled Cloud SDK and other tools
gcloud: for working with Compute Engine, Google Kubernetes Engine (GKE), and many Google Cloud services
gsutil: for working with Cloud Storage
kubectl: for working with GKE and Kubernetes
bq: for working with BigQuery
Language support for Java, Go, Python, Node.js, PHP, and Ruby
Web preview functionality
Built-in authorization for access to resources and instances

# GKE Autopilot CLuster
Kubectl adalah alat baris perintah yang digunakan untuk berinteraksi dengan kluster Kubernetes. Berikut adalah beberapa perintah umum yang dapat dieksekusi dengan kubectl:

1. kubectl get: Untuk mendapatkan informasi tentang objek dalam kluster, seperti Pod, Service, Node, dan sebagainya.
2. kubectl create: Untuk membuat objek baru dalam kluster, seperti membuat Pod atau Service.
3. kubectl apply: Untuk menerapkan perubahan pada objek yang sudah ada atau membuat objek jika belum ada.
4. kubectl delete: Untuk menghapus objek dalam kluster.
5. kubectl describe: Untuk mendapatkan deskripsi rinci tentang objek tertentu, seperti kubectl describe pod <nama_pod>.
6. kubectl logs: Untuk melihat log dari sebuah Pod, seperti kubectl logs <nama_pod>.
7. kubectl exec: Untuk mengeksekusi perintah dalam sebuah kontainer yang sedang berjalan dalam Pod, seperti kubectl exec -it <nama_pod> -- /bin/sh.
8. kubectl port-forward: Untuk meneruskan port dari Pod ke localhost, sehingga Anda dapat mengakses servis yang berjalan di dalam Pod secara lokal.
9. kubectl get events: Untuk mendapatkan informasi tentang peristiwa dalam kluster.
10. kubectl config: Untuk mengelola konfigurasi kubectl, seperti mengatur konteks dan kredensial.
11. kubectl rollout: Untuk mengelola rollout pembaruan aplikasi, seperti kubectl rollout status, kubectl rollout history, dan kubectl rollout undo.
12. kubectl scale: Untuk mengubah jumlah replika dari sebuah Deployment atau ReplicationController.
13. kubectl label: Untuk menambah atau mengubah label pada objek, seperti Pod atau Node.
14. kubectl get nodes: Untuk mendapatkan daftar node dalam kluster.
15. kubectl proxy: Untuk menjalankan proxy ke dasbor Kubernetes.
Itu hanya beberapa contoh perintah kubectl yang umum digunakan. Terdapat banyak lagi perintah dan opsi yang dapat digunakan dengan kubectl untuk mengelola kluster Kubernetes. Anda dapat menggunakan kubectl --help atau kubectl <command> --help untuk mendapatkan bantuan tentang penggunaan perintah kubectl tertentu.

Google Cloud Operations Suite adalah platform yang menyediakan berbagai alat dan layanan untuk pengawasan, pemantauan, manajemen, dan pemecahan masalah aplikasi dan infrastruktur yang dijalankan di Google Cloud Platform (GCP). Ini sebelumnya dikenal sebagai Google Cloud Operations (sebelumnya dikenal sebagai Google Cloud Monitoring, Google Cloud Logging, dan Google Cloud Trace).

Beberapa komponen dan fitur utama dari Google Cloud Operations Suite meliputi:

1. *Google Cloud Monitoring*: Ini memungkinkan Anda untuk mengumpulkan dan memantau data kinerja aplikasi dan infrastruktur Anda. Anda dapat membuat metrik, melihat dasbor, dan menerima pemberitahuan tentang kejadian yang terkait dengan metrik.

2. *Google Cloud Logging*: Ini digunakan untuk mengumpulkan, menganalisis, dan menyimpan log dari aplikasi dan infrastruktur Anda. Log ini dapat membantu Anda dalam pemecahan masalah dan pemantauan aplikasi Anda.

3. *Google Cloud Trace*: Ini memungkinkan Anda untuk memantau dan menganalisis kinerja aplikasi Anda dengan mengukur latensi permintaan HTTP. Ini membantu Anda memahami kinerja aplikasi Anda dan menemukan masalah yang mungkin memengaruhi pengalaman pengguna.

4. *Error Reporting*: Ini membantu Anda mendeteksi dan melacak kesalahan di aplikasi Anda. Anda dapat menerima pemberitahuan tentang kesalahan, melihat rincian kesalahan, dan melacak status penyelesaian.

5. *Debugging*: Alat ini memungkinkan Anda menganalisis aplikasi Anda secara real-time untuk memecahkan masalah dan mengidentifikasi penyebab kesalahan.

Google Cloud Operations Suite membantu pengembang dan tim operasi untuk menjaga kinerja dan ketersediaan aplikasi di Google Cloud Platform, serta mempermudah pemecahan masalah dan pengelolaan infrastruktur.

Google Cloud Observability adalah konsep yang merujuk pada kemampuan untuk memantau, mengukur, menganalisis, dan memahami bagaimana sistem, aplikasi, dan infrastruktur berperilaku. Ini mencakup pengumpulan data performa, pemantauan, pelacakan, pemecahan masalah, serta penyediaan wawasan tentang kinerja aplikasi dan infrastruktur yang dijalankan di lingkungan Google Cloud atau di cloud atau sistem lainnya.

Google Cloud Observability mencakup beberapa elemen kunci, termasuk:

1. *Monitoring*: Ini melibatkan pemantauan secara terus menerus dari metrik performa aplikasi dan infrastruktur. Ini membantu dalam mendeteksi masalah atau perubahan dalam kinerja yang memerlukan tindakan.

2. *Logging*: Logging melibatkan pengumpulan dan analisis catatan (logs) yang dibuat oleh aplikasi, sistem, atau infrastruktur. Log digunakan untuk pemecahan masalah, pelacakan kejadian, dan audit.

3. *Tracing*: Ini melibatkan pemantauan dan analisis jalur eksekusi permintaan melalui aplikasi, yang membantu dalam pemahaman aliran kerja aplikasi dan mengidentifikasi titik-titik bottleneck atau kesalahan.

4. *Error Tracking*: Ini membantu dalam mendeteksi, melacak, dan mengelola kesalahan yang terjadi dalam aplikasi Anda. Hal ini membantu tim Anda dalam merespon dan memperbaiki masalah lebih efisien.

5. *Analytics*: Analitik digunakan untuk menganalisis data performa yang terkumpul dan mendapatkan wawasan tentang tren, perilaku pengguna, dan efisiensi aplikasi Anda.

6. *Dashboard dan Visualisasi*: Dashboard dan alat visualisasi memungkinkan Anda untuk menyajikan data performa dalam bentuk grafik, visualisasi, dan laporan yang mudah dimengerti.

Google Cloud Observability membantu organisasi dalam menjaga kinerja aplikasi dan infrastruktur mereka, mengidentifikasi masalah dengan cepat, dan memberikan pengalaman yang lebih baik kepada pengguna akhir. Ini juga membantu dalam pemecahan masalah, perencanaan kapasitas, dan pengambilan keputusan yang informasional. Google Cloud menawarkan berbagai layanan dan alat yang mendukung observabilitas di lingkungan komputasi awan mereka.
