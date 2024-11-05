# azure-self-agent

docker run -e AZP_URL="https://dev.azure.com/{organization}" -e AZP_TOKEN="{token}" -e AZP_POOL="{pool}" -e AZP_AGENT_NAME="{agent_name}" --name "azp-agent-linux" azp-agent:linux
