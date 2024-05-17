# elk

    Install logstash
    Add filter-postfix.conf to /etc/logstash/conf.d or pipeline dir for dockerized Logstash
    Make dir /etc/logstash/patterns.d
    Add postfix.grok to /etc/logstash/patterns.d
    Restart logstash
