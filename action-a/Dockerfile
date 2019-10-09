FROM debian:9.5-slim

LABEL "com.github.actions.name"="Hello world"
LABEL "com.github.actions.description"="Write arguments to standard output"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="https://github.com/octocat/hello-world"
LABEL "homepage"="https://github.com/actions"
LABEL "maintainer"="Octocat <octocat@github.com>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
