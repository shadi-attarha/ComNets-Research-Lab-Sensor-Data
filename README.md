# ComNets-Research-Lab-Sensor-Data (SeDa)
This work conducts several experiments to prepare several datasets containing sensor data from real-world IoT implementations, encompassing both healthy and faulty sensor readings. 


The first experiment involved two $DHT11$ sensors, utilizing thermistor technology for temperature measurement and polymer-based capacitive technology for humidity measurement. One of these sensors had experienced aging, leading to performance degradation over time \cite{marathe2021currentsense}, while the other was a new unit verified against a reference device. Data from both sensors were collected over a week every 10 minutes. The datasets were labeled based on the $DHT11$ datasheet, which specifies an accuracy of ±2 for temperature and ±5\% for humidity measurements.

In the second experiment, three $DHT11$ sensors were employed. Initially, two sensors were in a normal operational state and underwent calibration against a reference device, while the third sensor had experienced aging due to prolonged use. Subsequently, one of the healthy sensors was exposed to high-temperature conditions, resulting in an alteration of its operational characteristics and the generation of faulty data for both temperature and humidity measurements. The data was collected over a one-month period at 10-minute intervals and labeled based on a $DHT11$ datasheet.

The third experiment utilized three $SCD30$ carbon dioxide measurement sensors employing NDIR technology. These sensors began in a normal operational state, and their measurements were compared to those obtained from a reference device. Subsequently, one of the sensors was subjected to elevated temperatures to accelerate the degradation of its sensing material and potentially deform the optical chamber, both known factors associated with sensor faults under extreme stress conditions\cite{jia2021miniaturised}. Data were recorded at 12-minute intervals over ten days. The datasets were labeled according to the $SCD30$ datasheet with an accuracy of +/-50 ppm.

The obtained faulty data exhibited complex behavior in all three experiments, revealing the inadequacy of modeling faults with a single fault factor. As a result, a thorough understanding of sensor faults is required, given the possibility that a hazard, such as degradation, may produce multiple faults concurrently.

---
**NOTE** <br>
---
To Use the data, you need to reference this paper: <br> <br>
      @article{attarha2024assuresense, <br>
        title={AssureSense: A Framework for Enabling Sensor Fault Detection in Low-Power IoT Edge Devices},<br>
        author={Attarha, Shadi and F{\"o}rster, Anna},<br>
        journal={IEEE Sensors Journal},<br>
        year={2024},<br>
        publisher={IEEE}<br>
      }<br>

DOI: https://doi.org/10.1109/JSEN.2024.3451349


![alt text](https://github.com/ComNets-Bremen/ComNets-Real-Sensor-Data/blob/master/Humidity.png)
![alt text](https://github.com/ComNets-Bremen/ComNets-Real-Sensor-Data/blob/master/Temperature.png)
![alt text](https://github.com/ComNets-Bremen/ComNets-Real-Sensor-Data/blob/master/Co2.png)



