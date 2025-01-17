---
title: WindowsAI Policy CSP
description: Learn more about the WindowsAI Area in Policy CSP.
ms.date: 05/20/2024
---

<!-- Auto-Generated CSP Document -->

<!-- WindowsAI-Begin -->
# Policy CSP - WindowsAI

[!INCLUDE [Windows Insider tip](includes/mdm-insider-csp-note.md)]

<!-- WindowsAI-Editable-Begin -->
<!-- Add any additional information about this policy here. Anything outside this section will get overwritten. -->
<!-- WindowsAI-Editable-End -->

<!-- AllowImageCreator-Begin -->
## AllowImageCreator

<!-- AllowImageCreator-Applicability-Begin -->
| Scope | Editions | Applicable OS |
|:--|:--|:--|
| ✅ Device <br> ❌ User | ✅ Pro <br> ✅ Enterprise <br> ✅ Education <br> ✅ Windows SE <br> ✅ IoT Enterprise / IoT Enterprise LTSC | ✅ Windows Insider Preview |
<!-- AllowImageCreator-Applicability-End -->

<!-- AllowImageCreator-OmaUri-Begin -->
```Device
./Device/Vendor/MSFT/Policy/Config/WindowsAI/AllowImageCreator
```
<!-- AllowImageCreator-OmaUri-End -->

<!-- AllowImageCreator-Description-Begin -->
<!-- Description-Source-DDF -->
This policy setting allows you to control whether Image Creator functionality is available in the Windows Paint app.

- If you disable this policy setting, Image Creator functionality won't be accessible in the Windows Paint app.

- If you enable or don't configure this policy setting, users will be able to access Image Creator functionality.
<!-- AllowImageCreator-Description-End -->

<!-- AllowImageCreator-Editable-Begin -->
<!-- Add any additional information about this policy here. Anything outside this section will get overwritten. -->
<!-- AllowImageCreator-Editable-End -->

<!-- AllowImageCreator-DFProperties-Begin -->
**Description framework properties**:

| Property name | Property value |
|:--|:--|
| Format | `int` |
| Access Type | Add, Delete, Get, Replace |
| Default Value  | 1 |
<!-- AllowImageCreator-DFProperties-End -->

<!-- AllowImageCreator-AllowedValues-Begin -->
**Allowed values**:

| Value | Description |
|:--|:--|
| 0 | Disabled. |
| 1 (Default) | Enabled. |
<!-- AllowImageCreator-AllowedValues-End -->

<!-- AllowImageCreator-GpMapping-Begin -->
**Group policy mapping**:

| Name | Value |
|:--|:--|
| Name | AllowImageCreator |
| Path | WindowsAI > AT > WindowsComponents > Paint |
<!-- AllowImageCreator-GpMapping-End -->

<!-- AllowImageCreator-Examples-Begin -->
<!-- Add any examples for this policy here. Examples outside this section will get overwritten. -->
<!-- AllowImageCreator-Examples-End -->

<!-- AllowImageCreator-End -->

<!-- DisableAIDataAnalysis-Begin -->
## DisableAIDataAnalysis

<!-- DisableAIDataAnalysis-Applicability-Begin -->
| Scope | Editions | Applicable OS |
|:--|:--|:--|
| ❌ Device <br> ✅ User | ✅ Pro <br> ✅ Enterprise <br> ✅ Education <br> ✅ Windows SE <br> ✅ IoT Enterprise / IoT Enterprise LTSC | ✅ Windows Insider Preview |
<!-- DisableAIDataAnalysis-Applicability-End -->

<!-- DisableAIDataAnalysis-OmaUri-Begin -->
```User
./User/Vendor/MSFT/Policy/Config/WindowsAI/DisableAIDataAnalysis
```
<!-- DisableAIDataAnalysis-OmaUri-End -->

<!-- DisableAIDataAnalysis-Description-Begin -->
<!-- Description-Source-DDF -->
This policy setting allows you to control whether Windows saves snapshots of the screen and analyzes the user's activity on their device.

- If you enable this policy setting, Windows won't be able to save snapshots and users won't be able to search for or browse through their historical device activity using Recall.

- If you disable or don't configure this policy setting, Windows will save snapshots of the screen and users will be able to search for or browse through a timeline of their past activities using Recall.
<!-- DisableAIDataAnalysis-Description-End -->

<!-- DisableAIDataAnalysis-Editable-Begin -->
<!-- Add any additional information about this policy here. Anything outside this section will get overwritten. -->
<!-- DisableAIDataAnalysis-Editable-End -->

<!-- DisableAIDataAnalysis-DFProperties-Begin -->
**Description framework properties**:

