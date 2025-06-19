 This thesis has been carried out at the Inria branch in Montpellier
 within the LEMON team, an interdisciplinary team working on the design and
 implementation of accurate and computationally inexpensive models for natural
 processes occurring in the littoral area. Urban-scale flood models are increas
ingly being studied in the context of risk prevention, to this end, for several years,
 the LEMONteamhasbeendeveloping so-called porosity models for the shallow wa
ter equations to provide rapid, large-scale simulations of these phenomena. Porous
 shallow water equations extend the classical shallow water model by introducing
 porosity to represent subgrid-scale effects caused by obstacles such as buildings
 and vegetation in floodplains. This work explores the use of variational data as
similation to improve the knowledge on the spatial distribution of porosity, and,
 ultimately, to increase accuracy in the prediction of the flood flow. Variational data
 assimilation is implemented using a gradient descent optimization approach, which
 efficiently computes the gradient through the adjoint problem. We present both
 the forward and adjoint formulations, along with their one-dimensional numerical
 solvers. Numerical experiments demonstrate the effectiveness of this approach for
 improving porosity estimation. We emphasize the importance of addressing the
 well-posedness of the assimilation problem to ensure reliable results.
