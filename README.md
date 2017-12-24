# Decode vSphere License

A VMware vRealize Orchestrator action sample posted on [VMware Sample Exchange](https://code.vmware.com/samples/1479/decode-vsphere-license) 
 
Decodes the `Product Name` and `Product Version` from a vSphere license string.
Also does some basic license key format validation

This sample just logs the Product Name and Product Version after some validation of the `licenseKey`

### Action Inputs:

| parameter | Type  |
| --------- | ----- |
| vCenterConnection | VC:SdkConnection |
| licenseKey | string |


**Return type:** `void`
