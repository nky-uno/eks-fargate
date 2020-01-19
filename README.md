# eks-fargate

$ docker build -t fluentd:011802 ./  
$ docker images  
$ docker tag fluentd:011802 260859027812.dkr.ecr.ap-northeast-1.amazonaws.com/fluentd:011802  
$ docker push 260859027812.dkr.ecr.ap-northeast-1.amazonaws.com/fluentd:011802  

$ kubectl apply -f nginx-fluent.yaml  
$ kubectl apply -f fluent-configmap.yaml

https://blog.mosuke.tech/entry/2019/07/12/sidecar-fluentd-to-cloudwatchlogs/  
https://github.com/fluent-plugins-nursery/fluent-plugin-cloudwatch-logs/blob/master/example/fluentd.conf  
https://tech.ga-tech.co.jp/entry/2019/02/eks-production  
https://nishipy.com/archives/987
