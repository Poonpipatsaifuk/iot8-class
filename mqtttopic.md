## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301016/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301016/model-01/sn-001
    - payload
        - {"temperature": "25.2"}
        - {"Humidity": "40"}
        - {"Detergent": "50"}
        - {"Imbalance": "13"}
        - {"Air_flow": "80"}
        - {"Noise_anamoly": "65"}
        - {"Water_level": "7"}
        - {"Rotating": "1200"}
        - {"Cool_down": "2"}
        

 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301016/model-01/sn-001
    - payload
        - {"Door_lock": "on"}
        - {"Lid_sensor": "30"}
        - {"Vibration": "25"}
        - {"Current": "115"}



