

This a model from the article:  
** A mathematical model of parathyroid hormone response to acute changes in plasma ionized calcium concentration in humans. **   
Shrestha RP, Hollot CV, Chipkin SR, Schmitt CP, Chait Y. _Math Biosci._2010
Jul;226(1):46-57. [20406649](http://www.ncbi.nlm.nih.gov/pubmed/20406649),  
**Abstract:**   
A complex bio-mechanism, commonly referred to as calcium homeostasis,
regulates plasma ionized calcium (Ca(2+)) concentration in the human body
within a narrow range which is crucial for maintaining normal physiology and
metabolism. Taking a step towards creating a complete mathematical model of
calcium homeostasis, we focus on the short-term dynamics of calcium
homeostasis and consider the response of the parathyroid glands to acute
changes in plasma Ca(2+) concentration. We review available models, discuss
their limitations, then present a two-pool, linear, time-varying model to
describe the dynamics of this calcium homeostasis subsystem, the Ca-PTH axis.
We propose that plasma PTH concentration and plasma Ca(2+) concentration bear
an asymmetric reverse sigmoid relation. The parameters of our model are
successfully estimated based on clinical data corresponding to three healthy
subjects that have undergone induced hypocalcemic clamp tests. In the first
validation of this kind, with parameters estimated separately for each subject
we test the model's ability to predict the same subject's induced
hypercalcemic clamp test responses. Our results demonstrate that a two-pool,
linear, time-varying model with an asymmetric reverse sigmoid relation
characterizes the short-term dynamics of the Ca-PTH axis.

The model corresponds to hypercalcemic clamp test explained in the paper and
parameter values used in the model are that of "subject 1". In order to obtain
the plots corresponding to "subject 2" and "subject 3" the following
parameters to be changed: lambda_1, lambda_2, m1, m2, R, beta, x1_n, x2_n,
x2_min, x2_max, t0, Ca0, Ca1 and alpha.

parameter | Subject 1  |  Subject 2 |  Subject 3  
---|---|---|---  
lambda_1  | 0.0125  | 0.0122  | 0.0269  
lambda_2  | 0.5595  | 0.4642  | 0.4935  
m1  | 112.5200  | 150.0000  | 90.8570  
m2  | 15.0000  | 15.0000  | 15.0000  
R  | 1.2162  | 1.1627  | 1.1889  
beta  | 10e+06  | 10e+06  | 10e+06  
x1_n  | 490.7800  | 452.8200  | 298.8200  
x2_n  | 6.6290  | 9.5894  | 5.4600  
x2_min  | 0.6697  | 1.4813  | 0.8287  
x2_max  | 14.0430  | 17.8710  | 15.1990  
Ca0  | 1.2200  | 1.2513  | 1.2480  
Ca1  | 0.2624  | 0.2267  | 0.2132  
t0  | 575  | 575  | 575  
alpha  | 0.0569  | 0.0563  | 0.0421  
  
This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2010 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)

