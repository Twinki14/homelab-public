# homelab-public

## Sealing secrets
```bash
kubeseal -f secret.yml > sealed-secret.yaml -o yaml --scope cluster-wide
```