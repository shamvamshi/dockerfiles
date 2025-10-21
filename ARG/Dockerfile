arg version
from almalinux:${version:-9}
env COURSE="devops" \
    DURATION="120hours"
arg TRAINER="myself"
env TRAINER=$TRAINER
run echo "Hi, COURSE is ${COURSE}, DURATION is ${DURATION}, and TRAINER is ${TRAINER}, version: ${version}"
cmd ["sleep", "1000"]