#linux

export JAVA_HOME=/opt/soft/jdk-13.0.2
export JRE_HOME=${JAVA_HOME}/jre
export CLASSPATH=.:${JAVA_HOME}/lib:${JRE_HOME}/lib:$CLASSPATH
export JAVA_PATH=${JAVA_HOME}/bin:${JRE_HOME}/bin
export PATH=$PATH:${JAVA_PATH}

https://mirrors.huaweicloud.com/openjdk/13.0.2/
