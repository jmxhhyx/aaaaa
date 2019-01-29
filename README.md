# DCIC-Failure-Prediction-of-Concrete-Piston-for-Concrete-Pump-Vehicles

# 赛题背景
对生产设备的维护，传统的做法主要有两类，一种是等故障发生后再维修，但这会导致非计划性的停产，经济损失大；第二种是以固定计划进行维护，但维修成本高，停机时间长。预测性维护，则通过分析故障历史数据和实时监测数据，对设备关键部件的剩余寿命或故障进行提前预测预警，并据此进行维护维修，从而减少设备非计划停机时间、降低维护成本。
（Traditional approaches to production equipment maintenance remain mainly in corrective maintenance and routine-based maintenance. Corrective maintenance, which is no fail no repair, implies unscheduled downtime of equipment, severe security risk and unacceptable economic loss, while routine or time-based maintenance is time consuming and costly. By data analysis and modeling, predictive maintenance forecasts the residual life or possible failure of key components, and schedules maintenance accordingly，in order to avoid unscheduled downtime and to save cost.）

砼活塞是混凝土泵车的关键部件，也是消耗性部件，活塞故障将导致泵车无法正常工作，同时可能导致整个工地其他配套设备无法正常施工，从而带来相当大的经济损失。活塞寿命与设备的具体工况等密切相关，通过物联网将泵车的实时工况数据等上传至工业互联网云平台，基于积累的数据建立合适的模型，有望对砼活塞在未来一定工作任务期间内可能出现的故障做出有效的预测预警，从而提醒作业人员在施工前进行必要的维护，避免因计划外停机而带来的经济损失。
（Concrete pistons are key and consumptive components of concrete pump vehicles. Failure of the piston will cause malfunction of the pump vehicle, which may even halt the whole construction site and bring unacceptable economic loss. Piston life is closely related to the specific operation conditions of the equipment. First, we upload floor data of pump vehicles through Industrial Internet of Things (IIoT) to the cloud platform. Second, we train appropriate models based on the accumulated data. And then we predict the possible failure of the concrete piston, and accordingly remind the operators to carry out necessary maintenance before construction, which is promising to avoid economic loss caused by unscheduled downtime.）


# 赛题任务
本赛题由中科云谷科技有限公司提供某类混凝土泵车砼活塞故障有关的数据，包括工作时间、发动机转速、油温、压力等多类工况数据，以及对应情况下，在未来完成给定工作量（混凝土泵送方量）的过程中，活塞是否故障的标识信息。希望参赛者利用大数据分析、机器学习、深度学习等方法，提取合适的特征、建立合适的故障预测模型，再根据测试数据预测该活塞在未来给定工作量内（泵送方量），是否会发生故障。
（Provided by ZVALLEY，data samples are extracted from floor data related to the concrete piston of some types of concrete pump vehicles, including worktime, engine rotation speed, hydraulic oil temperature, hydraulic pressure, etc. Sample labels indicate whether or not the piston will malfunction in the future on the given workload (pump volume). Contestants are expected to combine big data analysis and machine learning/deep learning techniques to extract features, establish failure prediction models， and forecast whether the piston will malfunction or not.）

