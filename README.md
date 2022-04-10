# DS_Predicting-concrete-strength

Can you predict the strength of concrete?
📖 Background
You work in the civil engineering department of a major university. You are part of a project testing the strength of concrete samples.

Concrete is the most widely used building material in the world. It is a mix of cement and water with gravel and sand. It can also include other materials like fly ash, blast furnace slag, and additives.

The compressive strength of concrete is a function of components and age, so your team is testing different combinations of ingredients at different time intervals.

The project leader asked you to find a simple way to estimate strength so that students can predict how a particular sample is expected to perform.

💾 The data
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

💪 Challenge

Provide your project leader with a formula that estimates the compressive strength. Include:

The average strength of the concrete samples at 1, 7, 14, and 28 days of age.
T
he coefficients 𝛽0, 𝛽1 ... 𝛽8, to use in the following formula:

𝐶𝑜𝑛𝑐𝑟𝑒𝑡𝑒 𝑆𝑡𝑟𝑒𝑛𝑔𝑡ℎ=𝛽0 + 𝛽1∗𝑐𝑒𝑚𝑒𝑛𝑡 + 𝛽2∗𝑠𝑙𝑎𝑔 + 𝛽3∗𝑓𝑙𝑦 𝑎𝑠ℎ + 𝛽4∗𝑤𝑎𝑡𝑒𝑟 +
𝛽5∗𝑠𝑢𝑝𝑒𝑟𝑝𝑙𝑎𝑠𝑡𝑖𝑐𝑖𝑧𝑒𝑟 + 𝛽6∗𝑐𝑜𝑎𝑟𝑠𝑒 𝑎𝑔𝑔𝑟𝑒𝑔𝑎𝑡𝑒 + 𝛽7∗𝑓𝑖𝑛𝑒 𝑎𝑔𝑔𝑟𝑒𝑔𝑎𝑡𝑒 + 𝛽8∗𝑎𝑔𝑒
