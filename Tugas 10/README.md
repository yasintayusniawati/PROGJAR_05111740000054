## Tugas 10

#### 1. Jalankan async_server.py pada port 9002, 9003, 9004, 9005 (lihat pada BackendList)
![1](https://github.com/yasintayusniawati/PROGJAR_05111740000054/blob/master/Tugas%2010/Screenshot/Run_async_server.py.png)

#### 2. Jalankan file lb.py, jalankan di port 44444
![2](https://github.com/yasintayusniawati/PROGJAR_05111740000054/blob/master/Tugas%2010/Screenshot/Run_lb.py.png)

#### 3. Jalankan browser, akseslah http://localhost:44444/page.html
![3](https://github.com/yasintayusniawati/PROGJAR_05111740000054/blob/master/Tugas%2010/Screenshot/lb.py_port_44444.png)

#### 4. Lihatlah di log program, bahwa setiap request akan dilayani oleh backend yang bergantian
![4](https://github.com/yasintayusniawati/PROGJAR_05111740000054/blob/master/Tugas%2010/Screenshot/log_lb.py.png)

#### 5. Lakukan performance test seperti pada tugas 9, bandingkan penggunaan load balancer dengan async_server dengan server_thread_http pada folder progjar5

#### Performance Test
  * Jumlah request    : 1000
  * Konkurensi        : 1,2,3,4

#### Load Balancer : PORT 44444
![5](https://github.com/yasintayusniawati/PROGJAR_05111740000054/blob/master/Tugas%2010/Screenshot/Load_balancer/hasil_test.JPG)

#### Server Async : PORT 45000
![6](https://github.com/yasintayusniawati/PROGJAR_05111740000054/blob/master/Tugas%2010/Screenshot/hasil_test_async.JPG)

#### Server Thread : PORT 46000
![7](https://github.com/yasintayusniawati/PROGJAR_05111740000054/blob/master/Tugas%2010/Screenshot/hasil_test_thread.JPG)
