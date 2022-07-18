- Download published helm 
    ```
    helm pull chartrepo/chartname
    ```
    
- Create helm structure 
    ```
    # The directory name is the helm name
    helm create <chart-name>
    ```
    
- Test    
    ```
    # Test the Chart without deploy
    helm install --debug --dry-run <directory> <path-directory>
    ```
    
- Deploy helm
    ```
    helm install <chart> <path-directory>
    ```
    
- Update Helm
    ```
    helm upgrade <chart> <path-directory>
    ```
    
- Show history
    ```
    helm history <chart>
    ```
    
- Rollback history    
    ```
    helm rollback <directory> <version>
    ```
    
- Check status
    ```
    helm status <directory>
    ```
