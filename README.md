# leaf disease detection

Çalışmamızda yüksek doğruluk ile yapraklardaki hastalıkları bulma amaçlanmıştır. Veri seti olarak plantvillage oluşturduğu veri seti içerinde 25 sınıf ele alınmıştır. Veri setinde %80 train, %20 test olmak üzere ikiye ayrılmıştır. Ardından % 80 train set içerisinde %15 validation set oluşturulmuştur. Eğitim aşamasında pytorch derin öğrenme kütüphanesi yararlanılmış olup batch size 16, epoch 30, learning rate 0.001 değerleri ele alınmıştır. Ayrıca optimizasyon algoritması olarak adam optimizasyon algoritması kullanılmıştır. Doğruluk oranını arttırmak için transfer öğrenim modellerinden biri olan resnet152 modeli kullanılmıştır. Eğitim sonunda %95.81 doğruluk değeri elde edilmiştir. 
Prediction aşamasında ise Python tkinter kütüphanesi kullanılarak GUI uygulaması gerçekleştirilmiştir.   
#
Veri seti:
https://www.kaggle.com/abdallahalidev/plantvillage-dataset
