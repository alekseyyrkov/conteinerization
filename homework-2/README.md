1) add namespace kubedoom (kubectl create ns kubedoom)
2) kubectl apply -f kubedoom_deployment.yaml
3) sudo kubectl --namespace kubedoom port-forward --address 0.0.0.0 "pode name" 5901:5900
