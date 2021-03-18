data source - https://www.kaggle.com/shrutibhargava94/india-air-quality-data

Objective:
The objective for this project is, how India’s few festival like Diwali, Eid, and
Christmas affects the air quality of the country. At first cleaning of the data is
done, to remove all the Nan values, and drop off columns which are least gonna
help in the model. Later that I would do feature engineering and combine the
columns, which results in pollution i.e so2, no2, rspm,spm.. Then late as the date
of the recording are specified so, I would try to create a column based on the date
that does that recording date before or after the three festivals. If it lies before
these months we give it value of 0, if it doesn’t we give it a value 1. Here there is
a column of type too i.e Industrial, Rural, Residential etc, we can use one hot
encoding to understand better a model. Then will try to implement ensemble
methods, such as Random forest, or K-NN models, to train models and find out a
relation between pollution and the festivals. Later we can use bagging,
bootstrapping- optimization and check how it behaves, with different proportion
of data.

Dataset details:
The data is combined(across the years and states) and largely clean version of the
Historical Daily Ambient Air Quality Data released by the Ministry of
Environment and Forests and Central Pollution Control Board of India under the
National Data Sharing and Accessibility Policy (NDSAP).
This dataset contains approximately 30K data points, it’s recorded from Dec 86 -
Dec15.
Columns:
• State : The state of india
• Location : City in the state.
• Type : Area where it belongs, I.e Residential, Rural, or Industrial
• so2: Sulphur dioxde (Pollution created in industrial power plants)
• no2: Nitrogen dioxide (Pollution created in industrial power plants)
• rspm:Respirable Suspended Particulate Matter (Produce by combustion
processes, vehicles and industrial sources.
• spm:Suspended Particulate Matter (dispersed through the air from combustion
processes, industrial activities or natural sources.)
