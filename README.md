# service


  pack build 911848148261.dkr.ecr.us-east-1.amazonaws.com/kor-sdr-enforcer \
           --volume /home/akopachevskyy/1-prj/kor/sdr-enforcer/java/maven/binding:/platform/bindings/my-maven-settings \
           --builder paketobuildpacks/builder:0.1.98-base \
           --path . \
           --trust-builder 