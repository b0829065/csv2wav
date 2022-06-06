# csv2wav
csv2wav

使用流程： 

1.透過 

from google.colab import drive  

drive.mount('/content/drive') 

取得個人雲端資料 

 

2. 

fname = '/content/drive/MyDrive/physical_csv/KKBOX.csv'  

取得要轉換的csv檔 

註:csv檔格式 

Col1 =  x  

Col2 = y 

(x,y) is coordinate 

 

3.將轉換的csv檔存入雲端位置 

write_wav(sampled, "/content/drive/MyDrive/physical_csv/KKBOX" + ".wav", target_samplerate, 32700) 
