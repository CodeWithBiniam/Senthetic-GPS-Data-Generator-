# Senthetic-GPS-Data-Generator-


This script generates a new GPS data point every second. The data is printed to the console, but in the feature case, I would want to send this data to my Kafka topic.


This program that generates random but plausible latitude and longitude values within a certain range. These ranges can be set based on the area wanted to be simulated, such as a specific city or neighborhood. In this case city of Toronto is choosen.

For the "device_id", I create a list of unique identifiers and randomly assign one to each data point.

The "timestamp" field can be set based on the current system time whenever a new data point is generated, ensuring that each data point has a unique timestamp.

The "speed" can also be randomly generated, within a certain plausible range for vehicle speeds.


