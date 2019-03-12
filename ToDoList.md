# The Question(s)

>Is there a way we can use the same software for most testbeams, while making the software equally useful for all people, easy to use and bind, and presentable?

>When the next-generation of lepton colliders are built, will their detectors be able to identify the presence of BSM physics in the Higgs sector by looking at ee->tth events?

# Master To Do List
1. **DQM4hep**
   - Assess the qtests by making plots of "goodness" against parameters to see how the "goodness" varies and whether it's useful
   - Create an example repo to help people write custom plugins and modules (include CMake files, highly-commented file readers, event streamers, and analysis modules)
2. **Testbeam Analysis**
   - Make energy-to-ADC calibration, using the assumption that the calorimeter response is linear
   - Perform tower calibration, using the calibration electron runs
3. **Physics Analysis**
   - Start writing some code to try to do the jet charge determination, both at MC-level and reconstruction-level
   - Test out the Valencia algorithm on some of the tth stuff (if possible with this large sample size?)
4. **Thesis Writing**
   - [...]
