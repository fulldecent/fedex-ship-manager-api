# Secret FedEx® Ship Manager® API

FedEx has two simple web API endpoints which you can use to print shipping labels. We use these APIs to ship products directly from our internal production fulfillment dashboard. It took about 30 minutes to set up and does NOT require registration through the [FedEx developer program](https://www.fedex.com/en-us/developer.html).

To our knowledge, this API is secret, and the document you are reading is the only place which explains it. We have set this up in our producting shipping environment and have been using it without change for 5+ years. It was as simple to setup as [DYMO® Label Framework](http://developers.dymo.com/2010/06/02/dymo-label-framework-javascript-library-samples-print-a-label/), which we also use in fulfillment.

## ![demo](/Users/williamentriken/Desktop/fedex-ship-manager-api/demo.png)Feature overview

|                                                 | Ship Manager® API<br />(this document) | FedEx Web Services<br />standard services | FedEx Web Services<br />advanced services |
| ----------------------------------------------- | -------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| Use without registering                         | ✅                                      | ❌                                         | ❌                                         |
| Create shipments                                | ✅                                      | ❌                                         | ✅                                         |
| Quote rate                                      | ❌                                      | ✅                                         | ❌                                         |
| Validate service availability                   | ❌                                      | ✅                                         | ❌                                         |
| Validate postal codes                           | ❌                                      | ✅                                         | ✅                                         |
| Validate addresses                              | ❌                                      | ❌                                         | ✅                                         |
| Track shipments                                 | ❌                                      | ✅                                         | ❌                                         |
| Search FedEx locations                          | ❌                                      | ✅                                         | ❌                                         |
| Manage open shipping                            | ❌                                      | ❌                                         | ✅                                         |
| Manage pickups                                  | ❌                                      | ❌                                         | ✅                                         |
| Close shipments                                 | ❌                                      | ❌                                         | ✅                                         |
| DGDS — upload dangerous goods commodities data  | ❌                                      | ❌                                         | ✅                                         |
| DGLD – retrieve dangerous goods shipments       | ❌                                      | ❌                                         | ✅                                         |
| Redirect shipments                              | ❌                                      | ❌                                         | ✅                                         |
| Can be used in applications that will be resold | :white_check_mark:                     | :x:                                       | :x:                                       |

## Endpoints

### `POST https://www.fedex.com/fcl/logon.do`

You must call the login endpoint first before creating shipments.

Read the [logon endpoint documentation](logon-documentation.md) or try the [logon endpoint live example](logon-example.html).

### `POST https://www.fedex.com/shipping/shipAction.handle?method=doContinue`

You will call the ship endpoint to create each shipment.

Read the [ship endpoint documentation](ship-documentation.md) or try the [ship endpoint live example](ship-example.html).

## Project scope

This project endeavors to fully document the logon and ship endpoints. Any issue or pull request which can improve such documentation is in scope.

Additionally, if there is a machine readible vocabulary for documenting these endpoints (like [Swagger](https://github.com/swagger-api/swagger-spec#readme), [RAML](http://raml.org/), [API Blueprint](https://apiblueprint.org/), [HAL](http://stateless.co/hal_specification.html), [Hydra](http://www.w3.org/ns/hydra/spec/latest/core/), etc) then it will be in scope to add these structured descriptions into the project.

## Disclaimers

This repository is developed independently and is not affiliated with FedEx. FedEx, ShipManager and DYMO are registered trademarks of their respective owners.

