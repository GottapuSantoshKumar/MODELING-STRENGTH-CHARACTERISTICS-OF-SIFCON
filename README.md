# MODELING-STRENGTH-CHARACTERISTICS-OF-SIFCON
Slurry infiltrated fibrous concrete (SIFCON) is relatively a new type of
high strength and high performance fibre reinforced concrete in which moulds
are filled to its capacity with fibres and the resulting fibre network is infiltrated
by cement based slurry. Infiltration is usually accomplished by gravity flow.
Using steel fibres in concrete not only develops concrete performance against
fire and reduces spalling, but also increases structural resistance by taking into
account tensile behaviour of fibres. This study focuses mainly on behaviour of
SIFCON made with manufactured sand for various fibre fractions when
exposed to elevated temperatures 100°C, 200°C, 300°C and 400°C for 1hour,
2hours and 3hours exposure condition. The properties of concrete changes
when concrete structures are exposed to extreme temperatures. To predict the
response of structure after exposure to high temperature, it is essential that the
strength properties of SIFCON concrete subjected to elevated temperatures be
clearly understood. Therefore it is aimed at to study a new type of material,
termed SIFCON made with manufactured sand experimentally to determine
the strength characteristics of SIFCON for 8%, 10% and 12% fibre volume
fractions before and after subjected to elevated temperatures at different
exposure conditions. The results obtained from the study are studied and
compared with values of strengths of SIFCON before heat.
Conventional methods of predicting strength characteristics of concrete
are basically based upon statistical analysis by which many linear and
nonlinear regression equations have been constructed to model such a
prediction problem. These models have been developed based on a limited
number of data and parameters. If the new data is quite different from the
original data, then the model should be updated to include its coefficients and
also its equation. Therefore, there is a need to develop state of the art machine
learning or Artificial Neural Network (ANN) models that can predict the
strength characteristics of SIFCON made with manufactured sand accurately
with different fibre volume fractions under at various curing periods and
temperatures.

i

Artificial Neural Network modeling was selected over the conventional

methods for this study due to its ability to generalize multiple variable, non-
linear, complex relationships and thereby predict results from a range of inputs

with which they have been trained. ANNs are similar in structure and
functioning to the Biological Neural Networks (BNNs). The neurons learn
from their experimental data to detain the linear and non linear trends in the
complex data, so that they provide reliable predictions for new situations
containing even partial information. The artificial network design consists of
input and output vectors and the intermediate hidden layers. The processing
ability of the network is stored in the interneuron connection strengths called
weights. The weights are acquired by an adaptation process. Multilayer feed
forward back propagation neural networks were used for prediction analysis,
evaluation and comparison of the models.
In this thesis, a new feed forward and back propagation architecture of
ANN models are developed using four types of optimisation techniques
(Steepest Descent (SD), Genetic Algorithm (GA), Levenberg–Marquardt (LM)
algorithms) and Polynomial Curve Fitting model with R2

≈1 for accurate
prediction of strength properties of SIFCON with different fibre fractions at
different curing periods. A total of 15 ANN architectures are implemented for
each optimization technique combined with various combinations of ANN
topologies and the results are analyzed for the optimal ANN model that gives
the low MSE value. One of the major issues concerning the ANNs design is a
proper adjustment of the weights of the network. There have been a number of
studies comparing the performance of evolutionary and gradient based ANNs
learning. But the results of the studies, sometime conflicting to each other
although the same and standard data set development had been used. The
number of hidden layers directly affects the performance of the network.
Therefore, many experimental investigations are conducted. The architectures
of ANN model are found to be the best possible architectures for prediction of
SIFCON strength characteristics with different combinations are: i) LMANN
2-2-15-1, SDANN 2-4-14-1, GAANN 2-4-15-1 architectures; and the Poly2
curve fitting model for compressive strength, ii) LMANN 2-1-10-1, SDANN
2-2-14-1, GAANN 2-1-14-1; and the Polynomial degree 3 curve fitting model

ii

for Split tensile strength and iii) LMANN 2-2-10-1, SDANN 2-2-14-1,
GAANN 2-1-10-1 architectures; and the Poly3 curve fitting model for Flexural
strength predictions. These architectures have learnt the relationship for
predicting the strength of SIFCON (compressive, split tensile and flexural) in
different training epochs and they are implemented as per their respective
procedures. The training examples are so chosen that they will cover all the
variables (percentage fibre fraction, curing period and strength) involved in the
problem. The network could learn the strength prediction problem within a
maximum of 1000 iterations. Investigation was done on two aspects in this
research work. First one is evaluation of SIFCON strength with manufactured
sand utilizing quartz, as concrete through laboratory experiment. Second one is
to compare the experimentally observed value with the predicted results
obtained through the proposed ANN based and Polynomial Curve fitting
models.
In all the proposed ANN models, the compressive strength obtained
has gradually increased with the curing period from 7 to 91 days. On
comparison of addition of 8%, 10% and 12% steel fibres in concrete, 12%
fibre showed the maximum value in strength for all the curing periods. In the
case of 56 days of curing, there is a gradual increase in the compressive
strength obtained from 2% to 20% as the fibre volume fraction increases, and
when fibre percent increased beyond 20%, there is a drop in the compressive
strength. LMANN model performance is compared with all other models by
taking MSE as the criterion. Lower values of MSE are better and zero MSE
means no error. The LMANN, SDANN, Polynomial Curve fitting model,
GAANN are able to predict the strength characteristics of SIFCON concrete
satisfactorily with an accuracy of about 96%, 85%, 90%, and 92% respectively
for different percentage of fibre fractions and curing period. Thus, it is
concluded that the LM algorithm gives better performance and accuracy than
that of Curve Fitting, SD and GA algorithms. Hence, it is concluded that the
developed neural network models (LMANN 2-2-15-1, 2-1-10-1 and 2-2-10-1)
can be best served for predicting the strength characteristics (compressive,
split tensile and flexural) of SIFCON.
