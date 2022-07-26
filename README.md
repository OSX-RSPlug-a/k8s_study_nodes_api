# k8s_study_nodes_api
This it's a study exercise to set up a k8s cluster with 3 nodes with one nodejs api

Commands:

      npm init -y
     
      docker build -t hello-api

      kind create cluster --name test-cluster --config ./nodes.yaml
      
      kind load docker-image hello-api --name test-cluster
      
      kubectl apply -f ./deployment-api.yaml
      
      
