# Argo Rollouts + Istio Proposal

User would define the objects under `istio-rollout-user-objs.yaml`, namely:
* Rollout
* Service
* Gateway

This would result in the isto objects under `istio-rollout-owned-objs.yaml`, namely:
* DestinationRule
* VirtualService
