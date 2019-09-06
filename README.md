# m2i-jour2
WebApp.Fix (Cbr.Net.Fix 18.0.0.975 | Cbp.Net.Fix 12.9.54.508 | Cbr.Clienteling.Net 18.0.0.823)
WorkerProcess.Multi-Tenant.Fix (Cbr.Delphi.Fix 18.0.0.1547 | Cbr.Net.Fix 18.0.0.975 | Cbp.Delphi.Fix 12.9.54.432 | Cbp.Net.Fix 12.9.54.508)
WebApp.Current (Cbr.Net.Current 18.0.0.1487 | Cbp.Net.Current 12.9.81.726 | Cbr.Clienteling.Net 18.0.0.823)
WorkerProcess.Multi-Tenant.Current (Cbr.Delphi.Current 18.0.0.2339 | Cbr.Net.Current 18.0.0.1487 | Cbp.Delphi.Current 12.9.81.616 | Cbp.Net.Current 12.9.81.726]CPTXFiles.Fix)

Code Coverage des derniers tests effectués

Légende du rapport disponible ici
With Fix Y2 Core 
 
01:56
PROD..UGIN 
Thu 10:24
PROD..UGIN 
Thu 02:39
PROD..UGIN 
Wed 12:31
PROD..UGIN 
Wed 11:48
PROD..UGIN 
WebServices
+9
22
1,779

(42)
06:25
+1
13
1,779

(42)
06:27

12
1,779

(42)
06:24

12
1,779

(42)
06:27

12
1,779

(42)
06:30
WebServices_Tech

0
5


00:05

0
5


00:05

0
5


00:05

0
5


00:05

0
5


00:05
TOTAL
22/1,784 
06:30
13/1,784 
06:33
12/1,784 
06:30
12/1,784 
06:32
12/1,784 
06:36

Code Coverage des derniers tests effectués

Légende du rapport disponible ici
With Current Y2 Core 
 
02:15
PROD..UGIN 
Thu 10:43
PROD..UGIN 
Thu 02:58
PROD..UGIN 
Wed 12:52
PROD..UGIN 
Wed 12:06
PROD..UGIN 
WebServices
+9
12
1,779

(42)
06:39
+1
3
1,779

(42)
06:42

2
1,779

(42)
06:45

2
1,779

(42)
06:49

2
1,779

(42)
06:49
WebServices_Tech

0
5


00:05

0
5


00:05

0
5


00:05

0
5


00:05

0
5


00:05
TOTAL
12/1,784 
06:44
3/1,784 
06:47
2/1,784 
06:50
2/1,784 
06:55
2/1,784 
06:54

