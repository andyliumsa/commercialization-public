---
title: Camera Driver System Test - MediaCapture - ValidateFrameIsoSpeedValues
description: Camera Driver System Test - MediaCapture - ValidateFrameIsoSpeedValues
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 121fe154-b7a2-47a2-9aa6-629ba25bcbbc
---

# <span id="p_hlk_test.bfcf4a45-33fc-4ece-93ca-97dfacfa2b24"></span>Camera Driver System Test - MediaCapture - ValidateFrameIsoSpeedValues


This test validates ISO Speed values exposed by the camera via variable photo sequence capture (3 frame and 10 frame). In each case it will step through the exposed range of values based on the number of frames captured.

## Test details
|||
|---|---|
| **Specifications**  | <ul><li>System.Client.Camera.VideoCaptureAndCameraControls</li></ul> |  
| **Platforms**   | <ul><li>Windows 10 client editions (x86)</li><li>Windows 10, client editions (x64)</li><li>Windows 10, client editions (ARM64)</li><li>Windows 10, mobile edition (ARM)</li><li>Windows 10, mobile edition (ARM64)</li></ul> |
| **Supported Releases** | <ul><li>Windows 10</li><li>Windows 10, version 1511</li><li>Windows 10, version 1607</li><li>Windows 10, version 1703</li><li>Windows 10, version 1709</li></ul> |
|**Expected run time (in minutes)**| 1 |
|**Category**| Compatibility |
|**Timeout (in minutes)**| 10 |
|**Requires reboot**| false |
|**Requires special configuration**| false |
|**Type**| automatic |

 

## <span id="Additional_documentation"></span><span id="additional_documentation"></span><span id="ADDITIONAL_DOCUMENTATION"></span>Additional documentation


Tests in this feature area might have additional documentation, including prerequisites, setup, and troubleshooting information, that can be found in the following topic(s):

-   [System.Client additional documentation](system-client-additional-documentation.md)

## <span id="More_information"></span><span id="more_information"></span><span id="MORE_INFORMATION"></span>More information


### <span id="Parameters"></span><span id="parameters"></span><span id="PARAMETERS"></span>Parameters

| Parameter name                  | Parameter description                                                |
|---------------------------------|----------------------------------------------------------------------|
| **DriverVerifierExcludedFlags** | Driver Verifier flags that may be manually excluded for the test run |
| **AllVideoDevices**             |                                                                      |

 

## <span id="Troubleshooting"></span><span id="troubleshooting"></span><span id="TROUBLESHOOTING"></span>Troubleshooting


For generic troubleshooting of HLK test failures, see [Troubleshooting Windows HLK Test Failures](..\user\troubleshooting-windows-hlk-test-failures.md).

 

 






