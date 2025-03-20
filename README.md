# Running A Quick Demo for ARPA-H Visit
 The repo contains codes and steps for running external tracking systems to Register Endoscope and Instrument with CT/Phantom. 

 The Endoscope is tracked by Polaris Vega XT (PO_to_EN) using Transformations: PO_to_BF, BF_to_EN,

 The PIN and Instrument is tracked by Aurora (FG_to_PI) using Transformations: FG_to_EM, EM_to_PI,

 The Phantom/CT is tracked by both Polaris and Aurora by placing Probe on Markers (PO_to_CT, FG_to_CT),

 Then, Endoscope and Pin poses are expressed in {CT}: CT_to_EN, CT_to_PI.

# Things DO NOT have yet
1. {EM} to {PIN}

2. PIN .stl file.