| Property name | Property value |
|:--|:--|
| Format | `int` |
| Access Type | Add, Delete, Get, Replace |
| Default Value  | 0 |
<!-- DisableAIDataAnalysis-DFProperties-End -->

<!-- DisableAIDataAnalysis-AllowedValues-Begin -->
**Allowed values**:

| Value | Description |
|:--|:--|
| 0 (Default) | Enable saving Snapshots for Windows. |
| 1 | Disable saving Snapshots for Windows. |
<!-- DisableAIDataAnalysis-AllowedValues-End -->

<!-- DisableAIDataAnalysis-GpMapping-Begin -->
**Group policy mapping**:

| Name | Value |
|:--|:--|
| Name | DisableAIDataAnalysis |
| Path | WindowsAI > AT > WindowsComponents > WindowsAI |
<!-- DisableAIDataAnalysis-GpMapping-End -->

<!-- DisableAIDataAnalysis-Examples-Begin -->
<!-- Add any examples for this policy here. Examples outside this section will get overwritten. -->
<!-- DisableAIDataAnalysis-Examples-End -->

<!-- DisableAIDataAnalysis-End -->

<!-- TurnOffWindowsCopilot-Begin -->
## TurnOffWindowsCopilot

<!-- TurnOffWindowsCopilot-Applicability-Begin -->
| Scope | Editions | Applicable OS |
|:--|:--|:--|
| ❌ Device <br> ✅ User | ✅ Pro <br> ✅ Enterprise <br> ✅ Education <br> ✅ Windows SE <br> ✅ IoT Enterprise / IoT Enterprise LTSC | ✅ Windows 10, version 21H2 [10.0.19044.3758] and later <br> ✅ Windows 10, version 22H2 [10.0.19045.3758] and later <br> ✅ Windows 11, version 22H2 [10.0.22621.2361] and later <br> ✅ Windows 11, version 23H2 [10.0.22631] and later |
<!-- TurnOffWindowsCopilot-Applicability-End -->

<!-- TurnOffWindowsCopilot-OmaUri-Begin -->
```User
./User/Vendor/MSFT/Policy/Config/WindowsAI/TurnOffWindowsCopilot
```
<!-- TurnOffWindowsCopilot-OmaUri-End -->

<!-- TurnOffWindowsCopilot-Description-Begin -->
<!-- Description-Source-ADMX -->
This policy setting allows you to turn off Windows Copilot.

- If you enable this policy setting, users won't be able to use Copilot. The Copilot icon won't appear on the taskbar either.

- If you disable or don't configure this policy setting, users will be able to use Copilot when it's available to them.
<!-- TurnOffWindowsCopilot-Description-End -->

<!-- TurnOffWindowsCopilot-Editable-Begin -->
<!-- Add any additional information about this policy here. Anything outside this section will get overwritten. -->
<!-- TurnOffWindowsCopilot-Editable-End -->

<!-- TurnOffWindowsCopilot-DFProperties-Begin -->
**Description framework properties**:

| Property name | Property value |
|:--|:--|
| Format | `int` |
| Access Type | Add, Delete, Get, Replace |
| Default Value  | 0 |
<!-- TurnOffWindowsCopilot-DFProperties-End -->

<!-- TurnOffWindowsCopilot-AllowedValues-Begin -->
**Allowed values**:

| Value | Description |
|:--|:--|
| 0 (Default) | Enable Copilot. |
| 1 | Disable Copilot. |
<!-- TurnOffWindowsCopilot-AllowedValues-End -->

<!-- TurnOffWindowsCopilot-GpMapping-Begin -->
**Group policy mapping**:

| Name | Value |
|:--|:--|
| Name | TurnOffWindowsCopilot |
| Friendly Name | Turn off Windows Copilot |
| Location | User Configuration |
| Path | Windows Components > Windows Copilot |
| Registry Key Name | SOFTWARE\Policies\Microsoft\Windows\WindowsCopilot |
| Registry Value Name | TurnOffWindowsCopilot |
| ADMX File Name | WindowsCopilot.admx |
<!-- TurnOffWindowsCopilot-GpMapping-End -->

<!-- TurnOffWindowsCopilot-Examples-Begin -->
<!-- Add any examples for this policy here. Examples outside this section will get overwritten. -->
<!-- TurnOffWindowsCopilot-Examples-End -->

<!-- TurnOffWindowsCopilot-End -->

<!-- WindowsAI-CspMoreInfo-Begin -->
<!-- Add any additional information about this CSP here. Anything outside this section will get overwritten. -->
<!-- WindowsAI-CspMoreInfo-End -->

<!-- WindowsAI-End -->

## Related articles

[Policy configuration service provider](policy-configuration-service-provider.md)
