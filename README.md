# home_automation
installation de node red mosquitto influxdb grafana sur raspberry pi 1B :

grafana : installer version compatible avec arm6  

mosquitto : ajouter ces 2 lignes à mosquitto conf :  

  allow_anonymous true  
  listener 1883 0.0.0.0 


