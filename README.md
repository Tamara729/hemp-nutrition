## Hemp Nutritional Metadata and Experiment Description
Nutrient management trials during summer 2020 at TREC, Homestead, FL.

`Essential Oils - N study`
Varieties Maverick and NBS were hand-sown on May 22nd, 2020.
Variety Wife was transplanted on May 26th, 2020.
Treatments evaluated were 0, 50, 100, 150, 200, and 250 lbs of N per acre.

`EO_UnitsID_2020.csv`: Description of experimental units of the first N study on essential oil varieties.
- `Unit`: Number identification of experimental units.
- `Variety`: Varieties evaluated in the trial.
- `Treatment`: Treatments evaluated in the trial.

`EO_UnitsID_2020_FI.csv`: Description of experimental units of the first N study on essential oil varieties.
- `Unit`: Number identification of experimental units.
- `Variety`: Varieties evaluated in the trial.
- `Treatment`: Treatments evaluated in the trial.
- `PlantingDate`: Date of planting of each unit/variety.
- Notes: Same data as in `EO_UnitsID_2020.csv` and used to determine anthesis over time.

`EO_PlantHeight_2020.csv`: Plant height of first N study on essential oil varieties.
- `Unit`: Number identification of experimental units.
- `Rep`: Plants within each experimental units.
- `Height_cm`: Stem length in centimeters from plant base to apex.

`EO_Flowering_2020.csv`: Flowering behavior data of first N study on essential oil varieties.
- `Unit`: Number identification of experimental units.
- `Rep`: Plants within each experimental units.
- `Induc_perc`: Percentage of flowering induction.
- `FemaleOpen_perc`: Percent of female plants with over half of flowers opened.

`EO_Harvest_2020.csv`: Harvest data of first N study on essential oil varieties.
- `Unit`: Number identification of experimental units.
- `Rep`: Plants within each experimental units.
- `FreshWeight_g`: Fresh aboveground biomass in grams.

`EO_HarvestIndex_2020.csv`: Data to calculate conversion factor for extrapolating total dry weights of the first N study on essential oil varieties.
- `Variety`: Varieties evaluated in the trial.
- `Treatment`: Treatments evaluated in the trial.
- `Rep`: Replications of treatments (4).
- `Unit`: Number identification of experimental units.
- `TotalFreshWeight_g`: Weight of sampled fresh aboveground biomass in grams from each experimental unit.
- `TotalDryWeight_g`: Weight of sampled dry aboveground biomass in grams from each experimental unit.
- `StemLeavesDryWeight_g`: Weight of sampled dry stems & leaves biomass in grams from each experimental unit.
- `FlowerDryWeight_g`: Weight of sampled dry floral biomass in grams from each experimental unit.

`EO_HarvestIndex_C_2020.csv`: Data to calculate conversion factor for extraolating total dry weights of the first N study on essential oil varieties.
- `Variety`: Varieties evaluated in the trial.
- `Treatment`: Treatments evaluated in the trial.
- `Rep`: Replications of treatments (4).
- `Unit`: Number identification of experimental units.
- `TotalFreshWeight_g`: Weight of sampled fresh aboveground biomass in grams from each experimental unit.
- `TotalDryWeight_g`: Weight of sampled dry aboveground biomass in grams from each experimental unit.
- `StemLeavesDryWeight_g`: Weight of sampled dry stems & leaves biomass in grams from each experimental unit.
- `FlowerDryWeight_g`: Weight of sampled dry floral biomass in grams from each experimental unit.
- Notes: Same data as in `EO_HarvestIndex_2020.csv` but used for creating the stacked bar graph.

`EO_NutrientAnalysis_2020.csv`: Foliar nutrient analyses results at harvest of the first N study on essential oil varieties.
- `Variety`: Varieties evaluated in the trial.
- `Treatment`: Treatments evaluated in the trial.
- `Rep`: Replications of sampling per treatment.
- `TKN_ppm`: Parts per milliom of Total Kjeldhal Nitrogen.
- `P_ppm`: Parts per million of Phosphorus.
- `K_ppm`:Parts per million of Potassium.
- `B_ppm`: Parts per million of Boron.
- `Cu_ppm`: Parts per million of Copper.
- `Mn_ppm`: Parts per million of Manganese.
- `Zn_ppm`: Parts per million of Zinc.

