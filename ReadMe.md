### Intro:
`canadian_band_plan.py` script does two things:

  1. It reads all `asd` output files from the Rig Expert that are placed
     in the same folder as this script and calculates the VSWR as a
    function of the frequency.
  2. It recreates the band plan for all bands from 2200m to 70cm and adds
     VSWR graphs on top of it.


### Usage:
   * Use the Rig Expert connected to a computer to scan a range of
     frequencies.
   * Copy the `asd` files along side this script.
   * Run `python canadian_band_plan.py`
