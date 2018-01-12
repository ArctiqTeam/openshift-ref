# Custom Roles

This repository contains some customized roles for OpenShift. 


#### custom_ops_cluster_admin.yaml
This role is intended to reduce the capabilities of the cluster admin role such 
that cluster admins cannot view secrets from projects that they do not own, and 
cannot also create projects directly. That role/capability can easily be added 
to the appropriate group without needing to extend this role. 

