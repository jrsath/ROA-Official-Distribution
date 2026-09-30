# Recloser Optimisation Application

Download the Windows installer or USB package from [Releases](https://github.com/jrsath/ROA-Official-Distribution/releases).

Windows x64 engineering preview. Includes the .NET desktop runtime and the authorised KC_Test network. 

- ROA-Setup.zip: extract and run RecloserOptimisation-Setup.exe. Installation to Program Files needs administrator permission.
- usb.zip: extract the entire archive into a writable USB folder and run RecloserOptimisation.exe. Keep portable.roa beside it; work is stored under Data on that drive.
- Guest has no password. Reports, Outages and Optimization pages remain accessible; input storage is protected within the UI.
- No private account, password, recovery credential, prior study results or crash dump is bundled. Local JSON is not encrypted or tamper-proof.

This update adds an independent electrical-reference editor, declared supplies and switch-controlled sections, editable orthogonal SLD layout, reference/map discrepancies and reviewed SLD-based map repairs. Geographic models are preserved. Repair proposals never infer connections from nearest-node proximity; ambiguous identities, long overhead spans and new closed loops require review. Terrain scoring uses DEM slope where available and distance to configured towns; weights remain study assumptions.


