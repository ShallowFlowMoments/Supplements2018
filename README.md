Supplementing material for the paper

## "Depth-projected Shallow Flow and Moment Approximations"

    Julia Kowalski, AICES Graduate School, RWTH Aachen University, kowalski@aices.rwth-aachen.de
    Manuel Torrilhon, Department of Mathematics, RWTH Aachen University, torrilhon@rwth-aachen.de


#### Abstract:  
Shallow flow models are used for a large number of applications including weather forecasting, open channel hydraulics and simulation-based natural hazard assessment. The shallowness of the process motivates depth-averaging and results in a mathematical system of mixed conditionally hyperbolic and parabolic type. While the shallow flow formulation is advantageous in terms of computational efficiency, it also comes at the price of losing vertical information such as the flow's velocity profile. This gives rise to a model error, which limits the shallow flow model's predictive power and is often not  explicitly quantified.
We propose the use of vertical moments to overcome this problem. The shallow moment approximation preserves information on the vertical flow structure while still making use of the simplifying and complexity reducing framework of depth-averaging. In this article, we derive a generic shallow flow moment system of arbitrary order starting from a set of balance laws, which has been reduced by scaling arguments. In addition, we derive a depth-projected, yet fully vertically resolved reference model by mapping the vertical coordinate onto the unit interval. We specify the shallow flow moment hierarchy for kinematic and Newtonian flow conditions and present 1D numerical  results for shallow moment systems up to third order. Finally, we  assess their performance with respect to both the standard shallow flow  model as well as with respect to the vertically resolved reference model.  Our results show that depending on the parameter regime, e.g. friction and slip, shallow moment approximations significantly reduce the model error in shallow flow regimes and have a lot of potential to increase the predictive power of computational shallow flow models, while keeping them computationally cost efficient. 

#### Program files (requires [Wolfram Mathematica](https://www.wolfram.com/mathematica/))

* DepthProjectedShallowFlow.nb
* ShallowFlowMoments.nb

#### To get started:
  1. open the file
  2. mark all cells (crtl+a)
  3. run (shift+enter)
