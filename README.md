<!--
    TODO criar imagens
    iac timeline
    terraform x other iacs
    drill down presentation (terraform core workflow)
 -->

## Minhas configurações

```bash
alias tf="terraform"
alias tg="terragrunt"
alias tws="terraform workspace"
alias tffiles="touch main.tf variables.tf outputs.tf"

function plan() {
    terraform plan --var-file $1
}

function apply() {
    terraform apply --var-file $1
}

function init() {
    git init
    touch README.md .gitignore
}

```
