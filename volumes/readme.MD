#ebs driver
kubectl apply -k "github.com/kubernetes-sigs/aws-ebs-csi-driver/deploy/kubernetes/overlays/stable/?ref=release-1.53"

#ebs permmision plocry
security --> IAM role -->add permission --> attach permission
1)AmazonEBSCSIDriverPolicy [attach this]
AmazonEBSCSIDriverPolicy

#