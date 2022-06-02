# `pcluster describe-cluster-instances`<a name="pcluster.describe-cluster-instances-v3"></a>

Describe the instances in a cluster\.

```
pcluster describe-cluster-instances [-h] 
                 --cluster-name CLUSTER_NAME
                [--debug]
                [--next-token NEXT_TOKEN]
                [--node-type {HeadNode,ComputeNode}]
                [--query QUERY]
                [--queue-name QUEUE_NAME]
                [--region REGION]
```

## Named arguments<a name="pcluster-v3.describe-cluster-instances.namedargs"></a>

`-h, --help`  
Shows the help text for `pcluster describe-cluster-instances`\.

`--cluster-name, -n CLUSTER_NAME`  
Specifies the name of the cluster\.

`--debug`  
Enables debug logging\.

`--next-token NEXT_TOKEN`  
Specifies the token to use for paginated requests\.

`--node-type {HeadNode,ComputeNode}`  
Specifies the node types to list\. Supported values are `HeadNode` and `ComputeNode`\. If this parameter is not specified, both `HeadNode` and `ComputeNode` instances are described\.

`--query QUERY`  
Specifies the JMESPath query to perform on the output\.

`--queue-name QUEUE_NAME`  
Specifies the name of the queue to list\. If this parameter is not specified, instances in all queues are described\.

`--region, -r REGION`  
Specifies the AWS Region to use\. The Region must be specified, using the `AWS_DEFAULT_REGION` environment variable, the `region` setting in the `[default]` section of the `~/.aws/config` file, or the `--region` parameter\.