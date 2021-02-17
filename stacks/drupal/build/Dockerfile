FROM srijanlabs/php-cli:7.3-buster

ARG stack_id

WORKDIR /workspace

# non-zero sets all user-owned directories to BUILTIN\Users
ARG cnb_uid=1000
ARG cnb_gid=1000

ENV CNB_USER_ID=${cnb_uid}
ENV CNB_GROUP_ID=${cnb_gid}

LABEL io.buildpacks.stack.id=${stack_id}
ENV CNB_STACK_ID=${stack_id}

USER continua