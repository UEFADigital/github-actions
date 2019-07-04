FROM hashicorp/terraform:0.12.3

LABEL "com.github.actions.name"="terraform init"
LABEL "com.github.actions.description"="Run terraform init"
LABEL "com.github.actions.icon"="download"
LABEL "com.github.actions.color"="purple"

RUN apk --no-cache add jq curl

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
