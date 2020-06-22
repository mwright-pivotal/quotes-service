# Tanzu Bank mods
- added config-map for use by SPring Cloud Kubernetes Config instead of Config server
- removed Registry and Hysterix dependencies since we 'll leverage K8s and Istio for these funcs
- IEX Cloud still offers a "free" plan to query stock data.   API endpoints have changed.  Sign up for a free account at https://iexcloud.io/ 

# quotes-service
This service is a spring boot application responsible for providing up to date company and ticker/quote information. 
