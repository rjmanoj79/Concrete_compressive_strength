# Concrete_compressive_strength
Estimate Compressive Strength of Concrete
Civil engineering is a professional engineering discipline that deals with the design, construction, and maintenance of the physical and naturally built environment, including public works such as roads, bridges, canals, dams, airports, sewerage systems, pipelines, structural components of buildings, and railways.

Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients. Compressive strength or compression strength is the capacity of a material or structure to withstand loads tending to reduce the size, as opposed to which withstands loads tending to elongate. In other words, compressive strength resists being pushed together, whereas tensile strength resists tension (being pulled apart). In the study of strength of materials, tensile strength, compressive strength, and shear strength can be analyzed independently.

Objective
The concrete compressive strength is a highly nonlinear function of age and ingredients. These ingredients include cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, and fine aggregate. Your objective is to build a machine learning model that would help Civil Engineers to estimate the compressive strength of the concrete and they can further take a decision whether the concrete should be used in their current project or not.

To load the training data on your notebook, use the below command:

import pandas as pd

concrete_data  = pd.read_csv("https://raw.githubusercontent.com/dphi-official/Datasets/master/concrete_data/training_set_label.csv" )

Data Description
Cement (component 1)(kg in a m3 mixture): Cement   (component 1) -- Kilogram in a meter-cube mixture -- Input Variable
Blast Furnace Slag (component 2)(kg in a m3 mixture): Blast Furnace   Slag (component 2) -- kg in a m3 mixture -- Input Variable
Fly Ash (component 3)(kg in a m3 mixture): Fly Ash   (component 3) -- kg in a m3 mixture -- Input Variable
Water  (component 4)(kg in a m3   mixture): Water   (component 4) -- kg in a m3 mixture -- Input Variable
Superplasticizer (component 5)(kg in a m3 mixture): Superplasticizer   (component 5) -- kg in a m3 mixture -- Input Variable
Coarse Aggregate  (component 6)(kg   in a m3 mixture): Coarse   Aggregate (component 6) -- kg in a m3 mixture -- Input Variable
Fine Aggregate (component 7)(kg in a m3 mixture): Fine Aggregate   (component 7) -- kg in a m3 mixture -- Input Variable
Age (day): Age -- Day   (1-365) -- Input Variable
Concrete compressive strength(MPa, megapascals): Concrete   compressive strength -- MegaPascals -- Output Variable
Test Dataset
Load the test data (name it as test_data). You can load the data using the below command.

test_data = pd.read_csv('https://raw.githubusercontent.com/dphi-official/Datasets/master/concrete_data/testing_set_label.csv')

Here the target column is deliberately not there as you need to predict it.
