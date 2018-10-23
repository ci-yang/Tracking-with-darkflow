# Deap Sort Fix Version



運用自己訓練的 yolo  cfg 及 weight 生成 deep sort 的影片及 csv.



## 步驟



### Step1 環境建立 



#### Step1

Clone 我 Fork 下來並修改的檔案，請使用我的分支

```bash
$ git clone --single-branch -b FixDarkflow https://github.com/ci-yang/Tracking-with-darkflow.git
```





#### Step2

安裝需要的相依套件，已整理好直接使用以下指令可以安裝完畢

```bash
$ pip install -r requirements.txt
```



 





### Step2 事前準備



#### Step1 Darkflow

1. 先 cd 到此資料夾並將此套件安裝到全域環境

```bash
$ pip install .
```

2. 
3. 



#### Step2 Deep Sort

1. cd deep_sort 資料夾後到以下網址下載





#### Step  根目錄

1. 在 Tracking-with-darkflow 根目錄底下新增 cfg 檔案夾並將 coco.names 放入其中，裡面的內容為對應 cfg 的類別標籤

```

```

2. .cfg 檔案放置其中並命名為 yolo.cfg
3. 











### Step3 主程式 Run.py











### Step4 開始訓練











