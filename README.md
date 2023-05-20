# self-hosted-aci-agent

## Docker Build

```shell
docker build -t dockeragent:latest .

docker run -e AZP_URL=<Azure DevOps instance> -e AZP_TOKEN=<PAT token> -e AZP_POOL=myagentpool -e AZP_AGENT_NAME=mydockeragent dockeragent:latest
```