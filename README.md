# Entity-Relationship-for-Substance-use
Following files performs :
*  BratReader_and_analysis.ipynb: Processing raw data and store into a json format. Perform exploratory analysis and identify cardinal relations.
*  Datasets_generation: Performs train and test split on datasets and stored as trainset.json and testset.json in data directory.
*  FlatNERModel_v1.ipynb: Performs parallel task learnining for entity(with dynamic labelling) and role categories and evaluate them.
*  FlatNERModel_v2.ipynb: Performs parallel task learnining for entity(removed overlapping entities) and role categories and evaluate them.
*  Indp_NERmodel.ipynb: Trains independtly Entity and role models .
*  Inf_FlatNERRelation.ipynb: Extracts entity and role model outputs , forms span pairs and predicts relations. Evaluating relations by mapping span pairs to relation labels.
*  NER Analysis.ipynb: Performs Analysis for entity ,role model outputs.
*  Entity_Relationship prediction.ipynb: Whole system of given a text identifies entities, roles and relations between them.
*  NestedNER.ipynb: Performs training for substance use entities handling overlap.
*  Relation_Classifier.ipynb: Constructs relation training and test data and performs relation classification training.
*  Relation-FlatNER.ipynb: Performs parallel task learning for entities, roles and relations. Relations trained with only spans of entities and roles.

#Run : Change the project directory in each script and some inputs needed are specified in run instructions of each notebook.
