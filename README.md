## Responsys Kit Integration

This repository contains the [Responsys](https://docs.oracle.com/cloud/latest/marketingcs_gs/OMCFB/) integration for the [mParticle Apple SDK](https://github.com/mParticle/mparticle-apple-sdk).

### Adding the integration
1. For adding the Responsys SDK, refer to  the [Step-by-Step guide](https://docs.oracle.com/cloud/latest/marketingcs_gs/OMCFA/ios/step-by-step/) and follow steps [1] through [7].

	**NOTE**: In **step [2]**, download your app's **pushio_config.json** file, however, this does not need to be added to your app, you will need its contents to create the Responsys Connection in your mParticle workspace. 

2. Download the [Responsys Kit files](https://github.com/mparticle-integrations/mparticle-apple-integration-responsys/tree/master/mParticle-Responsys) and include it in your project target.

3. Follow the mParticle iOS SDK [quick-start](https://github.com/mParticle/mparticle-apple-sdk), then rebuild and launch your app, and verify that you see `"Included kits: { Responsys }"` in your Xcode console 

> (This requires your mParticle log level to be at least Debug)

4. Follow step [8.5] in [Step-by-Step guide](https://docs.oracle.com/cloud/latest/marketingcs_gs/OMCFA/ios/step-by-step/) to register the app. 

    **NOTE**:  This step might prompt user for push notification permission if not already prompted. If you want to delay notification permission prompt than register at appropriate place.

5. Reference mParticle's integration docs below to enable the integration.

6. To enable additional features of the Responsys SDK like In-App Messaging, Notification Preferences etc., follow the respective guides available [here](https://docs.oracle.com/cloud/latest/marketingcs_gs/OMCFB/ios/).


### Documentation

[Responsys integration](https://docs.mparticle.com/integrations/oracle-responsys/event/)

### License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
