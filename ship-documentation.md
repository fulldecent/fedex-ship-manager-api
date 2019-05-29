# Ship Endpoint Documentation

* Endpoint address: https://www.fedex.com/shipping/shipAction.handle?method=doContinue

* HTTP method: POST
* Encoding: HTTP form

## Not yet known if required or optional

- `fromData.moduleStateExpanded`
  > TODO: add documentation
  
  - Example value: `false`
- `fromData.moduleJsInitState`
  > TODO: add documentation
  
  - Example value: `lite`
- `fromData.addressData.wabsID`
  > TODO: add documentation
  
  - Example value: *empty*
- `fromData.addressData.countryCode`
  > TODO: add documentation
  
  - Example value: `US`
- `fromData.addressData.companyName`
  > TODO: add documentation
  
  - Example value: `Select or enter`
- `fromData.addressData.contactName`
  > TODO: add documentation
  
  - Example value: `Shipper Name`
- `fromData.addressData.addressLine1`
  > TODO: add documentation
  
  - Example value: `1234 Shipper Lane`
- `fromData.addressData.addressLine2`
  > TODO: add documentation
  
  - Example value: `Suite 101`
- `fromData.addressData.zipPostalCode`
  > TODO: add documentation
  
  - Example value: `19006`
- `fromData.addressData.city`
  > TODO: add documentation
  
  - Example value: `Philadelphia`
- `fromData.addressData.stateProvinceCode`
  > TODO: add documentation
  
  - Example value: `PA`
- `fromData.addressData.phoneNumber`
  > TODO: add documentation
  
  - Example value: `8001234567`
- `fromData.addressData.phoneNumberExt`
  > TODO: add documentation
  
  - Example value: *empty*
- `toDisplay.deniedPartyURL`
  > TODO: add documentation
  
  - Example value: *empty*
- `toData.srnNumber`
  > TODO: add documentation
  
  - Example value: *empty*
- `toData.addressData.wabsID`
  > TODO: add documentation
  
  - Example value: *empty*
- `toData.addressData.skipAddressCheck`
  > TODO: add documentation
  
  - Example value: `false`
- `toData.addressData.verified`
  > TODO: add documentation
  
  - Example value: `false`
- `toData.addressData.addressCheckPerformed`
  > TODO: add documentation
  
  - Example value: `false`
- `toData.addressData.addressCheckDate`
  > TODO: add documentation
  
  - Example value: *empty*
- `toData.addressData.addressSourceType`
  > TODO: add documentation
  
  - Example value: *empty*
- `toData.addressData.verifiedByINET`
  > TODO: add documentation
  
  - Example value: `false`
- `toData.addressData.uspsAddressType`
  > TODO: add documentation
  
  - Example value: *empty*
- `outlookPath`
  > TODO: add documentation
  
  - Example value: `https://www.fedex.com/woas/WoasAction.do?&amp;locale=en_us&amp;appContextPath=`
- `outlookReturnPath`
  > TODO: add documentation
  
  - Example value: `https://www.fedex.com:443/shipping/jsp/WoasClient.jsp`
- `origAddressFromWabsAsString`
  > TODO: add documentation
  
  - Example value: `||Select or enter||empty|false`
- `toAliasCountryCode`
  > TODO: add documentation
  
  - Example value: *empty*
- `toData.addressData.countryCode`
  > TODO: add documentation
  
  - Example value: `US`
- `toData.addressData.companyName`
  > TODO: add documentation
  
  - Example value: `Select or enter`
- `toData.addressData.contactName`
  > TODO: add documentation
  
  - Example value: `Receiver Name`
- `toData.addressData.addressLine1`
  > TODO: add documentation
  
  - Example value: `1234 Receiver Lane`
- `toData.addressData.addressLine2`
  > TODO: add documentation
  
  - Example value: *empty*
- `toData.addressData.zipPostalCode`
  > TODO: add documentation
  
  - Example value: `10453`
- `toData.addressData.city`
  > TODO: add documentation
  
  - Example value: `New York`
- `toData.addressData.stateProvinceCode`
  > TODO: add documentation
  
  - Example value: `LA`
