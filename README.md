# kubernetes-dashboard
This Manifest will deploy Traefik version 1.7 in a kubernetes cluster<br/>
<br/>
Requirements<br/>
kubectl installed and configured<br/>
configure your desired email in the 05-daemonset.yaml in replace of "--acme.email=example@example.com"
configure your desired domain in 08-ingress.yaml in replace of host: customdomain-example.com
<br/>
### Usage<br/>
<pre>
kubectl apply -f ./
</pre>
<br/>
