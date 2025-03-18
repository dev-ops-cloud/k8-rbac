# Ingress controller

REGION_CODE=us-east-1
CLUSTER_NAME=expense
ACC_ID=557690626059

### Permissions

* OIDC provider(# one time step administaration will do)
...
eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve