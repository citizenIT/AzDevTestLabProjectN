# Some AZ Commands

| Command                                                                            | Def                             |
| ---------------------------------------------------------------------------------- | ------------------------------- |
| `az login`                                                                         | logins into azure               |
| `az group list -o table`                                                           | list resource groups in the sub |
| `az deployment group list -g $rg`                                                  | display deployments from rg     |
| `az deployment group validate -f template.json -p parameters.json -g $rg`          | validates an ARM template       |
| `az deployment group create -n $deploy -g $rg -f template.json -p parameters.json` | deploys the ARM template        |
