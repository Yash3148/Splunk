# Splunk Standalone Instance with Splunk Operator 

A Kubernetes cluster administrator can install and start the Splunk Operator for cluster-wide by running:

#Step1 kubectl apply -f splunk-operator.yaml --server-side  --force-conflicts

#Step2 kubectl apply -n splunk-operator -f splunk-enterprise.yaml