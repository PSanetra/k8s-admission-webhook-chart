# Kubernetes Admission Webhook Helm Chart

This repository provides a Helm chart, which can be used to deploy generic validating and mutating admission webhooks.

The deployment requires an available cert-manager in the Kubernetes cluster to manage the TLS certificate of the webhook.
