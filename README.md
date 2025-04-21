# BigTree

eligibilityd InputManager values for test Apple Intelligence 

`
(lldb) po [InputManager sharedInstance] objectForInputValue:1]
[LocatedCountryInput countryCodes:{(
    CN
)} confidence:4 [EligibilityInput type:OS_ELIGIBILITY_INPUT_COUNTRY_LOCATION status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 14:01:08 +0000 settingProcess:countryd(413)]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:1]
(lldb) po [InputManager sharedInstance] objectForInputValue:2]
[CountryBillingInput countryCode:"US" appStore:US music:US iCloud:US [EligibilityInput type:OS_ELIGIBILITY_INPUT_COUNTRY_BILLING status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 14:01:01 +0000 settingProcess:amsaccountsd(479)]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:2]
(lldb) po [InputManager sharedInstance] objectForInputValue:3]
[DeviceClassInput deviceClass:"Mac" [EligibilityInput type:OS_ELIGIBILITY_INPUT_DEVICE_CLASS status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 14:00:45 +0000 settingProcess:eligibilityd]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:3]
(lldb) po [InputManager sharedInstance] objectForInputValue:4]
[DeviceLocaleInput deviceLocale:"US" [EligibilityInput type:OS_ELIGIBILITY_INPUT_DEVICE_LOCALE status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 12:25:27 +0000 settingProcess:eligibilityd]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:4]
(lldb) po [InputManager sharedInstance] objectForInputValue:5]
[ChinaCellularInput chinaCellularDevice:N [EligibilityInput type:OS_ELIGIBILITY_INPUT_CHINA_CELLULAR status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 14:00:45 +0000 settingProcess:eligibilityd]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:5]
(lldb) po [InputManager sharedInstance] objectForInputValue:6]
[DeviceRegionCodeInput deviceRegionCode:"LL" [EligibilityInput type:OS_ELIGIBILITY_INPUT_DEVICE_REGION_CODE status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 14:00:45 +0000 settingProcess:eligibilityd]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:6]
(lldb) po [InputManager sharedInstance] objectForInputValue:7]
[DeviceLanguageInput deviceLanguages:(en)"(
    "en-US"
)" [EligibilityInput type:OS_ELIGIBILITY_INPUT_DEVICE_LANGUAGE status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 12:25:27 +0000 settingProcess:eligibilityd]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:7]
(lldb) po [InputManager sharedInstance] objectForInputValue:8]
[GenerativeModelSystemInput supportsGenerativeModelSystems:Y [EligibilityInput type:OS_ELIGIBILITY_INPUT_GENERATIVE_MODEL_SYSTEM status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 14:00:45 +0000 settingProcess:eligibilityd]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:8]
(lldb) po [InputManager sharedInstance] objectForInputValue:9]
[GreymatterQueueInput onQueue: N [EligibilityInput type:OS_ELIGIBILITY_INPUT_GREYMATTER_ON_QUEUE status:OS_ELIGIBILITY_INPUT_STATUS_NOT_SET setTime:2025-04-21 12:25:27 +0000 settingProcess:<NULL>]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:9]
(lldb) po [InputManager sharedInstance] objectForInputValue:10]
[SiriLanguageInput language:"en-US" [EligibilityInput type:OS_ELIGIBILITY_INPUT_SIRI_LANGUAGE status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 12:25:27 +0000 settingProcess:eligibilityd]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:10]
(lldb) po [InputManager sharedInstance] objectForInputValue:11]
[ExternalBootDriveInput hasExternalBootDrive:N [EligibilityInput type:OS_ELIGIBILITY_INPUT_EXTERNAL_BOOT_DRIVE status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 14:00:45 +0000 settingProcess:eligibilityd]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:11]
(lldb) po [InputManager sharedInstance] objectForInputValue:12]
[SharediPadInput isSharediPad:N [EligibilityInput type:OS_ELIGIBILITY_INPUT_SHARED_IPAD status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 12:25:27 +0000 settingProcess:eligibilityd]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:12]
(lldb) po [InputManager sharedInstance] objectForInputValue:13]
[EligibilityInput type:OS_ELIGIBILITY_INPUT_DEVICE_AND_SIRI_LANGUAGE_MATCH status:OS_ELIGIBILITY_INPUT_STATUS_NONE setTime:2025-04-21 12:25:27 +0000 settingProcess:eligibilityd]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:13]
(lldb) po [InputManager sharedInstance] objectForInputValue:14]
[InitialSetupLocationInput countryCodes:(null) [EligibilityInput type:OS_ELIGIBILITY_INPUT_INITIAL_SETUP_LOCATION status:OS_ELIGIBILITY_INPUT_STATUS_NOT_SET setTime:2025-04-21 12:25:27 +0000 settingProcess:<NULL>]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:14]
(lldb) po [InputManager sharedInstance] objectForInputValue:15]
[BirthdateInput age:(null) [EligibilityInput type:OS_ELIGIBILITY_INPUT_BIRTHDATE status:OS_ELIGIBILITY_INPUT_STATUS_NOT_SET setTime:2025-04-21 12:25:27 +0000 settingProcess:<NULL>]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:15]
(lldb) po [InputManager sharedInstance] objectForInputValue:16]
[PreciseLocationInput countryCodes:(null) [EligibilityInput type:OS_ELIGIBILITY_INPUT_PRECISE_LOCATION status:OS_ELIGIBILITY_INPUT_STATUS_NOT_SET setTime:2025-04-21 12:25:27 +0000 settingProcess:<NULL>]]

  Evaluated this expression after applying Fix-It(s):
    [[InputManager sharedInstance] objectForInputValue:16]
`