`EO_SoilNutrientAnalysisAfter_2020`: Soil nutrient analyses result after harvest of the first N study on essential oil varieties.
- `Variety`: Varieties evaluated in the trial.
- `Treatment`: Treatments evaluated in the trial.
- `MWHC_perc`: Percentage of Maximum Water Holding Capacity.
- `OM_perc`: Percentage of organic matter.
- `TKN_ppm`: Parts per milliom of Total Kjeldhal Nitrogen.
- `P_ppm`: Parts per million of Phosphorus.
- `NO3_ppm`: Parts per million of Nitrate.
- `NH4N_ppm`: Part per million of Ammonium nitrate

`EO_CannabinoidSample_2020.csv`: Data collected of samples submitted for cannabinoid quantification of the first N study on essential oil varieties.
- `Variety`: Varieties evaluated in the trial.
- `Treatment`: Treatments evaluated in the trial.
- `Rep`: Replications of treatments (4).
- `FlowerWeight_g`: Weight (in grams) of fresh floral material from three sampled 15-cm stem from the main stem (one per plant).
- `TotalFreshWeight_g`: Weight (in grams) of three fresh sampled 15-cm stem from the main stem (one per plant).
- `DryFlowerWeight_g`: Weight  (in grams) of dry floral material from three sampled 15-cm stem from the main stem (one per plant).
- `TotalDryWeight_g`: Weight  (in grams) of three dry sampled 15-cm stem from the main stem (one per plant).

`EO_CannabinoidProfile_2020.csv`: Cannabinoid quantification data from samples collected at harvest of the first N study on essential oil varieties.
- `Variety`: Varieties evaluated in the trial.
- `Treatment`: Treatments evaluated in the trial.
- `Rep`: Replications of treatments (4).
- `CBC`: Percentage of Cannabichromene.
- `CBCA`: Percentage of Cannabichromenic acid. 
- `CBD`: Percentage of Cannabidiol.
- `CBDA`: Percentage of Cannabidiolic acid.
` `CBDV`: Percentage of Cannabidivarin.
- `CBG`: Percentage of Cannabigerol.
- `CBGA`: Percentage of Cannabigerolic acid.
- `CBL`: Percentage of Cannabicyclol.
- `CBN`: Percentage of Cannabinol.
- `8_THC`: Percentage of Delta-8-Tetrahydrocannabinol.
- `9_THC`: Percentage of Delta-9-Tetrahydrocannabinol.
- `THCA`: Percentage of Tetrahydrocannabinolic acid.
- `THCV`: Percentage of Tetrahydrocannabivarin.
- `TotalPotentialTHC`: Percentage of Delta-9-Tetrahydrocannabinol plus Tetrahydrocannabinolic acid.
- `TotalPotentialCBD`: Percentage of Cannabidiol plus Cannabidiolic acid.
- `TotalPotentialCBC`: Percentage of Cannabichromene plus Cannabichromenic acid.
- `TotalPotentialCBG`: Percentage of Cannabigerol plus Cannabigerolic acid.

`EO_CannabinoidProfile2_2020.csv`: Cannabinoid quantification data from samples collected at harvest of the first N study on essential oil varieties.
- `Variety`: Varieties evaluated in the trial.
- `Treatment`: Treatments evaluated in the trial.
- `Rep`: Replications of treatments (4).
- `CBC`: Percentage of Cannabichromene.
- `CBCA`: Percentage of Cannabichromenic acid. 
- `CBD`: Percentage of Cannabidiol.
- `CBDA`: Percentage of Cannabidiolic acid.
` `CBDV`: Percentage of Cannabidivarin.
- `CBG`: Percentage of Cannabigerol.
- `CBGA`: Percentage of Cannabigerolic acid.
- `CBL`: Percentage of Cannabicyclol.
- `CBN`: Percentage of Cannabinol.
- `8_THC`: Percentage of Delta-8-Tetrahydrocannabinol.
- `9_THC`: Percentage of Delta-9-Tetrahydrocannabinol.
- `THCA`: Percentage of Tetrahydrocannabinolic acid.
- `THCV`: Percentage of Tetrahydrocannabivarin.
- `TotalPotentialTHC`: Percentage of Delta-9-Tetrahydrocannabinol plus Tetrahydrocannabinolic acid.
- `TotalPotentialCBD`: Percentage of Cannabidiol plus Cannabidiolic acid.
- `TotalPotentialCBC`: Percentage of Cannabichromene plus Cannabichromenic acid.
- `TotalPotentialCBG`: Percentage of Cannabigerol plus Cannabigerolic acid.
- Notes: Same data as in `EO_CannabinoidProfile_2020.csv` but with removed outliers (described below) due to a possible high-THC chemotype.
	- Variety NBS - Treatment 0 - Rep 1
	- Variety NBS - Treatment 50 - Rep 2 


