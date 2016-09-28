# TeamCity systemd units

These files provide autostart for Teamcity's Server and Agent.

### Note:
* teamcity-agent.service: Service PIDfile should be the same as in conf/buildAgent.properties.
* teamcity-server.service: Serive PIDfile should be the same as in Environment="TEAMCITY_PID_FILE_PATH=..."
