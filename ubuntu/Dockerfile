FROM ubuntu:14.04

RUN dpkg --add-architecture i386 && apt-get update

RUN apt-get install -y libc6:i386 libncurses5:i386 libstdc++6:i386 unixodbc:i386 unixodbc-dev:i386 libmyodbc:i386 mysql-client

ADD ../odbc/odbc.ini /etc/odbc.ini
