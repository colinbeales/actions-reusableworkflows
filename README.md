# actions-reusableworkflows

Small repo with some reusable workflows in GitHub Actions in use. In this repo are the called reusable workflows.

Shows how reusables can also
- Nest (i.e. call a reusable from a reusable)
- Matrix (i.e. be involked in a matrix strategy)
- Use OIDC (i.e. Call a cloud like Azure/AWS etc... within a reusable) - Note more config required to use the `job_workflow_ref` claim as per [OIDC in Reusables docs](https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/using-openid-connect-with-reusable-workflows)

Note: The caller of these reusable actions are defined in another repo [colinbeales/actions-reusable-demo](https://github.com/colinbeales/actions-reusable-demo)
