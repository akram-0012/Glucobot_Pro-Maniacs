# Glucobot_Pro-Maniacs

Youtube Link: https://youtu.be/zOltJHRuAK4

Now a days, Diabetes has become an important life style related metabolic disorder. Normally, the estimation of glucose level is done by taking blood from the patient. There is a great demand to detect blood sugar without taking blood sample. Hence it is proposed to develop a non-invasive optical based glucose detection system.

Idea: The detection of glucose will be based on absorption spectroscopy. The Beer Lambert Law will be applied to detect glucose in the blood. When the incident light is incident on the body, apart of it is absorbed by the species present in the sample.

According to the Beer Lambert Law, attenuation of light in the tissue is given by Eq. 1 where I is the light intensity after absorption, I0 the incident light intensity, µeff the effective attenuation coefficient, and d the optical path length in the tissue. 

I=Io e^(-µeff d)

 µeff=f(µa,µs) 

The glucose has absorption in the range of 750–2500 nm wavelength (940nm wavelength is easily available in market). 

When the light signal (I0) of selected wavelength is passed through blood sample, the signal is absorbed by the sample depending upon the concentration of glucose and this signal after absorption (I) is detected by the detector. 

The glucose level can be estimated using equation 1. Important Hardware requirements: 

An IR LED of 940nm wavelength 

AN IR receiver 

A ESP32- system on a chip microcontroller with integrated bluetooth and wifi 

A LCD display

A constant voltage supply 

A box
