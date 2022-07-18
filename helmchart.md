- Download published helm 
    ```
    helm pull chartrepo/chartname
    ```
    
- Create helm structure 
    ```
    # The directory name is the helm name
    helm create eksworkshop
    ```
    
- Test    
    ```
    # Test the Chart without deploy
    helm install --debug --dry-run <nome-diretorio> <caminho-diretorio>
    ```
    
- Deploy helm
    ```
    helm install workshop <caminho-diretorio>
    ```
    
- Update Helm
    ```
    helm upgrade workshop <caminho-diretorio>
    ```
    
- Show history
    ```
    helm history workshop
    ```
    
- Rollback history    
    ```
    helm rollback <nome-diretorio> <versão>
    ```
    
- Check status
    ```
    helm status <nome-diretorio>
    ```
