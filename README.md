
This respository contains all of the scripts needed to perform the analysis and
create the plots from [Pardo & Doré (2021)](https://ui.adsabs.harvard.edu/abs/2021arXiv210810886P/abstract).

The [`dmsl/`](dmsl/) directory contains the main calculation scripts.

The [`drivers/`](drivers/) directory contains the scripts that make all
of the plots and perform the analyses.

To run the scripts for yourself, uncomment the analysis types you'd like in [`run_analysis.py`](drivers/run_analysis.py). Then run the scripts for any plots you want to make. You can also add your own lens profiles in [`mass_profile.py`](dmsl/mass_profile.py) or your own surveys in [`survey.py`](dmsl/survey.py). 

----

<sub>Copyright 2021, by the California Institute of Technology. ALL RIGHTS RESERVED. United States Government Sponsorship acknowledged. Any commercial use must be negotiated with the Office of Technology Transfer at the California Institute of Technology. This software may be subject to U.S. export control laws. By accepting this software, the user agrees to comply with all applicable U.S. export laws and regulations. User has the responsibility to obtain export licenses, or other export authority as may be required before exporting such information to foreign countries or providing access to foreign persons.</sub>
