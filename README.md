Biologist
=========

Along with Trainer, Biologist is of the Support part of CreepCamp Service.
It's job is to generate Creeps and assist their evolution.
See the Biologist as a Solution generator, whereas Trainer is a Solution optmiser.

# Biologist purpose

* Generate new Creep blueprint ( Genotypes ), ultimately based on previously stored Genotypes
* Mutate Genotypes to provide new solutions possibilities.
* Overwatch living species

# Modules

* Control Port: User access API, will provide Biologist with it's mission.
* Action Port: The Biologist has to be able to start and overwatch Creep programs.
* Database Module: Ensure the Biologist never forget its creation ! Enable quicker solution finding algo. 
* Creep Generation and Mutation Modules: Main job of the Biologist is to generate Creep. These module will allow Creep creation, merge and mutations.

# Milestones:

1. Creep Generation Module  : Base creeps creation
2. Database Module I: Genotype Storage
3. Control & Action Port I: Basic Start ! 
4. Mutation Module I: Implement several mutation operations
5. Solution Module I: Try several mutations up to a best solution is found ( or enough tries have been done )
6. Database Module II: Stores by solution kind Genotypes, add taggings for nicer lookup and matching.
7. Mutation Module II: Implement Merge, add some more mutation operations.
8. Control & Action Port II: Allow multiple simulation to be running, add informations calls, access to Database



