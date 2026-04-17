# Test Kubernetes Bundle Vendor Helm Rendered

E2E test repo for `kubernetes-bundle-vendor-helm-rendered` workflow in buildon-github-actions.

Tests Helm OCI chart fetch from bitnami/nginx, post-processing with sed patterns + yq transforms + file moves, image retagging with tag suffix, and stringtemplate token style.
