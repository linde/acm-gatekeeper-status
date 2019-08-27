# Custom Resource Definition and Custom Resource syncing example

this is a example configuration for [Anthos Config
Management](https://cloud.google.com/anthos-config-management/). it has CRDs
from the
[spark-on-k8s-operator](https://github.com/GoogleCloudPlatform/spark-on-k8s-operator)
which are in the [cluster](config-root/cluster/) directory and it instantiates a
spark operator resource using the
[spark-operator.yaml](config-root/namespaces/spark-operator/spark-operator.yaml)
which lives in a dedicated namespace,
[spark-operator](config-root/namespaces/spark-operator).

the example here is to use ACM constraint templates to roll up monitoring status
for the operator.





