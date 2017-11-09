# The Question(s)

>Is there a way we can use the same software for most testbeams, while making the software equally useful for all people, easy to use and bind, and presentable?

>When the next-generation of lepton colliders are built, will their detectors be able to identify the presence of BSM physics in the Higgs sector by looking at ee->tth events?

# Master To Do List
1. **EUDAQ and DQM4HEP**
   - Move the Mean90 and RMS90 algorithms into a separate file (e.g. AnalysisHelper.cc) with it's includes and plugins, so that the methods can be accessed outside of the individual qtest file
   - Make plots of a qtest's "goodness" against the qtest parameters, to see how the "goodness" varies and whether it's a useful statistic
   - Do some more stuff on the canRun() function in the qtests, so that it is more useful (e.g. make it check whether the histogram is empty or not)
   - Continue writing the user's guide documentation
   - Implement more quality tests (especially Kolmogorov-Smirnov now that reference histograms are possible)
   - Try to implement fully-parameterised functionality for the mean/RMS tests
   - Somehow get access to the DESY dCache so I can download more testbeam data later on, especially for thesis work
3. **Physics Analysis, Processing**
   - Finish processing all runs through the analysis
3. **Physics Analysis, Other**
   - Read papers about previous analyses of tth stuff
   - Try to find more information on how to quantify CP violation in tth events
4. **Papers and Literature**
   - Read papers about ILC/CLIC and tth analysis
   - Write conference proceedings for ACAT (11th Nov)
5. **Miscellany**
   - Test out the Valencia algorithm on some of the tth stuff (if possible with this large sample size?)

- - -

To rebase/merge with git:
`git checkout origin master`
`git pull`
`git checkout fork qtestworking`
`git rebase`
