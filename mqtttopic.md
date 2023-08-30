## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301024/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301024/model-01/sn-001
    - payload
        - {"temperature": "25.2"}
        - {"load": "5.5"}
        - {"pressure": "2.5"}
        - {"water_level": "20"}
        - {"rotating": "2000"}
        - {"imbalance": "10"}
        - {"detergent": "50"}
        - {"humidity": "70"}
        - {"noise_anomaly": "50"}
        

 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301024/model-01/sn-001
    - payload
        - {"temperature": "35"}
        - {"radar": "5"}
        - {"current": "120"}
        - {"humidity": "50"}
        - {"vibration": "10"}
        - {"air_pressure: "1"}
        - {"touch_open/close": "0"}