- `toData.addressData.phoneNumber`
  > TODO: add documentation
  
  - Example value: `8002345678`
- `toData.addressData.phoneNumberExt`
  > TODO: add documentation
  
  - Example value: *empty*
- `toDisplay.addressCheckRequiredOnPageLoadFlag`
  > TODO: add documentation
  
  - Example value: `N`
- `psdData.shipDate`
  > TODO: add documentation
  
  - Example value: `05/29/2019`
- `psdData.expiryDate`
  > TODO: add documentation
  
  - Example value: *empty*
- `psdData.pickupDate`
  > TODO: add documentation
  
  - Example value: *empty*
- `psdData.arePackagesIdentical`
  > TODO: add documentation
  
  - Example value: *empty*
- `removeRelatedVO`
  > TODO: add documentation
  
  - Example value: `true`
- `psd_shipDate`
  > TODO: add documentation
  
  - Example value: `05/29/2019`
- `psdData.numberOfPackages`
  > TODO: add documentation
  
  - Example value: `1`
- `psdData.mpsRowDataList[0].quantity`
  > TODO: add documentation
  
  - Example value: `1`
- `psdData.weightUnitOfMeasure`
  > TODO: add documentation
  
  - Example value: `LBS`
- `psdData.mpsRowCount`
  > TODO: add documentation
  
  - Example value: `0`
- `psdData.mpsMaxRowIndex`
  > TODO: add documentation
  
  - Example value: `0`
- `psdData.mpsRowDataList[0].weight`
  > TODO: add documentation
  
  - Example value: `1`
- `psdData.weightUnitOfMeasure`
  > TODO: add documentation
  
  - Example value: `LBS`
- `psdData.mpsRowDataList[0].carriageValue`
  > TODO: add documentation
  
  - Example value: `1`
- `psdData.declaredValueCurrencyCode`
  > TODO: add documentation
  
  - Example value: `USD`
- `commodityData.documentDescriptionCode`
  > TODO: add documentation
  
  - Example value: `empty`
- `commodityData.descriptionForIntraEU`
  > TODO: add documentation
  
  - Example value: *empty*
- `commodityData.yourDocumentDescription`
  > TODO: add documentation
  
  - Example value: *empty*
- `commodityData.docShipEligibleForSED`
  > TODO: add documentation
  
  - Example value: *empty*
- `commodityData.productsAsString`
  > TODO: add documentation
  
  - Example value: *empty*
- `commodityData.displayReturnAlert`
  > TODO: add documentation
  
  - Example value: *empty*
- `psdData.serviceType`
  > TODO: add documentation
  
  - Example value: `FedEx Express Saver`
- `psdData.packageType`
  > TODO: add documentation
  
  - Example value: `FedEx Envelope`
- `psdData.mpsRowDataList[0].mpsDimensionSelect`
  > TODO: add documentation
  
  - Example value: `empty`
- `psdData.mpsRowDataList[0].mpsLength`
  > TODO: add documentation
  
  - Example value: `L`
- `psdData.mpsRowDataList[0].mpsWidth`
  > TODO: add documentation
  
  - Example value: `W`
- `psdData.mpsRowDataList[0].mpsHeight`
  > TODO: add documentation
  
  - Example value: `H`
- `psdData.dimensionUnitOfMeasure`
  > TODO: add documentation
  
  - Example value: `I`
- `psdData.dimensionsProfileName`
  > TODO: add documentation
  
  - Example value: *empty*
- `psdData.bookingConfirmationNumber`
  > TODO: add documentation
  
  - Example value: *empty*
- `psdData.shipmentWillBeReadyByHH`
  > TODO: add documentation
  
  - Example value: `1`
- `psdData.shipmentWillBeReadyByMM`
  > TODO: add documentation
  
  - Example value: `00`
- `psdData.shipmentWillBeReadyByAMPM`
  > TODO: add documentation
  
  - Example value: `AM`
- `psdData.reasonForReturn`
  > TODO: add documentation
  
  - Example value: `empty`
- `psdData.specifyReason`
  > TODO: add documentation
  
  - Example value: *empty*
- `billingData.selectedBillTransportationIndex`
  > TODO: add documentation
  
  - Example value: `1`
