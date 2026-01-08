# Energy Profiling Project Summary

During my internship at Apleona Ireland, I developed scripts designed to automate and streamline the energy profiling of commercial buildings using granular sensor data. 

Apleona relies on accurate data to identify baseload energy consumption across various building assets. Understanding the specific energy demands of individual systems, such as HVAC, lighting, and server rooms, is critical for helping clients pinpoint inefficiencies. By quantifying these "energy signatures", companies can implement data-driven strategies to significantly reduce operational costs and their carbon footprint.

While initially validated on office environments (data in this repository has been generated), this application can be scaled for larger usages. It can be used to profile larger industrial facilities, generating precise energy signatures for every appliance or structural component.

# Breakdown of Project

* **Objective**: To analyze and energy-profile office spaces by leveraging time-series data collected from building sensors.


* **Problem**: Energy profiling requires engineers to manually monitor and interpret live sensor tables to determine when energy systems were active. For large buildings with many sensors, this manual process could take several hours, making profiling time-consuming and inefficient.

* **Solution**: I developed code that automated energy profiling workflow. Rather than manually inspecting each sensor in real time, engineers can record the on/off timestamps for energy systems and analyze these events through generated visualizations after data collection. This approach significantly reduced the need for manual monitoring and enabled faster, more scalable analysis. 

# Project Structure

* **CLEAN_analysis.ipynb**: Contains Python functions for data processing, statistical analysis, and visualization. Includes an example for conducting analysis on an energy signature for an individual system.
* **data/**: A directory storying raw sensor data. Data is partitioned by day to align with a day of profiling a building.