`Indoor Supplemental Fertility study`
Varieties Cherry Blossom x T1 were transplanted and moved to the greenhouse on June 24th, 2020.
Treatments evaluated were control (unfertilized), low (100-17.5-50 ppm), medium (200-35-100 ppm), and high (300-52.5-150 ppm).

`UnitsID_Indoor_2020.csv`: Description of plants/experimental units of the indoor supplemental fertility study.
- `Unit`: Number identification of each plant/experimental unit.
- `Rep`: Replications of treatments (4).
- `Treatment`: Treatments evaluated in the trial.

`PlantHeight_StemDiameter_Indoor_2020.csv`: Plant height and stem diameter data of the indoor supplemental fertility study.
- `Unit`: Number identification of each plant/experimental unit.
- `Height_cm`: Stem length in centimeters from plant base to apex.
- `Diameter_cm`: Stem diameter in centimeter at 10 cm from plant base.
- `DAT`: Days after transplant.

`Flowering_Indoor_2020.csv`: Flowering behavior data of the indoor supplemental fertility study.
- `Unit`: Number identification of each plant/experimental units.
- `Induc_perc`: Percentage of flowering induction.
- `FemaleOpen_perc`: Percent of female plants with over half of flowers opened.

`Harvest_Indoor_2020.csv`: Harvest data of the indoor supplemental fertility study.
- `Unit`: Number identification of each plant/experimental unit.
- `TotalFreshWeight_g`: Weight (in grams) of total fresh aboveground biomass from each plant/experimental unit.
- `FlowerFreshWeight_g`: Weight (in grams) of total floral biomass from each plant/experimental unit.
- `TotalDryWeight_g_24`: Weight (in grams) of total dry aboveground biomass (after 24 hours) from each plant/experimental unit.
- `TotalDryWeight_g_48`: Weight (in grams) of total dry aboveground biomass (after 48 hours) from each plant/experimental unit.
- `FlowerDryWeight_g_48`: Weight (in grams) of total dry floral biomass (after 48 hours) from each plant/experimental unit.
- `DryStemsLeaves_g_48`: Weight (in grams) of total dry stems & leaves biomass (after 48 hours) from each plant/experimental unit.

`ScaffoldsInternodes_Indoor_2020.csv`: Scaffolds and internodes at harvest of the indoor supplemental fertility study.
- `Unit`: Number identification of each plant/experimental unit.
- `Scaffolds`: Total amount of scaffolds in each plant/experimental unit.
- `Sca_Internodes`: Total amount of internodes corrresponding to the amount of scaffolds in each plant/experimental unit.
- `NS_Inflo_Internodes`: Total amount of internodes in the inflorescence not sampled for cannabinoid quantification.
- `S_Inflo_Internodes`: Total amount of internodes in the inflorescence sampled for cannabinoid quantification.
- `Total_Inflo_Internodes`: Total amount of internodes in the inflorescence of each plant/experimental unit.
- `Total_Internodes`: Total amount of internodes in each plant/experimental unit.