- `billingData.referenceData.yourReference`
  > TODO: add documentation
  
  - Example value: `ref12345`
- `billingData.selectedReferenceType`
  > TODO: add documentation
  
  - Example value: *empty*
- `billingData.referenceData.purchaseOrderNumber`
  > TODO: add documentation
  
  - Example value: *empty*
- `billingData.referenceData.invoiceNumber`
  > TODO: add documentation
  
  - Example value: *empty*
- `billingData.referenceData.departmentNumber`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.moduleJsInitState`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.moduleStateExpanded`
  > TODO: add documentation
  
  - Example value: `true`
- `ssData.diaData.addressData.wabsID`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.codData.addressData.wabsID`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.deliveryDate`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.halData.addressData.addressLine1`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.halData.addressData.addressLine2`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.halData.addressData.zipPostalCode`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.halData.addressData.city`
  > TODO: add documentation
  
  - Example value: `Select or enter`
- `ssData.diaData.addressData.countryCode`
  > TODO: add documentation
  
  - Example value: `US`
- `ssData.diaData.addressData.companyName`
  > TODO: add documentation
  
  - Example value: `Select or enter`
- `ssData.diaData.addressData.contactName`
  > TODO: add documentation
  
  - Example value: `Select or enter`
- `ssData.diaData.addressData.addressLine1`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.diaData.addressData.addressLine2`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.diaData.addressData.zipPostalCode`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.diaData.addressData.city`
  > TODO: add documentation
  
  - Example value: `Select or enter`
- `ssData.diaData.addressData.phoneNumber`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.diaData.addressData.phoneNumberExt`
  > TODO: add documentation
  
  - Example value: *empty*
- `psdData.mpsRowDataList[0].dryIceWeight`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.itarExemptionNumber`
  > TODO: add documentation
  
  - Example value: *empty*
- `ssData.signatureType`
  > TODO: add documentation
  
  - Example value: `0`
- `ssData.isUserChosenSignature`
  > TODO: add documentation
  
  - Example value: `false`
- `ssData.codDiaServiceType`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.pickupTypeCode`
  > TODO: add documentation
  
  - Example value: `3`
- `pickupDropoffData.moduleState`
  > TODO: add documentation
  
  - Example value: `C`
- `pickupDropoffData.moduleRequiredOrOptional`
  > TODO: add documentation
  
  - Example value: `O`
- `pickupDropoffData.accountAddressFlag`
  > TODO: add documentation
  
  - Example value: `ALA`
- `pickupDropoffData.displayAlert`
  > TODO: add documentation
  
  - Example value: `false`
- `pickupDropoffData.carrierCode`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.locationCode`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.confirmatioNumberPickupDate`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.accAddrLinkDisplayStatus`
  > TODO: add documentation
  
  - Example value: `true`
- `pickupDropoffData.alternativeAddressData.contactName`
  > TODO: add documentation
  
  - Example value: `Shipper Name`
- `pickupDropoffData.alternativeAddressData.companyName`
  > TODO: add documentation
  
  - Example value: `Shipper Company`
- `pickupDropoffData.alternativeAddressData.city`
  > TODO: add documentation
  
  - Example value: `Philadelphia`
- `pickupDropoffData.pickupDate`
  > TODO: add documentation
  
  - Example value: `05/29/2019`
- `pickupDropoffData.sdocType`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.isSDOCResidentialAllowed`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.pickupTypeCode`
  > TODO: add documentation
  
  - Example value: `3`
- `pickupDropoffData.confirmationNumber`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.accountAddressData.countryCode`
  > TODO: add documentation
  
  - Example value: `US`
- `pickupDropoffData.alternativeAddressData.countryCode`
  > TODO: add documentation
  
  - Example value: `US`
- `pickupDropoffData.accCountryName`
  > TODO: add documentation
  
  - Example value: `United States`
- `pickupDropoffData.altCountryName`
  > TODO: add documentation
  
  - Example value: `United States`
- `pickupDropoffData.accountAddressData.companyName`
  > TODO: add documentation
  
  - Example value: `Shipper Company`
- `pickupDropoffData.alternativeAddressData.companyName`
  > TODO: add documentation
  
  - Example value: `Shipper Company`
