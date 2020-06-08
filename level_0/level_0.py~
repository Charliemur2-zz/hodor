#!/usr/bin/python3
"""
Write a script or a program that votes 1024 times for your id
"""
import requests


address = "http://158.69.76.135/level0.php"
pay_load = {"id": "871", "holdthedoor": "submit"}
for i in range(1024):
    requests.post(address, data=pay_load)
    print("votos :  {}".format(i))