With Fix Y2 Core MSSQL - Tests newly broken (9) 
WebServices (9) 
Mobility_GetSaleDocumentTypeParameters (9) 
Test_16 [ADE] - !! NEW !! - NC - complèment par établissement [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_17 [ADE] - !! NEW !! - NC - complément Etablissement - Utilisation des tables libres FALSE (GPC_AFFPIECETABLE) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_18 [ADE] - !! NEW !! - NC - complément Etablissement - Mise à jour de la valeur par défaut (GPC_CODPIECEDEF1) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_19 [ADE] - !! NEW !! - NC - complément Etablissement - Champ obligatoire pour une table libre (GPC_CODEPIECEOBL1) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_20 [ADE] - !! NEW !! - NC - complément Etablissement - Champ Initialiser avec les valeurs du tiers (GPC_PIECTABPRERENS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_21 [ADE] - !! NEW !! - NC - complément Etablissement - Champ pas de saisie si tout est renseigné (GPC_PIECTABSICOMPL) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_22 [ADE] - !! NEW !! - NC - complément Etablissement - Champ Proposer les tables libres du tiers (GPC_PIECTABETTIERS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_23 [ADE] - !! NEW !! - NC - complément Etablissement - MAJ des tables libres du tiers (GPC_MAJTABLIBTIERS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_24 [ADE] - !! NEW !! - NC - complément Etablissement - MAJ des tables libres du tiers (GPC_MAJTABLIBTIERS) mais pas de table [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
With Fix Y2 Core MSSQL - All Broken Tests (22) 
WebServices (22) 
Mobility_GetParameters (1) 
Test_06 [ADE] - NC - retrait des commandes en point relais actif (société) [Assert.IsTrue failed. Modification - expected (false), result (true). Voir le chemin (/GetMobilityParametersResponse[1]/GetMobilityParametersResult[1]/AllowOrderPickupLocation)]
Mobility_GetSaleDocumentTypeParameters (9) 
Test_16 [ADE] - !! NEW !! - NC - complèment par établissement [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_17 [ADE] - !! NEW !! - NC - complément Etablissement - Utilisation des tables libres FALSE (GPC_AFFPIECETABLE) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_18 [ADE] - !! NEW !! - NC - complément Etablissement - Mise à jour de la valeur par défaut (GPC_CODPIECEDEF1) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_19 [ADE] - !! NEW !! - NC - complément Etablissement - Champ obligatoire pour une table libre (GPC_CODEPIECEOBL1) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_20 [ADE] - !! NEW !! - NC - complément Etablissement - Champ Initialiser avec les valeurs du tiers (GPC_PIECTABPRERENS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_21 [ADE] - !! NEW !! - NC - complément Etablissement - Champ pas de saisie si tout est renseigné (GPC_PIECTABSICOMPL) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_22 [ADE] - !! NEW !! - NC - complément Etablissement - Champ Proposer les tables libres du tiers (GPC_PIECTABETTIERS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_23 [ADE] - !! NEW !! - NC - complément Etablissement - MAJ des tables libres du tiers (GPC_MAJTABLIBTIERS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_24 [ADE] - !! NEW !! - NC - complément Etablissement - MAJ des tables libres du tiers (GPC_MAJTABLIBTIERS) mais pas de table [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
SaleAndSellers_CreateReceipt (11) 
Test_21 [LBO] - NC - Fidélité - remise ticket en montant [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_22 [LBO] - NC - Fidélité - remise ligne en montant [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_23 [LBO] - NC - FFO - fidélité - bon d'achat fidélité préenregistré de type montant [Assert.AreEqual failed. Expected:<2>. Actual:<0>. check sale lines have been removed]
Test_24 [LBO] - NC - Fidélité - remise ticket en remise [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_25 [LBO] - NC - Fidélité - remise ligne en remise [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
[...output truncated - displaying 15 items out of 22]
With Current Y2 Core MSSQL - Tests newly broken (9) 
WebServices (9) 
Mobility_GetSaleDocumentTypeParameters (9) 
Test_16 [ADE] - !! NEW !! - NC - complèment par établissement [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_17 [ADE] - !! NEW !! - NC - complément Etablissement - Utilisation des tables libres FALSE (GPC_AFFPIECETABLE) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_18 [ADE] - !! NEW !! - NC - complément Etablissement - Mise à jour de la valeur par défaut (GPC_CODPIECEDEF1) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_19 [ADE] - !! NEW !! - NC - complément Etablissement - Champ obligatoire pour une table libre (GPC_CODEPIECEOBL1) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_20 [ADE] - !! NEW !! - NC - complément Etablissement - Champ Initialiser avec les valeurs du tiers (GPC_PIECTABPRERENS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_21 [ADE] - !! NEW !! - NC - complément Etablissement - Champ pas de saisie si tout est renseigné (GPC_PIECTABSICOMPL) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_22 [ADE] - !! NEW !! - NC - complément Etablissement - Champ Proposer les tables libres du tiers (GPC_PIECTABETTIERS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_23 [ADE] - !! NEW !! - NC - complément Etablissement - MAJ des tables libres du tiers (GPC_MAJTABLIBTIERS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_24 [ADE] - !! NEW !! - NC - complément Etablissement - MAJ des tables libres du tiers (GPC_MAJTABLIBTIERS) mais pas de table [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
With Current Y2 Core MSSQL - All Broken Tests (12) 
WebServices (12) 
Mobility_GetParameters (1) 
Test_06 [ADE] - NC - retrait des commandes en point relais actif (société) [Assert.IsTrue failed. Modification - expected (false), result (true). Voir le chemin (/GetMobilityParametersResponse[1]/GetMobilityParametersResult[1]/AllowOrderPickupLocation)]
Mobility_GetSaleDocumentTypeParameters (9) 
Test_16 [ADE] - !! NEW !! - NC - complèment par établissement [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_17 [ADE] - !! NEW !! - NC - complément Etablissement - Utilisation des tables libres FALSE (GPC_AFFPIECETABLE) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_18 [ADE] - !! NEW !! - NC - complément Etablissement - Mise à jour de la valeur par défaut (GPC_CODPIECEDEF1) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_19 [ADE] - !! NEW !! - NC - complément Etablissement - Champ obligatoire pour une table libre (GPC_CODEPIECEOBL1) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_20 [ADE] - !! NEW !! - NC - complément Etablissement - Champ Initialiser avec les valeurs du tiers (GPC_PIECTABPRERENS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_21 [ADE] - !! NEW !! - NC - complément Etablissement - Champ pas de saisie si tout est renseigné (GPC_PIECTABSICOMPL) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_22 [ADE] - !! NEW !! - NC - complément Etablissement - Champ Proposer les tables libres du tiers (GPC_PIECTABETTIERS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_23 [ADE] - !! NEW !! - NC - complément Etablissement - MAJ des tables libres du tiers (GPC_MAJTABLIBTIERS) [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
Test_24 [ADE] - !! NEW !! - NC - complément Etablissement - MAJ des tables libres du tiers (GPC_MAJTABLIBTIERS) mais pas de table [Assert.IsTrue failed. Elément manquant. Voir le chemin (/GetSaleDocumentTypeParametersResponse[1]/GetSaleDocumentTypeParametersResult[1]/SaleDocumentTypeParameters[1]/SaleDocumentTypeParameter[1]/IsClosedItemAllowed)]
SaleAndSellers_CreateDocument (1) 
Test_04 [LBO] - NC - Creation d'une commande avec BR - un champ requis ZIP vide mais BookedInStore [Assert.AreEqual failed. Expected:<1>. Actual:<0>. Control XML response]
SaleAndSellers_GetVouchers (1) 
Test_04 [CMA] - NC - Ticket avec BA type FBA [Assert.IsTrue failed. Modification - expected (30), result (10.22). Voir le chemin (/GetVouchersResponse[1]/GetVouchersResult[1]/Vouchers[1]/Voucher[1]/AvailableAmount)]
Tests not validated (yet!) (42) 
WebServices (42) 
Common_CommonSearchByReference (1) 
11 [ADE] [TFS.0] - NC - Recherche client - carte fermée - (normal test case)
Common_GetRegionsByCountryId (1) 
04 [JPE] [TFS.0] - NC - pays ne gérant pas les régions - pas de réponse - (limited test case)
Crm_CreateLoyaltyCard (2) 
09 [ADE] [TFS.0] - EC - numéro de carte non renseigné et attribution manuelle - ( )
13 [ADE] [TFS.0] - EC - création attribution manuelle et numéro vide - ()
Crm_GetClassifications (1) 
04 [SPA] [TFS.0] - NC - 2 classifications - test paramètre SO_MBOMULTICLASSIF (false) - ()
Crm_GetCollectingDataTypes (1) 
03 [CCH] [TFS.9999] - NC - traduction - messages traduits - (A corriger)
Crm_GetCustomerStatistics (3) 
02 [ADE] [TFS.579602] - NC - pas de ventes sur 3 ans (SC000637) - ()
03 [ADE] [TFS.579602] - NC - pas de ventes sur 3 ans/store Id renseigné (SC000637 mag 101) - ()
11 [LBO] [TFS.0] - NC - Test avec le paramètre AllReceipts True - Max 100 - (Add MaxReceipts param)
Crm_GetDuplicateCustomers (1) 
11 [ADE] [TFS.0] - NC - Recherche doublon sur 1 téléphone (en base avec espaces) - 1 réponse - ()
Crm_InsertCollectingData (2) 
19 [CCH] [TFS.0] - EC - pas de client renseigné (optionnel pour la collecte) - (LBO 2014/10/10 - Desactivé pour CBP en attendant correctif oracle)
21 [CCH] [TFS.0] - NC - client vide (optionnel pour la collecte) - (LBO 2014/10/10 - Desactivé pour CBP en attendant correctif oracle)
Crm_SearchCustomers (1) 
17 [ADE] [TFS.342460] - NC - recherche retournant plusieurs réponses sur champs différents (MAR) - ()
Image_GetClassificationNodeImage (3) 
12 [JPE] [TFS.0] - Size - valeur superieure au maxi - 10001 - ()
13 [JPE] [TFS.0] - Size egale a 10000 - ()
14 [JPE] [TFS.0] - Size intermediaire - 200 - ()
Image_GetCustomerImage (2) 
09 [JPE] [TFS.0] - LC - size égale à 10000 - ()
10 [JPE] [TFS.0] - NC - size intermédiaire - 200 - ()
Image_GetItemImage (5) 
05 [JPE] [TFS.0] - NC - index inexistant - valeur 99 - pas de réponse - ()
06 [JPE] [TFS.0] - EC - index inexistant - non numérique - ()
10 [JPE] [TFS.0] - NC - size correcte - ()
17 [SPA] [TFS.0] - NC - size égale à 1 - ()
18 [SPA] [TFS.0] - NC - size égale à 10000 - ()
Image_GetItemListImage (2) 
13 [JPE] [TFS.0] - Size egale a 10000 - ()
14 [JPE] [TFS.0] - Size intermediaire - 200 - ()
Item_GetClassification (1) 
02 [ADE] [TFS.307783] - Classification non renseignée - (Voir si possible de renvoyer une erreur)
ItemSearch_GetItems (4) 
17 [CCH] [TFS.0] - NC - pagination - page 1 - (Cas de test non pertinent et trop sensible aux perturbations des données en base)
25 [CCH] [TFS.0] - LC - classification node - empty value - (Cas de test non pertinent et trop sensible aux perturbations des données en base)
30 [CCH] [TFS.0] - LC - item list - empty value - (SPAT 2015/04/20 - ORACLE ne sait pas faire la différence entre une chaîne vide et une chaîne nulle, la recherche sur liste d'article null retourne les articles qui ne sont pas rattachés. Comme la règle est la base la plus restrictive gagne, c'est la règle ORACLE qui s'impose)
36 [CCH] [TFS.0] - LC - pas de critère de recherche - pas de code barres - (Cas de test non pertinent et trop sensible aux perturbations des données en base)
ItemSearch_GetItemsFacets (3) 
01 [TFS.0] - NC - recherche sur classification et texte (l) - (SPAT 2014/11/28 - Création du plan de test)
09 [TFS.0] - NC - recherche donnant tous les types de facettes - (JPE 2015/01/08 - test calcul facette avec recherche par facette)
24 [TFS.0] - NC - paramétrage uniquement classif - (SPAT 2014/11/28 - Création du plan de test)
ItemSearch_Keywords (1) 
01 [ADE] [TFS.342460] - NC - recherche avec un mot clef - ()
Mobility_UpdateDeviceCashRegister (1) 
02 [ADE] [TFS.309357] - LC - caisse inexistante - - (contrôle à rajouter)
SaleAndSellers_CreateReceipt (3) 
15 [ADE] [TFS.0] - NC - ticket avec CC de type FID - coefficient - ()
16 [ADE] [TFS.0] - NC - ticket avec CC de type FID - points - ()
17 [ADE] [TFS.0] - NC - TFS.918627 vérif des ajouts d'infos bancaires - ()
SaleAndSellers_CreateReceipt_IJSQL (1) 
14 [OCH] [TFS.1026072] - EC - SQL Injection - Trying to alter OriginReturnLine - (TFS.668908 - SQL Injections)
SaleAndSellers_GetDocumentDetailByKey (2) 
02 [ADE] [TFS.0] - NC - ticket + vendeur + ref externe - ()
12 [ADE] [TFS.0] - NC - SaleDocumentKey correct - company - ()
SaleAndSellers_GetPendingTicket (1) 
10 [OCH] [TFS.734847] - EC - SQL Injection - Trying to alter StoreId - (TFS.668908 - SQL Injections)
Broken Tests - in With Fix Y2 Core MSSQL, not in With Current Y2 Core MSSQL (11) 
WebServices (11) 
SaleAndSellers_CreateReceipt (11) 
Test_21 [LBO] - NC - Fidélité - remise ticket en montant [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_22 [LBO] - NC - Fidélité - remise ligne en montant [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_23 [LBO] - NC - FFO - fidélité - bon d'achat fidélité préenregistré de type montant [Assert.AreEqual failed. Expected:<2>. Actual:<0>. check sale lines have been removed]
Test_24 [LBO] - NC - Fidélité - remise ticket en remise [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_25 [LBO] - NC - Fidélité - remise ligne en remise [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_26 [LBO] - NC - Fidélité - remise cadeau [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_27 [LBO] - NC - Fidélité - bon d'achat fidélité de type mode de paiement [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale paiment has been removed]
Test_28 [LBO] - NC - Fidélité - bon d'achat fidélité de type remise [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale paiment has been removed]
Test_29 [LBO] - NC - FFO - fidélité - bon d'achat fidélité préenregistré de type remise [Assert.AreEqual failed. Expected:<2>. Actual:<0>. check sale lines have been removed]
Test_30 [ADE] - NC - ticket avec CC avec mot clef et iscanned à false [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check keywords]
Test_31 [ADE] - NC - ticket avec CC avec mot clef et iscanned à true [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check keywords]
Broken Tests - in With Current Y2 Core MSSQL, not in With Fix Y2 Core MSSQL (1) 
WebServices (1) 
SaleAndSellers_CreateDocument (1) 
Test_04 [LBO] - NC - Creation d'une commande avec BR - un champ requis ZIP vide mais BookedInStore [Assert.AreEqual failed. Expected:<1>. Actual:<0>. Control XML response]
Broken Tests - in With Current Y2 Core MSSQL, not in With Fix Y2 Core MSSQL (1) 
WebServices (1) 
SaleAndSellers_CreateDocument (1) 
Test_04 [LBO] - NC - Creation d'une commande avec BR - un champ requis ZIP vide mais BookedInStore [Assert.AreEqual failed. Expected:<1>. Actual:<0>. Control XML response]
Broken Tests - in With Fix Y2 Core MSSQL, not in With Current Y2 Core MSSQL (11) 
WebServices (11) 
SaleAndSellers_CreateReceipt (11) 
Test_21 [LBO] - NC - Fidélité - remise ticket en montant [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_22 [LBO] - NC - Fidélité - remise ligne en montant [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_23 [LBO] - NC - FFO - fidélité - bon d'achat fidélité préenregistré de type montant [Assert.AreEqual failed. Expected:<2>. Actual:<0>. check sale lines have been removed]
Test_24 [LBO] - NC - Fidélité - remise ticket en remise [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_25 [LBO] - NC - Fidélité - remise ligne en remise [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_26 [LBO] - NC - Fidélité - remise cadeau [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale lines have been removed]
Test_27 [LBO] - NC - Fidélité - bon d'achat fidélité de type mode de paiement [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale paiment has been removed]
Test_28 [LBO] - NC - Fidélité - bon d'achat fidélité de type remise [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check sale paiment has been removed]
Test_29 [LBO] - NC - FFO - fidélité - bon d'achat fidélité préenregistré de type remise [Assert.AreEqual failed. Expected:<2>. Actual:<0>. check sale lines have been removed]
Test_30 [ADE] - NC - ticket avec CC avec mot clef et iscanned à false [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check keywords]
Test_31 [ADE] - NC - ticket avec CC avec mot clef et iscanned à true [Assert.AreEqual failed. Expected:<1>. Actual:<0>. check keywords]
With Fix Y2 Core MSSQL - Tests in doubt (1) 
WebServices (1) 
Common_CommonSearchByReference (1) 
Test_01 [LBO] - NC - Recherche article [root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Framework.Web.Http.HubApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Erp.Data.Model.SchemaServiceFactory, Cegid.Erp.Data, Version=12.9.54.508, Culture=neutral, PublicKeyToken=1c8903203f6251e2' (Cegid.Erp.Data.Model.ISchemaService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Erp.Data.Model.FastSchemaServiceFactory, Cegid.Erp.Data, Version=12.9.54.508, Culture=neutral, PublicKeyToken=1c8903203f6251e2' (Cegid.Erp.Data.Model.ISchemaService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Clienteling.Services.Address.AddressNotificationServiceFactory, Cegid.Retail.Clienteling.Services, Version=18.0.0.823, Culture=neutral, PublicKeyToken=23983c4f573c2fb1' (Cegid.Retail.ServiceContracts.Address.IAddressService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Common.TraceHubForwardServiceFactory, Cegid.Retail.Services, Version=18.0.0.975, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.Services.Common.ITraceHubForwardService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Common.MsmqInterOpCallerServiceFactory, Cegid.Retail.Services, Version=18.0.0.975, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.Services.Common.IInterOpCaller) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Common.MsmqMultiTenantInterOpCallerServiceFactory, Cegid.Retail.Services, Version=18.0.0.975, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.Services.Common.IInterOpCaller) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Common.WorkerProcess.WorkerProcessServiceFactory, Cegid.Retail.Services, Version=18.0.0.975, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.Services.Common.WorkerProcess.IWorkerProcessService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Common.WorkerProcess.WorkerProcessMultiTenantServiceFactory, Cegid.Retail.Services, Version=18.0.0.975, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.Services.Common.WorkerProcess.IWorkerProcessService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Address.AddressServiceFactory, Cegid.Retail.Services, Version=18.0.0.975, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.ServiceContracts.Address.IAddressService) was not registered, another implementation already exists.]
With Current Y2 Core MSSQL - Tests in doubt (1) 
WebServices (1) 
Common_CommonSearchByReference (1) 
Test_01 [LBO] - NC - Recherche article [root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Framework.Web.Http.HubApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | CallingFlow | Method 'Services discovery' - Unable to load a type : Cegid.Erp.Web.Http.ErpApiController]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Erp.Data.Model.SchemaServiceFactory, Cegid.Erp.Data, Version=12.9.81.726, Culture=neutral, PublicKeyToken=1c8903203f6251e2' (Cegid.Erp.Data.Model.ISchemaService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Erp.Data.Model.FastSchemaServiceFactory, Cegid.Erp.Data, Version=12.9.81.726, Culture=neutral, PublicKeyToken=1c8903203f6251e2' (Cegid.Erp.Data.Model.ISchemaService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Clienteling.Services.Address.AddressNotificationServiceFactory, Cegid.Retail.Clienteling.Services, Version=18.0.0.823, Culture=neutral, PublicKeyToken=23983c4f573c2fb1' (Cegid.Retail.ServiceContracts.Address.IAddressService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Common.TraceHubForwardServiceFactory, Cegid.Retail.Services, Version=18.0.0.1487, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.Services.Common.ITraceHubForwardService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Common.MsmqInterOpCallerServiceFactory, Cegid.Retail.Services, Version=18.0.0.1487, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.Services.Common.IInterOpCaller) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Common.MsmqMultiTenantInterOpCallerServiceFactory, Cegid.Retail.Services, Version=18.0.0.1487, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.Services.Common.IInterOpCaller) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Common.WorkerProcess.WorkerProcessServiceFactory, Cegid.Retail.Services, Version=18.0.0.1487, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.Services.Common.WorkerProcess.IWorkerProcessService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Common.WorkerProcess.WorkerProcessMultiTenantServiceFactory, Cegid.Retail.Services, Version=18.0.0.1487, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.Services.Common.WorkerProcess.IWorkerProcessService) was not registered, another implementation already exists.]
[root][Warning][: 0 : Cegid.Framework.Services | ApplicationFlow | Function 'Hub services configuration' - Service implementation 'Cegid.Retail.Services.Address.AddressServiceFactory, Cegid.Retail.Services, Version=18.0.0.1487, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32' (Cegid.Retail.ServiceContracts.Address.IAddressService) was not registered, another implementation already exists.]


ExecutingAssembly: PublishTRX, Version=20.0.0.62, Culture=neutral, PublicKeyToken=35675b1a1bf7ff32
MachineName: CBR-TSTAUTOXXCL
CommandLine: "d:\CegidUtils\PublishTRX\PublishTRX.exe" "Retail V18.00 .Net Clienteling Production" "-mail=Retail V18.00 .Net Clienteling Production_PROD.432" D:\wwwroot\integrationTestsReports\ http://CBR-TSTAUTOXXCL:8080/integrationTestsReports WebApp.Fix=[Cbr.Net.Fix=18.0.0.975;Cbp.Net.Fix=12.9.54.508;Cbr.Clienteling.Net=18.0.0.823];WorkerProcess.Multi-Tenant.Fix=[Cbr.Delphi.Fix=18.0.0.1547;Cbr.Net.Fix=18.0.0.975;Cbp.Delphi.Fix=12.9.54.432;Cbp.Net.Fix=12.9.54.508];WebApp.Current=[Cbr.Net.Current=18.0.0.1487;Cbp.Net.Current=12.9.81.726;Cbr.Clienteling.Net=18.0.0.823];WorkerProcess.Multi-Tenant.Current=[Cbr.Delphi.Current=18.0.0.2339;Cbr.Net.Current=18.0.0.1487;Cbp.Delphi.Current=12.9.81.616;Cbp.Net.Current=12.9.81.726]CPTXFiles.Fix=[;MSSQL_Y2_PLUGIN=CBR_1800_1391_20190820_0904.CPTX ] "Fix,With Fix Y2 Core;Current,With Current Y2 Core" -emaildest=
WorkingDir: d:\CegidUtils\PublishTRX
User: CEGIDGROUP\SvcTestAutoRetail
Duration: 00:00:04.4234614
PeakVirtualMemorySize: 1.18 GB