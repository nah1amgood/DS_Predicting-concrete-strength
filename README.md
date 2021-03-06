# DS_Predicting-concrete-strength

Can you predict the strength of concrete?
π Background
You work in the civil engineering department of a major university. You are part of a project testing the strength of concrete samples.

Concrete is the most widely used building material in the world. It is a mix of cement and water with gravel and sand. It can also include other materials like fly ash, blast furnace slag, and additives.

The compressive strength of concrete is a function of components and age, so your team is testing different combinations of ingredients at different time intervals.

The project leader asked you to find a simple way to estimate strength so that students can predict how a particular sample is expected to perform.

πΎ The data
The team has already tested more than a thousand samples (source):

Compressive strength data:

"cement" - Portland cement in kg/m3

"slag" - Blast furnace slag in kg/m3

"fly_ash" - Fly ash in kg/m3

"water" - Water in liters/m3

"superplasticizer" - Superplasticizer additive in kg/m3

"coarse_aggregate" - Coarse aggregate (gravel) in kg/m3

"fine_aggregate" - Fine aggregate (sand) in kg/m3

"age" - Age of the sample in days

"strength" - Concrete compressive strength in megapascals (MPa)

*Acknowledgments: I-Cheng Yeh, "Modeling of strength of high-performance concrete using artificial neural networks," Cement and Concrete Research, Vol. 28, No. 12, pp. 1797-1808 (1998)*.

πͺ Challenge

Provide your project leader with a formula that estimates the compressive strength. Include:

The average strength of the concrete samples at 1, 7, 14, and 28 days of age.
T
he coefficients π½0, π½1 ... π½8, to use in the following formula:

πΆππππππ‘π ππ‘πππππ‘β=π½0 + π½1βππππππ‘ + π½2βπ πππ + π½3βπππ¦ ππ β + π½4βπ€ππ‘ππ +
π½5βπ π’πππππππ π‘ππππ§ππ + π½6βπππππ π ππππππππ‘π + π½7βππππ ππππππππ‘π + π½8βπππ
