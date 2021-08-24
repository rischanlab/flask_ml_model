# Cara mudah deploy machine learning model dengan Python Flask

Di pelatihan kali ini, kita akan belajar bagaimana caranya deploy machine learning model di Python kemudian kita pakai model yang sudah kita deploy menggunakan Flask. 

Di project ini ada dua percobaan yaitu: 

<ol>
<li>Prediksi sales </li>
<li>Prediksi Iris</li>
</ol>


### Iris: Gunakan command dibawah ini untuk mendapatkan prediksi iris
``` 
   curl -X POST \
   0.0.0.0:80/predict \
   -H 'Content-Type: application/json' \
   -d '[5.9,3.0,5.1,1.8]'
```

### Sales: Langsung gunakan UI dari web flask untuk mendapatkan prediksi sales


Flask bisa kita jalankan di laptop kita (i.e., localhost), bila masih ada waktu bisa mencoba menjalankan Flask dan deploy machine learning model kita di Cloud (AWS) 


Video: Simple way to deploy machine learning model using Flask on AWS (Cloud) https://youtu.be/I7sIOG0jBzk


Resources: 
<ol>
<li>https://towardsdatascience.com/simple-way-to-deploy-machine-learning-models-to-cloud-fd58b771fdcf</li>
<li>https://towardsdatascience.com/how-to-easily-deploy-machine-learning-models-using-flask-b95af8fe34d4</li>
</ol>
