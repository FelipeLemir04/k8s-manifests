# 🌐 Kubernetes + Minikube: Sitio Web Estático

Este proyecto despliega un sitio web estático (personalizado) en un clúster local de Minikube usando Kubernetes.

---

## 🔧 Requisitos

- Git
- Minikube
- kubectl
- Docker o VirtualBox
- Una carpeta local con el contenido del sitio (`static-website`)

---

## 📁 Estructura

- `deployments/`: Despliegue del contenedor (nginx)
- `services/`: Servicio para exponer la app en el navegador
- `volumes/`: Volumen persistente montado al contenedor

---

## 🚀 Instrucciones para desplegar

### 1. Clonar ambos repos:

```bash
git clone https://github.com/tu-usuario/static-website
git clone https://github.com/tu-usuario/k8s-manifests
