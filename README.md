# Experimental Data-Driven Design of Novel Fe-Co-Ni Alloys with Enhanced Structural, Magnetic, Mechanical, and Electrical Properties

This work under final stage of preparation for manuscript submission.

* Historically, material development and deployment is a long and expensive process. Starting from development of a new material from lab to meeting the industrial criterias to finally commercially deploying the material in a particular application, it takes nearly 20 years and millions of dollars is spent. In material development, mainly 3 types of methodologies are followed - trial and error experiments, theoretical laws and modelling, and high performance computer based simulations. However, with the advent of data-driven science, the use of machine learning and high-throughput experiments in materials development is a boon in terms of reducing time and cost and increasing efficient search. 

* One such class of materials are magnetic alloys and commercially there is no alloy with optimized multi-property. FeCoNi is a potential alloy which can offer high saturation magnetization due to presence of Fe and Co, low coercivity due to presence of Ni, high Curie temperature due to presnce of Co, high mechanical strength due to Co and Ni, and moderate electrical resistivity due to presence of Ni.

* Therefore, in this work, a database of 40 Fe-Co-Ni alloys was produced using high-throughput  experiments of combination of ball milling and spark plasma sintering. Rapid structural, magnetic, mechanical, and electrical properties were measured and the cost of the alloy was calculated based on the composition.

* Using this experimental data, multi-input multi-output regression models (Random Forest, Extra Trees, 2 types of Neural Network architecture, Transfer learning-based Deep Neural Network) was developed. Extra Trees, one of the NN architecture and TL-based DNN was used with Gausian Process based multi-objective Bayesian optimization to design alloys.

* The results were compared with the experimental results to check if predicted property values follow the trend.

* Finally, 2 alloy compositions were designed based on targeted property values.

The codes and results for each step will be available shortly!