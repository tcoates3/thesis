# The Question(s)

>Is there a way we can use the same software for most testbeams, while making the software equally useful for all people, easy to use and bind, and presentable?

>When the next-generation of lepton colliders are built, will their detectors be able to identify the presence of BSM physics in the Higgs sector by looking at ee->tth events?

# Master To Do List
1. **EUDAQ and DQM4HEP**
   - Write unit tests for the Kolmogorov and Chi2 tests
   - Rewrite the given nTuplizeMADA.cpp script so that it reads in data and the XML header into a new ROOT file
   - Start work on implementing the event streamer for the DREAM SiPM data
   - Assess the qtests by making plots of "goodness" against parameters to see how the "goodness" varies and whether it's useful
   - Continue writing the user's guide documentation
   - Incoporate Remi's changes into the qtest documentation (esp. once core docs pull request is closed)
3. **Physics Analysis**
   - Look through the data that Jenny has sent
   - Start writing some code to try to do the jet charge determination, both at MC-level and reconstruction-level
   - Test out the Valencia algorithm on some of the tth stuff (if possible with this large sample size?)
4. **Thesis Writing**
   - [...]
6. **Miscellany**
   - *Call* Oliver about DESY password reset
   - Finish report for annual review
