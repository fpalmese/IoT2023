# home-CoAPServer
Home automation using [CoAPthon](https://github.com/Tanganelli/CoAPthon)


How to run it:

- install the requirements `python3 -m pip install -r requirements.txt --user`
- `python3 coapserver.py`

Test:
- install [coap-cli](https://github.com/avency/coap-cli)
- `coap get coap://0.0.0.0:5683/dinning_room/temperature`
