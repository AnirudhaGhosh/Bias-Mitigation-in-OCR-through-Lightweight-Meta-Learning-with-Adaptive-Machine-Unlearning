# Bias-Mitigation-in-OCR-through-Lightweight-Meta-Learning-with-Adaptive-Machine-Unlearning

This supplementary repository includes the Python implementation of our research paper. The primary folder includes "Code," which contains our work's code as  ".ipynb" files, and "Results," which consists of the findings of our investigation as  Excel files.

---------------------------------------------------------- CODES ---------------------------------------------------------

%%%%%%%%%%%%%%%%%   LWCNN-PN  %%%%%%%%%%%%%

The Training codes:

	"./code/training/meta_training_of _model_a/base-PN/Resnet_18 training.ipynb"  - contains the traning code for B-PN(Resnet-18)

	"./code/training/meta_training_of _model_a/base-PN/Desnet169_training.ipynb"  - contains the traning code for B-PN(Densnet-169)

	"./code/training/meta_training_of _model_a/LWCNN-PN/lwcnn_traning.ipynb" - contains the traning code for propose LWCNN-PN



The Testing codes:

	"./code/testing/Table:1   LWCNN-PN vs B-PN(resnet18 & densnet169) no Test Dataset-2: Assamese Script/Testing on Test Dataset:1(Assamese Script) (15 case)_ (for B-PN(resnet18&densNet169) and LWCNN-PN _togather.ipynb.ipynb" - contains the testing code of all models for Test Dataset:1(Assamese Script)

	"./code/testing/Table:2   LWCNN-PN vs B-PN(resnet18 & densnet169) no Test Dataset-2: Meetei-Mayek Script/Testing_on_Test_Dataset_2(Meetei-Mayek_Script)_(15_case)__(for_B_PN(resnet18&densNet169)_and_LWCNN_PN__togather_ipynb.ipynb" - contains the testing code of all models for Test_Dataset_2(Meetei-Mayek_Script)


%%%%%%%%%%%%%%%%%   AMUL (BMWA)  %%%%%%%%%%%%%

The Generation of model_b:

	"./code/training/Generation of model-b for AMUL/Amul_asamese_tamplate.ipynb" - contains the template of traning code for model_bs (1,5 and 10 shot) for Test Dataset:1(Assamese Script)

	"./code/training/Generation of model-b for AMUL/Amul_Meetei-Mayek_tamplate_shot.ipynb" - contains the template of traning code for model_bs (1,5 and 10 shot) for Test_Dataset_2(Meetei-Mayek_Script)



Evaluating / Testing of corresponding model_b and Evaluate the Impact of Propose AMUL (BMWA):



	"./code/testing/AMUL(BMWA)/TABLE:3 GENERATION/Applying_AMWL(BMWA)_on_LWCNN_(with Bise ratio)_on_Test_Dataset_1_Assemese_Script.ipynb" - contains the tamplate code for evaluation of corresponding model_b and the impact of corresponding bise_ratio with B-PN( Resnet and densnet) andLWCNN-PN on Test Dataset:1(Assamese Script)

	"./code/testing/AMUL(BMWA)/TABLE:4 GENERATION/Applying_AMWL(BMWA)_on_LWCNN_(with_different_fc_ratio_values)_on_Test_Dataset_2_Meetei-Mayek_Script.ipynb" - contains the code for evaluation of corresponding model_b and the impact of different FC_ratios with LWCNN-PN on Test_Dataset_2(Meetei-Mayek_Script)



