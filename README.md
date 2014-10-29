Run the agent by specifying the server location:

docker run -e TEAMCITY_SERVER=http://buildserver:8111 -e AGENT_NAME=agent01 -dt -p 9090:9090 lemonbar/centos6-teamcity-agent
