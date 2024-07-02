# Bio-sensor-based-non-invasive-health-monitoring-system-using-PIC
Due to non-invasive and point of care (POC) cortisol detection sensors system has heavy demand in medical application. The miniaturized portable DPV system can be developed for human salivary cortisol detection. Droplets of saliva are poured on bio-sensor electrodes; sensor will convert chemical reaction of saliva with electrodes to electrical voltage and current form. Output from ammonia gas sensor will be in voltage form the strength of output voltage and current will depends and proportional to chemical reaction takes place in sensor and gas generated at gas sensor. This output voltage and current is passed through signal conditioning and amplifier to make signal to readable range to ADC of microcontroller. ADC then converts signal in digital form as to read by microcontroller with 16-bit binary value. Microcontroller will read data and compare with inbuilt database and display in ASCII user readable language. Digital to analog converter (DAC) is used to plot the graph on graphical display for analysis. Compared with different set point will give results for early prediction and early stage detection for various diseases, immunity, lack of vitamins, organs health, cancer detection and more. Saliva is the composition of ammonia, urea, uric acid, cholesterol, glucose, fatty acids, triglycerides, neutral lipids, steroid hormones, glycolipid, amino acid, mucin, lectin, glycol-protein, peroxidase, lysozyme, lactoferrin, drug monitoring and many more add-on with more than 700-800 microorganisms, testing and analyzing the concentration of all these content will be very helpful for early prediction and initial stages detection of many diseases.
MQ series Gas sensors are very common types of sensors used in Gas Detectors to detect or measure certain types of Gases. These sensors are widely used in all Gas related devices like from simple Smoke Detectors to Industrial Air Quality Monitors. We In this article, we will learn how to use these gas sensors with PIC Microcontrollers, to measure the PPM value of the gas and display it on a 16x2 LCD.
As mentioned earlier, there are different kinds of MQ series sensors available in the market and each sensor can measure different types of gases as shown in the table below. For the sake of this article, we will be using the MQ6 Gas sensor with PIC that can be used to detect the LPG gas presence and concentration. However, by using the same hardware and firmware other MQ series sensors can also be used without major modification in the code and hardware part.
Sensor	Detects
MQ-2	Methane, Butane, LPG, smoke
MQ-3	Alcohol, Ethanol, smoke
MQ-4	Methane, CNG Gas
MQ-5	Natural gas, LPG
MQ-6	LPG, butane gas
MQ-7	Carbon Monoxide
MQ-8	Hydrogen Gas
MQ-9	Carbon Monoxide, flammable gasses.
MQ131	Ozone
MQ135	Air Quality (Benzene, Alcohol, smoke)
MQ136	Hydrogen Sulfide gas
MQ137	Ammonia
MQ138	Benzene, Toluene, Alcohol, Acetone, Propane, Formaldehyde gas, Hydrogen
MQ214	Methane, Natural gas
MQ216	Natural gas, Coal gas
MQ303A	Alcohol, Ethanol, smoke
MQ306A	LPG, butane gas
MQ307A	Carbon Monoxide
MQ309A	Carbon Monoxide, flammable gasses
MG811	Carbon Dioxide (CO2)
AQ-104	Air quality
