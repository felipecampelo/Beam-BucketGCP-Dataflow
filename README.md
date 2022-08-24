### ❗ Habilitando APIs necessárias no GCP ❗

`Link`: [Enable APIs](https://console.cloud.google.com/flows/enableapi?apiid=dataflow,compute_component,logging,storage_component,storage_api,bigquery,pubsub,datastore.googleapis.com,cloudresourcemanager.googleapis.com&_ga=2.189426155.1983962144.1622827940-955197899.1622719217&_gac=1.221249130.1622828282.Cj0KCQjwnueFBhChARIsAPu3YkSUzoSQn7RE14ObAE51mBY111345EEps_OAYCDz3smm2mLh2zjZ__8aAq9dEALw_wcB&wdLOR=cFAD8FEBF-3295-4A46-A7CC-2BD1857695D0)

▶ *Dataflow API*, *Compute Engine API*, *Cloud Logging API*, *Cloud Storage*, *Google Cloud Storage JSON API*, *BigQuery API*, *Cloud Pub/Sub API*, *Cloud Datastore API*, *Cloud Resource Manager API*

### ❗ Apache Beam ❗

`Passo a passo para instalação do Apache Beam no Colab:`

`1)` pip install --upgrade pip

`2)` pip install apache-beam[interactive]

`3)` Reiniciar ambiente de execução

`4)` pip install apache-beam[gcp]

`5)` Reiniciar ambiente de execução

`6)` import apache_beam as beam

`OBS: Nunca usar funções de exibição e gravação na mesma pipeline`
