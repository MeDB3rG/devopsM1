# devopsM1

Créer les namespaces "nginx", "metallb", "prometheus"
Installer metallb avec helm puis helm upgrade de metallb avec les 2 fichiers 'IPAdressesPool" (modifier les adresses IP pour qu'elle soit en rapport avec vos IP) et le "announceIP" et  en précisant le namespace
Installer nginx avec helm avec les values.yaml en précisant le namespace
Installer prometheus avec helm avec les values.yaml puis edit le service avec la commande "kubectl edit svc prometheus-grafana -n prometheus" et modifier la ligne "ClusterIP" en "LoadBalancer"
