# GEORADIO
 Test days 1-3
 
 https://gienahdata.github.io/GEORADIO/ 
 
 ![georadio](https://user-images.githubusercontent.com/56297706/188924338-6827c1e2-359a-4dcf-9caa-79f77e293e25.png)

We started developing Georadio a year ago to ensure the high-quality data supply required for our research. Georadio is a mobile application based on Bluetooth technology that, acting as a moving detector, identifies Bluetooth devices around, then transmits detected MAC ID-s of devices along with the mobile phone's location data to a server. Data processing follows the European and domestic data protection regulations and the legal interpretation of the CMS law firm (see the attached Resolution, available only in Hungarian). We developed Georadio as a mobile application, but we are working towards elaborating a hardware solution.
During a two-round competition with Georadio, we entered the Proof-of-Concept programme of Óbuda University, during which we examined market utilisation and the general framework of patenting. In addition, with Georadio, we won the open call of the NEANIAS European Open Science Cloud program (Horizon RIA), where we examine research infrastructure and service applications that can be built upon location data collection.

To move forward, we needed to test the application to assess how large a population we can detect by Georadio and how large a fleet of devices is required to collect a reliable sample. We elaborated a three-day test on July 19-21, 2022. For those three days, we asked collegues to run Georadio anonymously on Android mobile phones. Since the program is designed for hardware and not for mobile devices, it was not necessary to get developed for iOS.

App stores mark Georadio as a potentially dangerous application due to location data sharing. The same application stores, however, enable applications frequently used by Open Source Intelligence without drawing attention to cybersecurity threats. The difference between these – most of all, fitness and navigation – application and Georadio is that, while the former hide the consent to data sharing with third parties, Georadio detects location data and equipment identifier by openly indicating the purpose of data collection (see Privacy Policy, available only in Hungarian). The application is safe to use and can be removed from your mobile phone quickly and entirely with one click at the end of the test.

At the webmap the results of the three-day test is presented. 

We detected a total of 20,448 different Bluetoot devices (BTs) during the 3 days by 13 active sensor devices.
A BT device - not trivially the detector itself - furthest detections: 151 km, 112 minutes apart, a Forerunner 35.

Most BT detections of 1 user within 1 second:
- Westo, 67 BT, Astoria
- deneb, 56 BT, Kelenföld railway station
- Pokatylov, 52 BT, Westend Shopping Center
- Matei, 39 BT, Erzsébet körút, Stifler Pool

Most BT detections of 1 user within 1 minute (all different BTs):
- Pokatylov, 201 BT, Westend Shopping Center
- Westo, 142 BT, Astoria

There were 10 BT devices detected by 3 users and 213 BT devices detected by 2 users.
Example: 
Pokatylov detected the 'OPPO A15s mobile phone' device at the southern corner of the Westend, with an accuracy of 23m, then approx. 3 hours later, the same device was detected by Kocsmárosé, close to the crossing in front of Nyugati, with an accuracy of 25m. 

Among the 213 BT devices detected by 2 users:
- 63 unknown BT names,
- 37 Lime scooters,
- 35 TVs (at least those that are easily recognizable),
- 17 TIER scooters,
- 3 KKSLOCK (MOL Bubi),
- 3 Huawei,
- 2 MIBOX4, etc.