- `pickupDropoffData.alternativeAddressData.contactID`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.accountAddressData.contactName`
  > TODO: add documentation
  
  - Example value: `Shipper Name`
- `pickupDropoffData.alternativeAddressData.contactName`
  > TODO: add documentation
  
  - Example value: `Shipper Name`
- `pickupDropoffData.accountAddressData.addressLine1`
  > TODO: add documentation
  
  - Example value: `1234 Shipper Lane`
- `pickupDropoffData.alternativeAddressData.addressLine1`
  > TODO: add documentation
  
  - Example value: `1234 Shipper Lane`
- `pickupDropoffData.accountAddressData.addressLine2`
  > TODO: add documentation
  
  - Example value: `Suite 101`
- `pickupDropoffData.alternativeAddressData.addressLine2`
  > TODO: add documentation
  
  - Example value: `Suite 101`
- `pickupDropoffData.accountAddressData.zipPostalCode`
  > TODO: add documentation
  
  - Example value: `19006`
- `pickupDropoffData.alternativeAddressData.zipPostalCode`
  > TODO: add documentation
  
  - Example value: `19006`
- `pickupDropoffData.accountAddressData.city`
  > TODO: add documentation
  
  - Example value: `Philadelphia`
- `pickupDropoffData.alternativeAddressData.city`
  > TODO: add documentation
  
  - Example value: `Philadelphia`
- `pickupDropoffData.accountAddressData.stateProvinceCode`
  > TODO: add documentation
  
  - Example value: `PA`
- `pickupDropoffData.accStateName`
  > TODO: add documentation
  
  - Example value: `PA`
- `pickupDropoffData.alternativeAddressData.stateProvinceCode`
  > TODO: add documentation
  
  - Example value: `PA`
- `pickupDropoffData.alternativeAddressData.stateProvinceCode`
  > TODO: add documentation
  
  - Example value: `PA`
- `pickupDropoffData.accountAddressData.phoneNumber`
  > TODO: add documentation
  
  - Example value: `8001234567`
- `pickupDropoffData.accountAddressData.phoneNumberExt`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.alternativeAddressData.phoneNumber`
  > TODO: add documentation
  
  - Example value: `8001234567`
- `pickupDropoffData.alternativeAddressData.phoneNumberExt`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.alternativeAddressData.residential`
  > TODO: add documentation
  
  - Example value: `false`
- `pickupDropoffData.serviceCode`
  > TODO: add documentation
  
  - Example value: `FedEx Express`
- `pickupDropoffData.numberOfPieces`
  > TODO: add documentation
  
  - Example value: `1`
- `pickupDropoffData.totalWeight`
  > TODO: add documentation
  
  - Example value: `0`
- `pickupDropoffData.weightUnit`
  > TODO: add documentation
  
  - Example value: `LBS`
- `pickupDropoffData.formattedPickupDate`
  > TODO: add documentation
  
  - Example value: `05/29/2019`
- `pdm_pickupDate`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.packageReadyTime`
  > TODO: add documentation
  
  - Example value: `1200`
- `pickupDropoffData.companyCloseTime`
  > TODO: add documentation
  
  - Example value: `1800`
- `pickupDropoffData.personWithSkidNumber`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.packageLocationOrInstructions`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.dimProfile`
  > TODO: add documentation
  
  - Example value: `empty`
- `pickupDropoffData.dimLength`
  > TODO: add documentation
  
  - Example value: `L`
- `pickupDropoffData.dimWidth`
  > TODO: add documentation
  
  - Example value: `W`
- `pickupDropoffData.dimHeight`
  > TODO: add documentation
  
  - Example value: `H`
- `pickupDropoffData.dimUnit`
  > TODO: add documentation
  
  - Example value: `I`
- `pickupDropoffData.truckType`
  > TODO: add documentation
  
  - Example value: *empty*
- `pickupDropoffData.truckSize`
  > TODO: add documentation
  
  - Example value: *empty*
- `notificationData.senderNotifications.email`
  > TODO: add documentation
  
  - Example value: `shipper@example.com`
- `notificationData.senderNotifications.notificationLanguage`
  > TODO: add documentation
  
  - Example value: `en`
