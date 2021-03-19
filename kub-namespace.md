## To create a new namespace

Use the following json. **namespace-dev.json**

    {
      "apiVersion": "v1",
      "kind": "Namespace",
      "metadata": {
        "name": "development",
        "labels": {
          "name": "development"
        }
      }
    }
    
Command:
    
    kubectl create -f namespace-dev.json
 
Get all namespaces:

    kubectl get ns
