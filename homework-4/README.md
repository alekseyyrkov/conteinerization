1) deploy ingress-nginx (LoadBalancer pending)
3) deploy metallb (add ip adress (свободные ip адреса в сети))
4) deploy postgress (все настройки с прошлой лабы переименовываем service )
5) deploy redmine (проверям доступность подов через указание в service NodePort)
6) добавил в hosts доменные имена redmine.org и adv.kz
7) deploy ingress-rules (добавляем доманные имена и указываем на какой сервис заворачивать клиентов)
8) ради интереча поднял сервер nginx с страничкой в отдельных подах что бы проверить как отрабатывает ingress контроллер
