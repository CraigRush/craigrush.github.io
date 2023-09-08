# Luciferase Reporters (ERE/PRE)

This protocol is for transfecting the Qiagen ERE/PRE luciferase assay or individual reporter plasmids and subsequently measuring luciferase activity using the Promega Dual Luciferase Assay kit.

An example timeline is: Friday (start stripping), Monday (plate cells in 96-well plates), Tuesday (transfect cells), Wednesday (drug/treat cells), Thurday (assay luciferase).

## Day -3
- 3 days prior to plating cells in 96 well plates, have cells growing in stripped media if needed (most likely needed because ERE luciferase assay tests E2 induction and activity). Typically, I split cells into a T75 with stripped media on the Friday before I plan to do the experiment.

## Day 1
- Plate cells at 15,000 cells/well in either stripped or regular media (depending on experiment) in 96 well culture plates. Plate cells such that you have them in either duplicate or triplicate (2 or 3 wells each) for each treatment or condition. There are two controls provided in the Qiagen kit, a positive control and a negative control, plate 2-3 wells or each cell line tested for each of these controls (optionally a third untransfected control can be done for each cell line as well – again 2-3 wells). Allow cells to attach overnight.

## Day 2
- Transfect cells with the Qiagen ERE Luciferase Assay DNA using Fugene HD transfection reagent. EC-PDX-023 are more difficult to transfect and requires a 4.5:1 reagent:DNA ratio (use dropdown box on the protocol page) if doing both Ishikawa and EC-PDX-023 the 4.5:1 ratio can be used for both so that you can make a mastermix for all wells of a given transfection rather than having to do them separately for cell line. Allow cells to transfect for 24 hours.

   1.	The previously used online calculator is now broken (Promega has taken it offline). Please use Craig’s excel sheet to calculate fugene amounts.

   2.	The Qiagen reporter, positive and negative controls are all provided at 100 ng/uL. If you are using Craig’s plasmid based ERE or PRE assays, you will need to calculate the amount of plasmid to use (I recommend a starting concentration of 95 ng of ERE/PRE firefly luciferase plasmid with 5 ng of constitutive renila luciferase per well).

   3.	FugeneHD protocol uses 100 ng/well of transfection DNA so make sure you have enough Qiagen reporter, positive or negative control DNA. 1 uL per well to be transfected. Or enough of the plasmids for 95 ng of reporter and 5 ng of control per well.

## Day 3
- Change media on cells and start drug treatments. For E2, it is standard to treat at 10 nM for 24 hours before reading.

## Day 4
- Read luciferase activity 24 hours after treatment start. We use the Promega Dual-Luciferase Reporter Assay (1000). Refer to protocol from Promega.

   1.	Make sure to thaw reagents to room temperature prior to use. Some of the reagents may already be reconstituted (i.e. person before reconstituted some but did not need all of the vial) but depending on volume you need, you may need to reconstitute additional vials.

   2.	Remove plates from incubator, remove media and wash once with PBS, remove PBS.

   3.	Lyse cells with 1x Passive Lysis Buffer (made from 5x PLB in kit). Lyse with 20-30 uL 1x PLB per well and gently shake/rock on rocker for 15 minutes at room temperature.

   4.	While cells are lysing, prepare LAR II and Stop&Glo reagents. 100 uL of each LAR II and Stop&Glo are needed per well.

     - LAR II is reconstituted by adding 10 mL of room temperature Luciferase Assay Buffer II to a lyophilized vial of Luciferase Assay Substrate (allow to reconstitute for ~10 min at room temperature).
  
     - Stop&Glo reagent should be prepared fresh for each use. The protocol says that the Stop&Glo reagent is 50x but their math is for 51x. I therefore prepare the amount I need based on 51x math. Prepare amount of 1x Stop&Glo reagent by diluting 51x Stop&Glo substrate into room temperature Stop&Glo Buffer.

   5.	Once lysis is complete, transfer 20 uL of lysate from the 96 well culture dish to a 96 well white plate. Do this for each well, should be done by multichanneling. All remaining steps done in this white assay plate.

   6.	Add 100 uL of LAR II solution to each assay well. Read plate using the Envision plate reader on 2nd floor using the low-sensitivity protocol. Save Read 1 to flash drive, this is the firefly luciferase reading.

   7.	Remove plate from reader and add 100 uL of 1x Stop&Glo solution to each assay well. Read using same premade protocol from above. Save Read 2 to flash drive, this is the control Renila luciferase reading.

   8.	Luciferase data should first be normalized to renila by taking the Firefly values (read 1) divided by the Renila values (read 2) for each well. Fold changes can then be looked at for treatments, e.g. average of E2 treated wells divided by average of DMSO treated wells with the values being the normalized values (read1/read2).
