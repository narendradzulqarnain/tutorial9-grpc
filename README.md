## Refleksi

1. What are the key differences between unary, server streaming, and bi-directional streaming RPC (Remote Procedure Call) methods, and in what scenarios would each be most suitable?
   - Dalam unary RPC, client mengirimkan sebuah request dan mendapatkan sebuah response. Unary RPC cocok untuk skenario request-response yang sederhana.
   - Dalam Server streaming RPC, client mengirimkan request dan menerima *stream* untuk membaca deretan pesan. Cocok untuk skenario dimana server perlu mengirimkan banyak data ke client.
   - Dalam Bidirectional RPC, client dan juga server saling mengirimkan banyak request dan response ke satu sama lain. Cocok untuk skenario dimana client dan server saling mengirimkan pesan secara asinkron.
   
