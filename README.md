# iot-led-control
python file to control led connected to wifi module


from boltiot import Bolt
api_key = "your api key"
device_id  = "your device id"
mybolt = Bolt(api_key, device_id)
#response = mybolt.digitalWrite('0', 'LOW')
response = mybolt.analogWrite('0','0')
print (response)

