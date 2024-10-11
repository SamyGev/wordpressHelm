# wordpressHelm
Helm chart for wordpress on k8s

## Install the chart
git clone https://github.com/SamyGev/wordpressHelm.git  
helm install ./wordpressHelm --generate-name  
kubectl port-forward -n wordpress4 services/wordpress 8080:80  
<br/>
## About the chart
The chart is not on artifacthub, you need to clone the repo first  
there is a few variable, the most important one is namespace  
wordpress4 is set by default but can be change with values file  

