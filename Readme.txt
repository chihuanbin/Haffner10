Title: Blue Straggler Candidates in the Open Cluster Haffner 10 from
Gaia: CMD Morphology and Astrometric Clues to Multiplicity
Authors: Chi, H. & Lv, J.
Table: Blue Straggler Star Members in Haffner 10

Description:
    This table contains the astrometric and photometric properties of 52 
    Blue Straggler Stars (BSSs) identified in the open cluster Haffner 10 
    using Gaia DR3 data. It includes the classification of each source into 
    either the 'Red' or 'Blue' BSS sequence based on their position in the 
    color-magnitude diagram.

Byte-by-byte Description of file: Haffner10_BSS_Members.csv
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1- 19  I19   ---     SourceID  Gaia DR3 source identifier
  21- 30  F10.6 deg     RA        Right Ascension (J2016.0)
  32- 41  F10.6 deg     Dec       Declination (J2016.0)
  43- 49  F7.4  mag     Gmag      Gaia DR3 mean G-band magnitude
  51- 57  F7.4  mag     BP-RP     Gaia DR3 BP-RP color
  59- 65  F7.3  mas/yr  pmRA* Proper motion in RA (pmRA * cosDec)
  67- 73  F7.3  mas/yr  pmDec     Proper motion in Dec
  75- 80  F6.4  mas     Plx       Gaia DR3 Parallax
  82- 87  F6.4  ---     Pmb       Membership probability
  89- 92  A4    ---     Type      BSS sequence classification (Red/Blue)
--------------------------------------------------------------------------------

Notes:
    (1) SourceID: Unique identifier provided by Gaia Data Release 3.
    (2) RA, Dec: Celestial coordinates from Gaia DR3 at epoch J2016.0.
    (3) pmRA*, pmDec: Proper motion components from Gaia DR3.
    (4) Pmb: Probability based on machine learning or kinematic-photometric 
        combined membership analysis.
    (5) Type: 'Red' refers to stars in the red-sequence of the BSS population, 
        'Blue' refers to the blue-sequence.