# k8s-homework-6

## Задание 1

Ссылка на [манифест deployment.yaml](https://github.com/RiteHist/k8s-homework-6/blob/main/src/deployment.yaml)

Ссылка на [манифест configmap-web.yaml](https://github.com/RiteHist/k8s-homework-6/blob/main/src/configmap-web.yaml)

Скриншот проверки, что выводится HTML страница из ConfigMap:

![alt text](https://github.com/RiteHist/k8s-homework-6/blob/main/media/1.PNG?raw=true)

## Задание 2

Ссылка на [манифест secret-tls.yaml](https://github.com/RiteHist/k8s-homework-6/blob/main/src/secret-tls.yaml)

Ссылка на [манифест ingress-tls.yaml](https://github.com/RiteHist/k8s-homework-6/blob/main/src/ingress-tls.yaml)

Сриншот запроса `curl`:

![alt text](https://github.com/RiteHist/k8s-homework-6/blob/main/media/2.PNG?raw=true)

## Задание 3

Ссылка на [манифест role-pod-reader.yaml](https://github.com/RiteHist/k8s-homework-6/blob/main/src/role-pod-reader.yaml)

Ссылка на [манифест rolebinding-developer.yaml](https://github.com/RiteHist/k8s-homework-6/blob/main/src/rolebinding-developer.yaml)

Скриншот команд генерации сертификатов:

![alt text](https://github.com/RiteHist/k8s-homework-6/blob/main/media/3.PNG?raw=true)

Скриншот проверки прав с флагом `--as=developer`:

![alt text](https://github.com/RiteHist/k8s-homework-6/blob/main/media/4.PNG?raw=true)

Скриншот попытки удаления deployment под пользователем developer:

![alt text](https://github.com/RiteHist/k8s-homework-6/blob/main/media/5.PNG?raw=true)

