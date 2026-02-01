# Muffin wallet

- [x] Разверните приложение muffin-wallet внутри кластера Kubernetes (minikube), используя манифесты Kubernetes или Helm-chart.
- [x] Разверните приложение muffin-currency внутри кластера Kubernetes (minikube), используя манифесты Kubernetes или Helm-chart.
- [x] Обеспечьте сбор логов из приложения muffin-wallet. 
- [x] Обеспечьте сбор трейсов системы. 

Запустить minikube.

Зайти в директорий local-env/helm запустить командой helmfile sync или helmfile apply.
Проверить, что запустились все поды в неймспейсах: muffin и monitoring
Зайти в Grafana и там создать дэшборд (соединения прописаны в yaml файлах графаны) 


