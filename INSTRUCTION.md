## Run Todoapp

```
chmod +x bootstrap.sh
./bootstrap.sh
```
or
```
helm install todoapp-release .infrastructure/helm-chart/todoapp
```

## Validate helm chart
```
helm install todoapp-release .infrastructure/helm-chart/todoapp --dry-run
```

## Unistall helm chart
```
helm uninstall todoapp-release
```