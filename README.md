# Recloser Optimisation Application

Download the Windows installer or USB package from [Releases](https://github.com/jrsath/ROA-Official-Distribution/releases).

Windows x64 engineering preview. Includes the .NET desktop runtime and the authorised KC_Test network, with identifiers and private notes removed. Geography and electrical connectivity are intentionally public with permission.

- ROA-Setup.zip: extract and run RecloserOptimisation-Setup.exe. Installation to Program Files needs administrator permission.
- usb.zip: extract the entire archive into a writable USB folder and run RecloserOptimisation.exe. Keep portable.roa beside it; work is stored under Data on that drive.
- Guest has no password. Reports, Outages and Optimization pages remain accessible; input storage is protected within the UI.
- No private account, password, recovery credential, prior study results or crash dump is bundled. Local JSON is not encrypted or tamper-proof.
- Hourly recovery replaces its previous copy. Save manually between autosaves. Originals are retained when saving edits as a new model.

This update keeps physical and electrical networks separate and includes the current provisional 11/33 kV planning case as a sanitised Guest demonstration. Its electrical graph assigns the recorded customers to supply paths and supports full and feeder-scope optimisation. Station terminals, missing sections, open points, customer counts, protection settings and fault rates remain assumptions requiring engineering review. The geographic coordinates have not been moved to conceal those gaps.

The app now reports recorded scoped customers even while reliability is pending. In Settings, report-figure export uses the active model and selected feeders, produces candidate-score and terrain/remoteness maps, and records terrain coverage. Outage maps keep feeder-level events in feeder totals while placing only uniquely matched events as points. Yellow R markers identify proposed recloser locations.

Known limitations: this is not a field-approved protection design or a forecast of achieved SAIDI. The provisional case contains assumed electrical links and supply states. The processed outage file has no coordinates for most events. Town distance is a remoteness proxy, not surveyed vehicle access; DEM coverage and slope vary by site. The supplied PDF cannot independently verify every electrical terminal. Local files are not encrypted or tamper-proof; password-recovery email needs administrator SMTP configuration. iPadOS/Android cannot run this Windows application natively. Physical laptop, tablet and USB-device performance has not been verified.

Check SHA256.csv against the downloaded ZIP. See release notes for limitations. This repository distributes binaries, not private working files or accounts.
