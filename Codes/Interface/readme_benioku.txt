The interface was run using VSCode.
After installing the required libraries for the relevant functions using "pip install", 
you can run the app.py file and access the interface via any web browser at 127.0.0.1:5000.
(The active IP addresses are also displayed in the VSCode terminal.)
Additionally, since the application is served on 0.0.0.0, 
any device connected to the same network can access the interface using the IP address of the machine running the code.

In the code, you can find that a "last.pt" model file is included.
This is supposed to be your trained model that will be doing the detections.
Please use your own model and put in in this directory: "Codes\Interface\yolo_xray_flask_app_v3"

------------------------------------------------


İlgili arayüzü "VSCode" üzerinden çalıştırdık.
İlgili fonksiyonlara ait kütüphaneleri "pip install" ile indirip,
app.py fonksiyonunu run ettiğiniz zaman 127.0.0.1:5000 adresi üzerinden herhangi bir tarayıcı ile açabilirsiniz.
(Zaten VSCode terminalde de hangi IP'lerde açıldığı yazar.)
Ayrıca 0.0.0.0'a yayın yaptığı için, internetinize bağlı her cihaz, kodu çalıştırdığınız cihazın IP adresi üzerinden arayüze erişebilir.

Kod içerisinde, "last.pt" dosyası göreceksiniz.
Bu sizin eğittiniz ve tespit yapacak olan modeliniz olmalıdır.
Lütfen bu dosya yoluna kullanacağınız modeli koyun: "Codes\Interface\yolo_xray_flask_app_v3"
