# ☸️ Kubernetes — Le projet qui m'a le plus impressionné

Honnêtement quand j'ai entendu parler de Kubernetes pour la première fois, 
j'avais peur. Ça semblait super complexe. Mais une fois qu'on comprend 
les bases, c'est vraiment impressionnant ce que ça fait automatiquement.

## 💡 Ce que j'ai fait

J'ai déployé mon app Python sur Kubernetes avec 3 copies qui tournent 
en même temps. Le truc qui m'a le plus bluffé : j'ai supprimé un pod 
manuellement et Kubernetes l'a recréé tout seul en quelques secondes. 
Sans que je fasse quoi que ce soit.

J'ai aussi installé Prometheus et Grafana pour surveiller mon infrastructure 
en temps réel. Me voir un vrai dashboard avec des graphiques de mon app 
c'était satisfaisant.

## 🛠️ Ce que j'ai utilisé

- **K3s** — une version légère de Kubernetes, parfaite pour apprendre
- **Docker Hub** — pour stocker mon image Docker
- **Helm** — le gestionnaire de paquets de Kubernetes
- **Prometheus** — pour collecter les métriques
- **Grafana** — pour visualiser tout ça avec de beaux graphiques

## 📚 Ce que j'ai compris

- La différence entre un Pod, un Deployment et un Service
- Pourquoi Kubernetes est indispensable en production
- Comment monitorer une infrastructure en temps réel
- Que les erreurs font partie de l'apprentissage aussi.

## 🔄 Comment ça marche

Mon image Docker (Docker Hub)
↓
Kubernetes télécharge l'image
↓
3 Pods lancés automatiquement
↓
1 Pod plante ? Kubernetes le recrée ✅
↓
Prometheus collecte les métriques
↓
Grafana affiche tout en temps réel 📊

## 💬 Mon retour honnête

C'est le projet le plus difficile que j'ai fait jusqu'ici. 
Il y a eu beaucoup d'erreurs et de moments où je ne comprenais pas 
pourquoi ça ne marchait pas. Mais c'est justement ça qui m'a le plus appris.
