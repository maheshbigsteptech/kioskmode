# Solutions available to achive KIOSK Mode

## 1. [Android Management Api](https://developers.google.com/android/management)  
The Android Management API is available as part of Android Enterprise, an initiative providing developers with tools to build solutions for organizations to manage their Android device fleets. The program is intended for enterprise mobility management providers (EMMs). To deploy a production solution that uses the Android Management API, EMMs need to follow the steps outlined in Release your solution.

You can use the Android Management API to support the work profile, fully managed device, and dedicated device solution sets.

### How it works
The Android Management API supports the full enterprise mobility management lifecycle, from initial customer enrollment to setting up and managing devices.


![](https://developers.google.com/android/management/images/android-management-api.png)

### Pros
1. This Plantform providing by google 
2. We can manage policy from cloud platform and change any time event after delivering devices 
3. No worries about OS maintanace 
4. Can reduce time & cost of customize android os for our app and can more focus on App development 

### Cons
1. Don't have a control on Android OS
2. We require approval of google to use android management api, They design this api for Enterprise solution, everthing is depends up on google's approval [Permissible Usage](https://developers.google.com/android/management/permissible-usage)
3. There's poilicy update request limitation, We may need to pay for request in future if we have more devices, [Quotas](https://developers.google.com/android/management/permissible-usage)


## 2. [Android Custom ROM](https://source.android.com)

### Pros
1. We can customize everthing we want 
2. We can allow out app to allow all android settings from app 

### Cons
1. We need to make OS comstomization which should compatible with device hardware
2. Need lot more efforts on OS customization compare to app development
3. We need to take care about OS updates
4. We need to worry about software(OS)/hardware failure 

## 3. [Scalefusion- Third party](https://scalefusion.com/features-overview)
### Pros
1. We can manage policy from cloud platform and change any time event after delivering devices 
2. Manage devices using cloud platforms
### Cons
1. Don't have a control on Android OS
2. We need to take care of Android ROM as Scalefusion does not provide any solutions of ROM
3. It's costs per device

## 4. [Manageengine- Third party](https://www.manageengine.com/mobile-device-management/features.html)
### Pros
1. We can manage policy from cloud platform and change any time event after delivering devices 
2. Manage devices using cloud platforms
### Cons
1. Don't have a control on Android OS
2. We need to take care of Android ROM as Manageengine does not provide any solutions of ROM
3. It's costs per device
## 5. [Esper- Third party](https://www.esper.io)

## 6. [Esper- Third party- Custom ROM](https://www.esper.io/esper-android-x86)
## 7. [Lineage- Third party- Custom ROM](https://lineageos.org/)
### Pros
1. We can customize everthing we want 
2. We can allow out app to allow all android settings from app 

### Cons
1. We need to make OS comstomization which should compatible with device hardware
2. Need lot more efforts on OS customization compare to app development
3. We need to take care about OS updates
4. We need to worry about software(OS)/hardware failure 
                                
