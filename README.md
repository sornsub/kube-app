if no permissin to add ebs for db pod

aws iam put-role-policy --role-name masters.kubevpro.sornsub.online --policy-name EBSAccessPolicy --policy-document file://policy.json
aws iam put-role-policy --role-name nodes.kubevpro.sornsub.online --policy-name EBSAccessPolicy --policy-document file://policy.json

