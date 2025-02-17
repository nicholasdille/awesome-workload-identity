# Awesome Workload Identity

XXX workload identity

XXX based on OIDC

XXX avoid explicit credentials between services

XXX focus on automation and especially CI/CD

## By Consumer

### AWS

Kubernetes Service Accounts to AWS IAM role, a.k.a. [**I**AM **R**oles for Kubernetes **S**ervice **A**ccounts (IRSA)](https://docs.aws.amazon.com/eks/latest/userguide/iam-roles-for-service-accounts.html), [mutating webhook](https://github.com/aws/amazon-eks-pod-identity-webhook)

GitLab CI to AWS ([GitLab official documentation](https://docs.gitlab.com/ee/ci/cloud_services/aws/))

GitHub Action to AWS ([GitHub official documentation](https://docs.github.com/en/actions/security-for-github-actions/security-hardening-your-deployments/configuring-openid-connect-in-amazon-web-services))

### Azure

Kubernetes Service Accounts to [Azure workload identity](https://github.com/Azure/azure-workload-identity)

GitLab CI to Azure ([GitLab official documentation](https://docs.gitlab.com/ee/ci/cloud_services/azure/))

GitHub Actions to Azure ([GitHub official documentation](https://docs.github.com/en/actions/security-for-github-actions/security-hardening-your-deployments/configuring-openid-connect-in-azure))

### Cosign

[Keyless signing using OIDC tokens](https://docs.sigstore.dev/certificate_authority/oidc-in-fulcio/) for [GitHub](https://docs.sigstore.dev/certificate_authority/oidc-in-fulcio/#github), [GitLab](https://docs.sigstore.dev/certificate_authority/oidc-in-fulcio/#gitlab) and [SPIFFE](https://docs.sigstore.dev/certificate_authority/oidc-in-fulcio/#spiffe-1)

Keyless signing in GitLab CI ([GitLab official documentation](https://docs.gitlab.com/ee/ci/yaml/signing_examples.html))

### Google Cloud

GitHub Actions to GCP ([GCP official documentation](https://cloud.google.com/blog/products/identity-security/enabling-keyless-authentication-from-github-actions))

GitLab CI to GCP ([GitLab official documentation](https://docs.gitlab.com/ee/ci/cloud_services/google_cloud/))

GitHub Actions to GCP ([GitHub official documentation](https://docs.github.com/en/actions/security-for-github-actions/security-hardening-your-deployments/configuring-openid-connect-in-google-cloud-platform), [Google Cloud blog](https://cloud.google.com/blog/products/identity-security/enabling-keyless-authentication-from-github-actions))

### Jfrog

GitHub Actions to JFrog ([GitHub official documentation](https://docs.github.com/en/actions/security-for-github-actions/security-hardening-your-deployments/configuring-openid-connect-in-jfrog))

### Kubernetes

GitLab user against Kubernetes ([blog](https://www.hoelzel.it/kubernetes/2023/04/17/k3s-gitlab-oidc-copy.html))

## By Provider

**Checkout the list of OIDC providers in the [Awesome OpenID Connect](https://github.com/cerberauth/awesome-openid-connect?tab=readme-ov-file#openid-providers-op) list**

[GitHub OIDC](https://docs.github.com/en/actions/security-for-github-actions/security-hardening-your-deployments/about-security-hardening-with-openid-connect)

[GitLab OIDC provider](https://docs.gitlab.com/ee/integration/openid_connect_provider.html)

[Keycloak](https://www.keycloak.org/)

## Tools

kubectl plugin for Kubernetes OpenID Connect authentication ([GitHub repository](https://github.com/int128/kubelogin))
