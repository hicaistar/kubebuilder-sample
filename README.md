# kubebuilder-sample
sample controller created by kubebuilder   
see [how to use kubebuilder](https://book.kubebuilder.io/)

## Generate project code
### Create a new project
$ kubebuilder init --domain k8s.io --license apache2 --owner "your-name"

### Create a new API(Resource)
$ kubebuilder create api --group hollow --version v1beta1 --kind Hollow

