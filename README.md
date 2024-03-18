# Children-Bone-Marrow-Transplant


About the dataset The dataset describes pediatric patients with several hematologic diseases: malignant disorders (i.a. patients with acute lymphoblastic leukemia, with acute myelogenous leukemia, with chronic myelogenous leukemia, with myelodysplastic syndrome) and nonmalignant cases (i.a. patients with severe aplastic anemia, with Fanconi anemia, with X-linked adrenoleukodystrophy). All patients were subject to the unmanipulated allogeneic unrelated donor hematopoietic stem cell transplantation. The motivation of this study was to identify the most important factors influencing the success or failure of the transplantation procedure. In particular, verification of the research hypothesis that increased dosage of CD34+ cells / kg extends overall survival time without simultaneous occurrence of undesirable events affecting patients' quality of life.

Dataset information The set contains 187 examples characterized by 37 attributes. The meaning of the following features is as follows: -Recipientgender - Male - 1, Female - 0,

Stemcellsource - Source of hematopoietic stem cells (Peripheral blood - 1, Bone marrow - 0),
Donorage - Age of the donor at the time of hematopoietic stem cells apheresis
Donorage35 - Donor age <35 - 0, Donor age >=35 - 1
IIIV - Development of acute graft versus host disease stage II or III or IV (Yes - 1, No - 0),
Gendermatch - Compatibility of the donor and recipient according to their gender (Female to Male - 1, Other - 0),
DonorABO - ABO blood group of the donor of hematopoietic stem cells (0 - 0, 1, A, B=-1, AB=2),
RecipientABO - ABO blood group of the recipient of hematopoietic stem cells (0 - 0, 1, A, B=-1, AB=2),
RecipientRh - Presence of the Rh factor on recipient�s red blood cells ('+' - 1, '-' - 0),
ABOMatch - Compatibility of the donor and the recipient of hematopoietic stem cells according to ABO blood group (matched - 1, mismatched - 1)
CMVstatus - Serological compatibility of the donor and the recipient of hematopoietic stem cells according to cytomegalovirus infection prior to transplantation (the higher the value the lower the compatibility)
RecipientCMV - Presence of cytomegalovirus infection in the donor of hematopoietic stem cells prior to transplantation (presence - 1, absence - 0)
Disease - Type of disease (ALL,AML,chronic,nonmalignant,lymphoma)
Riskgroup - High risk - 1, Low risk - 0,
Txpostrelapse - The second bone marrow transplantation after relapse (No - 0; Yes - 1),
Diseasegroup - Type of disease (malignant - 1, nonmalignant - 0),
HLAmatch - Compatibility of antigens of the main histocompatibility complex of the donor and the recipient of hematopoietic stem cell according to ALL international BFM SCT 2008 criteria (10/10 - 0, 9/10 - 1, 8/10 - 2, 7/10 - 3 (allele/antigens)),
HLAmismatch - HLA matched - 0, HL mismatched - 1,
Antigen - In how many anigens there is difference beetwen the donor nad the recipient (-1 - no differences, 0 - one difference,1 (2) two (three) diffences)
Allel - In how many allele there is difference beetwen the donor nad the recipient {-1 no differences,0 - one difference, 1 (2) (3) - two, (tree, four) differences)
HLAgrI - The differecne type beetwien the donor and the recipient (HLA mateched - 0,the difference is in only one antigen - 1, the difference is only in one allel - 2, the difference is only in DRB1 cell - 3, two differences (two allele or two antignes) - 4, two differences (two allele or two antignes) - 5),
Recipientage - Age of the recipient of hematopoietic stem cells at the time of transplantation,
Recipientage10 - Recipient age <10 - 0, Recipient age>=10 - 1,
Recipientageint - Recipient age in (0,5] - 0, (5, 10] - 1, (10, 20] - 2,
Relapse - Reoccurrence of the disease (No - 0, Yes - 1),
aGvHDIIIIV - Development of acute graft versus host disease stage III or IV (Yes - 0, No - 1)
extcGvHD - Development of extensive chronic graft versus host disease (Yes - 0, No - 1)
CD34kgx10d6 - CD34+ cell dose per kg of recipient body weight (10^6/kg)
CD3dCD34 - CD3+ cell to CD34+ cell ratio
CD3dkgx10d8 - CD3+ cell dose per kg of recipient body weight (10^8/kg)
Rbodymass - Body mass of the recipient of hematopoietic stem cells at the time of transplantation,
ANCrecovery - Time to neutrophils recovery defined as neutrophils count >0.5 x 10^9/L
PLTrecovery - Time to platelet recovery defined as platelet count >50000/mm3,
time_to_aGvHD_III_IV - Time to development of acute graft versus host disease stage III or IV
survival_time numeric
survival_status
Relation -Recipientgender {1,0} -Stemcellsource {1,0} -Donorage numeric -Donorage35 {0,1} -IIIV {1,0} -Gendermatch {0,1} -DonorABO {1,-1,2,0} -RecipientABO {1,-1,2,0} -RecipientRh {1,0} -ABOmatch {0,1} -CMVstatus {3,2,1,0} -DonorCMV {1,0} -RecipientCMV {1,0} -Disease {ALL,AML,chronic,nonmalignant,lymphoma} -Riskgroup {1,0} -Txpostrelapse {0,1} -Diseasegroup {1,0} -HLAmatch {0,1,3,2} -HLAmismatch {0,1} -Antigen {-1,1,0,2} -Alel {-1,0,2,1,3} -HLAgrI {0,1,7,3,2,4,5} -Recipientage numeric -Recipientage10 {0,1} -Recipientageint {0,1,2} -Relapse {0,1} -aGvHDIIIIV {0,1} -extcGvHD {1,0} -CD34kgx10d6 numeric -CD3dCD34 numeric -CD3dkgx10d8 numeric -Rbodymass numeric -ANCrecovery numeric -PLTrecovery numeric -time_to_aGvHD_III_IV numeric -survival_time numeric -survival_status numeric

Source Provide the names, email addresses, institutions, and other contact information of the donors and creators of the data set. Marek Sikora^{1,2} (marek.sikora '@' polsl.pl), Lukasz Wrobel^{1} (lukasz.wrobel '@' polsl.pl),
(1) Institute of Computer Science, Silesian University of Technology, 44-100 Gliwice, Poland (2) Institute of Innovative Technologies EMAG, 40-189 Katowice, Poland
