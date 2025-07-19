# Інструкція розгортання

1. Зібрати Docker образ:
```bash
docker build -t your-username/todo-app .
```

2. Застосувати маніфести:
```bash
kubectl apply -f .infrastructure/k8s/namespace.yml
kubectl apply -f .infrastructure/k8s/
```