- `notificationData.senderNotifications.shipmentNotificationFlag`
  > TODO: add documentation
  
  - Example value: `true`
- `notificationData.senderNotifications.tenderedNotificationFlag`
  > TODO: add documentation
  
  - Example value: `true`
- `notificationData.senderNotifications.exceptionNotificationFlag`
  > TODO: add documentation
  
  - Example value: `true`
- `notificationData.senderNotifications.deliveryNotificationFlag`
  > TODO: add documentation
  
  - Example value: `true`
- `notificationData.recipientNotifications.email`
  > TODO: add documentation
  
  - Example value: `receiver@example.com`
- `notificationData.recipientNotifications.notificationLanguage`
  > TODO: add documentation
  
  - Example value: `en`
- `notificationData.recipientNotifications.shipmentNotificationFlag`
  > TODO: add documentation
  
  - Example value: `true`
- `notificationData.recipientNotifications.tenderedNotificationFlag`
  > TODO: add documentation
  
  - Example value: `true`
- `notificationData.recipientNotifications.exceptionNotificationFlag`
  > TODO: add documentation
  
  - Example value: `true`
- `notificationData.recipientNotifications.deliveryNotificationFlag`
  > TODO: add documentation
  
  - Example value: `true`
- `notificationData.other1Notifications.email`
  > TODO: add documentation
  
  - Example value: *empty*
- `notificationData.other1Notifications.notificationLanguage`
  > TODO: add documentation
  
  - Example value: `en`
- `notificationData.other2Notifications.email`
  > TODO: add documentation
  
  - Example value: *empty*
- `notificationData.other2Notifications.notificationLanguage`
  > TODO: add documentation
  
  - Example value: `en`
- `notificationData.formatType`
  > TODO: add documentation
  
  - Example value: `H`
- `notificationData.emailMessage`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.proscribedCountry`
  > TODO: add documentation
  
  - Example value: `false`
- `completeShipData.fromEU`
  > TODO: add documentation
  
  - Example value: `false`
- `completeShipData.toEU`
  > TODO: add documentation
  
  - Example value: `false`
- `completeShipData.dynamicModuleNumber`
  > TODO: add documentation
  
  - Example value: `1,6`
- `completeShipData.products`
  > TODO: add documentation
  
  - Example value: `false`
- `completeShipData.createShipProfileEnabled`
  > TODO: add documentation
  
  - Example value: `true`
- `completeShipData.saveShipProfileEnabled`
  > TODO: add documentation
  
  - Example value: `false`
- `completeShipData.saveShipProfileAsNewEnabled`
  > TODO: add documentation
  
  - Example value: `false`
- `completeShipData.saveForLaterShowed`
  > TODO: add documentation
  
  - Example value: `true`
- `completeShipData.saveForLaterClicked`
  > TODO: add documentation
  
  - Example value: `false`
- `completeShipData.pendingId`
  > TODO: add documentation
  
  - Example value: `0`
- `completeShipData.profileId`
  > TODO: add documentation
  
  - Example value: `0`
- `completeShipData.shipFromPendingShipment`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.shipFromShipmentProfile`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.shipmentStatus`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.reviewShipmentProfilesFlg`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.reviewPaginationInfo`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.hasNextProfile`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.hasPreviousProfile`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.reviewEvent`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.docShipEligibleForEEISED`
  > TODO: add documentation
  
  - Example value: `false`
- `completeShipData.dbFull`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.nickNameDuplicateFlg`
  > TODO: add documentation
  
  - Example value: `N`
- `returnsTandCFlag`
  > TODO: add documentation
  
  - Example value: *empty*
- `orderData.externalOrderId`
  > TODO: add documentation
  
  - Example value: *empty*
- `orderData.middlewareVersion`
  > TODO: add documentation
  
  - Example value: *empty*
- `orderData.originatingSystem`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.profileNickName`
  > TODO: add documentation
  
  - Example value: *empty*
- `completeShipData.mobileShipmentEmailAddress`
  > TODO: add documentation
  
  - Example value: *empty*
- `utype`
  > TODO: add documentation
  
  - Example value: `null`