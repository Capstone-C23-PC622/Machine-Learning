# Deploy Flask dengan menggunakan Cloud Run 

Dokumentasi ini menjelaskan tentang bagaimana kami dan tim mendeploy model yang sudah dibuat.  

## Tech
- pandas 
- numpy 
- tensorflow 
- pickle
- matplotlib.pyplot
- tensorflow.keras.utils
- tensorflow.keras.utils.to_categorical
- tensorflow.keras.models
- tensorflow.keras.layers
- sklearn.tree
- sklearn.model_selection
- sklearn.compose
- sklearn.metrics
- sklearn.impute
- sklearn.preprocessing

## Cara deploy ke cloud-run menggunakan cloud shell
sh
$ gcloud init
$ gcloud services enable run.googleapis.com
$ gcloud builds submit --tag gcr.io/[project-id-kalian]/flask-model-deployment
$ gcloud run deploy --image gcr.io/[project-id-kalian]/flask-model-deployment --platform managed --region asia-southeast2 --allow-unauthenticated flask-model-ml

- Register / Login
- CRUD Biodata Pelamar / Pengusaha
- CRUD Lowongan 
- CRUD Profile

## Jika sudah berhasil tampilan akan seperti ini :
![gambar1](https://github.com/Capstone-C23-PC622/Machine-Learning/assets/75290755/2e492ef1-e104-474a-a060-cab432889a40)

![gambar2](https://github.com/Capstone-C23-PC622/Machine-Learning/assets/75290755/30b91f4b-a25b-4947-81d9-68743183cfa3)
## Setelah proses deploy selesai, saat di test pada POSTMAN
![gambar3](https://github.com/Capstone-C23-PC622/Machine-Learning/assets/75290755/0f4a3aa4-c5d6-4963-9fd2-e94ce2f63ccf)

## License

Tim Machine Learning Capstone-C23-PC622

*Capstone Bangkit 2023 Batch 1 :D*
