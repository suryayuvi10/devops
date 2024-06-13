k8s_yaml("deployment.yaml")

k8s_resource('frontend-deployment', port_forwards='3000:8081')

docker_build('html-css', 'css')

allow_k8s_contexts('arn:aws:eks:ap-south-1:616663264699:cluster/kubernets-cluster')