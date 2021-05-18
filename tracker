import phonenumbers
from test import number 
from phonenumbers import geocoder
from phonenumbers import carrier

#to track the country of origin of the target number
ch_number = phonenumbers.parse(number, "CH")
print(geocoder.description_for_number(ch_number, "en"))


#to track the service provider of the target number
service_number = phonenumbers.parse(number, "RO")
print(carrier.name_for_number(service_number, "en"))
