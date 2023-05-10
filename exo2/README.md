EXO2:
Les commandes pour tester cette application sont:  
kubectl apply -f nomfichier

Ensuite: kubectl exec -it debug -- sh pour se connecter au shell de notre pod debug

saisir: wget -O- http://www ou wget -O- http://www.default 
pour tester l'application.


MANIFEST:
kubectl apply -f nomfichier
kubectl port-forward service/vote-ui 5000 et copier l'adresse ip sur mon navigateur ou localhost:5000/ pour tester l'app
kubectl port-forward service/result-ui 5001  et copier l'adresse ip sur mon navigateur ou localhost:5001/ pour tester l'app