`NutrientAnalysis_Indoor_2020.csv`: Foliar nutrient analyses results at harvest of the indoor supplemental fertility study.
- `Variety`: Variety evaluated in the trial (Cherry Blossom x T1).
- `Treatment`: Treatments evaluated in the trial.
- `TKN_ppm`: Parts per milliom of Total Kjeldhal Nitrogen.
- `P_ppm`: Parts per million of Phosphorus.
- `K_ppm`:Parts per million of Potassium.
- `B_ppm`: Parts per million of Boron.
- `Cu_ppm`: Parts per million of Copper.
- `Mn_ppm`: Parts per million of Manganese.
- `Zn_ppm`: Parts per million of Zinc.

`CannabinoidProfile_Indoor_2020.csv`: Cannabinoid quantification data from samples collected at harvest of the indoor supplemental fertility study.
- `Variety`: Variety evaluated in the trial (Cherry Blossom x T1).
- `Treatment`: Treatments evaluated in the trial.
- `UnitID`: Number identification of each plant/experimental unit.
- `CBC`: Percentage of Cannabichromene.
- `CBCA`: Percentage of Cannabichromenic acid. 
- `CBD`: Percentage of Cannabidiol.
- `CBDA`: Percentage of Cannabidiolic acid.
` `CBDV`: Percentage of Cannabidivarin.
- `CBG`: Percentage of Cannabigerol.
- `CBGA`: Percentage of Cannabigerolic acid.
- `CBL`: Percentage of Cannabicyclol.
- `CBN`: Percentage of Cannabinol.
- `8_THC`: Percentage of Delta-8-Tetrahydrocannabinol.
- `9_THC`: Percentage of Delta-9-Tetrahydrocannabinol.
- `THCA`: Percentage of Tetrahydrocannabinolic acid.
- `THCV`: Percentage of Tetrahydrocannabivarin.
- `TotalPotentialTHC`: Percentage of Delta-9-Tetrahydrocannabinol plus Tetrahydrocannabinolic acid.
- `TotalPotentialCBD`: Percentage of Cannabidiol plus Cannabidiolic acid.
- `TotalPotentialCBC`: Percentage of Cannabichromene plus Cannabichromenic acid.
- `TotalPotentialCBG`: Percentage of Cannabigerol plus Cannabigerolic acid.

`CannabinoidSample_Indoor_2020.csv`: Data collected of samples submitted for cannabinoid quantification of the indoor supplemental fertility study.
- `Unit`: Number identification of each plant/experimental unit.
- `Inflo_internodes`: Total amount of internodes in the inflorescence (15-cm stem of the mainstem) sampled from each plant/experimental unit.
- `TotalFreshWeight_g`: Weight (in grams) of fresh sampled 15-cm stem of the main stem.
- `FlowerFreshWeight_g`: Weight (in grams) of fresh floral material from sampled 15-cm stem of the main stem.
- `TotalDryWeight_g_24`: Weight (in grams) of dry sampled 15-cm stem of the main stem.

`CanopyArea_Indoor_2020`: Canopy area data of of the indoor supplemental fertility study.
- `Unit`: Number identification of each plant/experimental unit.
- `Rep`: Replications of treatments (4).
- `Treatment`: Treatments evaluated in the trial.
- `CanopyArea_cm2`: Canopy area of each plant/experimental unit in squared centimeters.


`Fiber & Grain - N study` - Data entry in process.
Varieties Carmagnola, Puma-3, and Han NE were hand sown on May 13th, 2020.
Treatments evaluated were 0, 50, 100, 150, 200, and 250 lbs of N per acre.

- `FG_UnitsID_2020.csv`
- `FG_PlantHeight_2020.csv`
- `FG_Flowering_2020.csv`
- `FG_Harvest_2020.csv`
- `FG_HarvestIndex_2020.csv`
- `FG_NutrientAnalysis_2020.csv`
- `FG_CannabinoidSample_2020.csv`
- `FG_CannabinoidProfile_2020.csv`
