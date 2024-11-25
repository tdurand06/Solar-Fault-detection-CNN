# Solar-Fault-detection-CNN

This python script is a CNN classification machine learning project. The data contains 16 days of data of a grid-tie photovoltaic plant's operation with both faulty and normal operation. The paper achieved 99.88% accuracy with overfitting likely, and 98.31% accuracy with overfitting preventing methods including L2 regularizationa and neuron dropout, improving on the previous record for the dataset,97.64% accuracy

The faults include:

Short-Circuit (Short Circuit between 2 modules of a String)
Degradation (There is a resistance between 2 modules of a String)
Open Circuit (One String disconnected from the power inverter)
Shadowing (Shadow in one or more modules).

The paper and results i am trying to reproduce can be found here: [https://www.mdpi.com/1424-8220/22/21/8515#B29-sensors-22-08515](https://www.mdpi.com/1424-8220/22/21/8515#B29-sensors-22-08515)). This is the research that achieved 97.64% accuracy.

The data source can be found: [https://github.com/clayton-h-costa/pv_fault_dataset]([url](https://github.com/clayton-h-costa/pv_fault_dataset))

The data source origin is explained by this research group: [https://www.mdpi.com/1424-8220/20/17/4688](https://www.mdpi.com/1424-8220/20/17/4688))
