FROM gittools/gitversion:v4.0.0-beta.12

WORKDIR /tmp/
ADD GitVersion_4.0.0-beta0014.zip .
RUN rm -rf /usr/lib/GitVersion/ \
    && unzip -d /usr/lib/GitVersion/ GitVersion_4.0.0-beta0014.zip && rm GitVersion_4.0.0-beta0014.zip
WORKDIR /usr/lib/GitVersion/    