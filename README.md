# eks-fargate

$ docker build -t fluentd:011802 ./  
$ docker images  
$ docker tag fluentd:011802 260859027812.dkr.ecr.ap-northeast-1.amazonaws.com/fluentd:011802  
$ docker push 260859027812.dkr.ecr.ap-northeast-1.amazonaws.com/fluentd:011802  

$ kubectl apply -f nginx-fluent.yaml  
$ kubectl apply -f fluent-configmap.yaml
