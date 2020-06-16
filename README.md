# Tanzu Bank mods
- added config-map for use by SPring Cloud Kubernetes Config instead of Config server
- removed Registry and Hysterix dependencies since we 'll leverage K8s and Istio for these funcs

# quotes-service
This service is a spring boot application responsible for providing up to date company and ticker/quote information. 
