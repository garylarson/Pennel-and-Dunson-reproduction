# Pennel-and-Dunson-reproduction

This is a project I undertook to see if an AI tool could code up the MCMC for a complex Bayesian modeling application using the following rough steps:

1) Upload the paper PDF to an AI tool and request a LaTeX reproduction. Iterate until I have accurate LaTeX reproduction of the model and any relevant modeling details.
2) Upload the LaTeX details along with the paper and ask the AI model to write code that reproduces the modeling and MCMC. 

Some points:

- Either of these steps, especially Step 2, will have multiple sub-steps. 
- Why not just upload the paper and request the code? Why the intermediate step of getting the LaTeX? I did this because I thought adding the extra middle step of getting accurate LaTeX would help in the code generating process. This make sense given the simple fact that even asking for LaTeX reproduction of the paper's math does result in some notational errors. It seems foolish therefore to assume that just uploading the paper and asking for code would not contain more errors than there would be if I had LaTeX code that *did* produce the correct math notation.