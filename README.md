# GNN
GNN TSP
How do you add objective to a CQM instance named cqm?
Group of answer choices

cqm.add_objective()

cqm.new_objective()

cqm.objective()

cqm.set_objective()






Select the true statement(s).
Group of answer choices

No answer text provided.

One can set parameter of BQM hybrid solver to return 1000 samples.

Using BQM hybrid solver, one can solve an instance of CQM.

Hybrid BQM solver outputs only a single sample by default.

You can set BQM hybrid solver's parameter to sample 1000 samples.

You can solve problems formulated as a CQM using hybrid BQM solver.

BQM hybrid sampler is guaranteed to return optimal solution.

BQM hybrid sampler returns a single sample by default.






Select the true statement(s).
Group of answer choices

If a soft constraint is violated, then solution is not feasible.

In a CQM model, one can differentiate between hard and soft constraints.

If a hard constraint is violated, then solution is not feasible.

A constraint is set to soft through the keyword "soft=True"




Select the true statement(s).
Group of answer choices

In a CQM model, integer variables are not allowed.

In a CQM model, one can define linear constraints.

In a CQM model, one can define quadratic constraints.

One does not need to create a QUBO to use hybrid CQM solver.







Consider the following time-dependent Hamiltonian 
 H (t) H(t)=(1-\frac{t}{\tau})H_0+\frac{t}{\tau}H_p

 

Which one of the following(s) is(are) true?

Group of answer choices

The goal is to find the ground state of H_p

The goal is to find thr ground state of H_0

If the system is initialized with the ground state of H_p, it always remains in the ground state throughout the evolution

At t=0, only H_0 acts on the system






In D-Wave, interactions of the form J_{ijk}s_is_js_k
 can be implemented.
Group of answer choices

True

False






Adiabatic quantum computing is universal, i.e. you can simulate gate based quantum computers using adiabatic quantum computing.
Group of answer choices

True

False





How do you create a sampler to sample from D-Wave QPU with built-in minor embedding?
Group of answer choices

sampler = EmbeddingComposite(DWaveSampler())

sampler = MinorEmbedding(DWaveSampler())

sampler = EmbeddingComposite()

sampler = MinorEmbedding()




How do you create a sampler to sample from D-Wave default QPU?
Group of answer choices

sampler = DWaveSampler("default"))

sampler = DWave()

sampler = DWaveQPU()

sampler = DWaveSampler()




How do you set the annealing time to 100 microseconds when calling the sample function?
Group of answer choices

sampler.sample(bqm, num_reads=1000, anneal_time=100)

sampler.sample(bqm, num_reads=1000, time=100)

sampler.sample(bqm, num_reads=1000, annealing_time=100)

sampler.sample(bqm, num_reads=100)



