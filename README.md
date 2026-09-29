# Recloser Optimisation Application

Download the Windows installer or USB package from [Releases](https://github.com/jrsath/ROA-Official-Distribution/releases).

Windows x64 engineering preview. Includes the .NET desktop runtime and the authorised KC_Test network, with identifiers and private notes removed. Geography and electrical connectivity are intentionally public with permission.

- ROA-Setup.zip: extract and run RecloserOptimisation-Setup.exe. Installation to Program Files needs administrator permission.
- usb.zip: extract the entire archive into a writable USB folder and run RecloserOptimisation.exe. Keep portable.roa beside it; work is stored under Data on that drive.
- Guest has no password. Reports, Outages and Optimization pages remain accessible; input storage is protected within the UI.
- No private account, password, recovery credential, prior study results or crash dump is bundled. Local JSON is not encrypted or tamper-proof.
- Hourly recovery replaces its previous copy. Save manually between autosaves. Originals are retained when saving edits as a new model.

This update adds an independent electrical-reference editor, declared supplies and switch-controlled sections, editable orthogonal SLD layout, reference/map discrepancies and reviewed SLD-based map repairs. Geographic models are preserved. Repair proposals never infer connections from nearest-node proximity; ambiguous identities, long overhead spans and new closed loops require review. Terrain scoring uses DEM slope where available and distance to configured towns; weights remain study assumptions.

Known limitations: this is not a field-approved protection design. The bundled Working network still needs reviewed substation/terminal connectivity. The earlier Benneydale audit found 170/1,727 usable radial scores, so complete-network optimisation is blocked pending topology review; no successful real-network run is claimed. Automatic PDF-to-connectivity adaptation is not implemented: import/export uses reviewed ROA electrical-reference JSON. Local files are not encrypted; password-recovery email needs administrator SMTP configuration. iPadOS/Android cannot run this Windows application natively. Physical laptop/tablet/USB-device performance has not been verified.

Check SHA256.csv against the downloaded ZIP. See release notes for limitations. This repository distributes binaries, not private working files or accounts.
