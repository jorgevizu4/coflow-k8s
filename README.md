# Coflow Kubernetes Platform 🚀

Proyecto orientado al despliegue y gestión de una aplicación en un entorno Kubernetes utilizando contenedores y recursos declarativos.

El objetivo del proyecto es trabajar con conceptos fundamentales de Kubernetes como despliegues, servicios, configuración y administración de aplicaciones contenerizadas.

## 🏗️ Arquitectura

El proyecto utiliza un cluster Kubernetes local mediante Minikube para desplegar y gestionar los diferentes componentes de la aplicación.

Flujo general:

```
Código fuente
      |
      v
 Docker Container
      |
      v
 Kubernetes Cluster
      |
      v
 Aplicación desplegada
```

## 🛠️ Tecnologías utilizadas

### Kubernetes
- Minikube
- Kubernetes
- kubectl

### Contenedores
- Docker

### Configuración y despliegue
- Kubernetes YAML manifests
- Deployments
- Services
- ConfigMaps
- Secrets

## 🚀 Despliegue del entorno

### Requisitos

- Docker
- Minikube
- kubectl

### Crear cluster Kubernetes

Iniciar Minikube:

```bash
minikube start
```

Comprobar estado del cluster:

```bash
kubectl get nodes
```

## 📦 Despliegue de la aplicación

Los recursos de Kubernetes se definen mediante archivos YAML.

Ejemplo:

```bash
kubectl apply -f <archivo.yaml>
```

Consultar recursos desplegados:

```bash
kubectl get pods
```

Consultar servicios:

```bash
kubectl get services
```

## 🔧 Gestión del entorno

Durante el desarrollo se trabajan conceptos como:

- Creación y administración de Pods.
- Gestión de Deployments.
- Exposición de servicios mediante Kubernetes Services.
- Configuración de aplicaciones mediante archivos declarativos YAML.
- Administración del ciclo de vida de aplicaciones desplegadas en Kubernetes.

## 🎯 Objetivos del proyecto

Aplicar conocimientos relacionados con:

- Contenerización de aplicaciones.
- Orquestación con Kubernetes.
- Despliegues declarativos.
- Administración básica de clusters Kubernetes.

## 📚 Aprendizajes

El proyecto permite practicar:

- Uso de Kubernetes en un entorno local.
- Gestión de recursos mediante kubectl.
- Despliegue y actualización de aplicaciones contenerizadas.
- Trabajo con configuraciones YAML.

## 👨‍💻 Autor

Jorge Vizuete Méndez

Cloud / DevOps Junior

Tecnologías:
Kubernetes | Docker | Minikube | YAML
