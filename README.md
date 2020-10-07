# ObstacleDetector
The Obstacle Detector simply counts the number of clock cycles between the TIGEER and ECHO pin and then decides if an object is is front of it or not.
Speed of sound in air = 340m/s at room conditions.
For distance upto 1m, sound takes approximately 3ms to travel. This means an echo will return in 6ms back to the sensor.
At 50MHz, 6ms is 300,000 clock cycles.
