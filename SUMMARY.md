# Table of contents

* [Intro](README.md)
* [Standards](standards/README.md)
  * [Timeline](standards/timeline.md)
  * [PCM30](standards/pcm30.md)
  * [PCM24](standards/pcm24.md)

## Architecture

* [✅ GSM Radio Stack](architecture/gsm-radio-stack/README.md)
  * [Layer 1 - Radio](architecture/gsm-radio-stack/layer-1-radio.md)
  * [Layer 2 - LAP-Dm](architecture/gsm-radio-stack/layer-2-lap-dm.md)
  * [Layer 3 − GSM signalling](architecture/gsm-radio-stack/layer-3-gsm-signalling.md)
* [MS - Mobile Station](architecture/ms-mobile-station/README.md)
  * [ME - Mobile Equipment](architecture/ms-mobile-station/me-mobile-equipment/README.md)
    * [Baseband](architecture/ms-mobile-station/me-mobile-equipment/baseband.md)
  * [SIM Card - Subscriber Identity Module](architecture/ms-mobile-station/sim-card-subscriber-identity-module.md)
* [BSS - Base Station Subsystem](architecture/bss-base-station-subsystem/README.md)
  * [🟢 BTS - Base Transceiver Station](architecture/bss-base-station-subsystem/bts-base-transceiver-station.md)
  * [✅ BSC - Base Station Controller](architecture/bss-base-station-subsystem/bsc-base-station-controller.md)
* [NSS - Network Switching Subsystem](architecture/nss-network-switching-subsystem/README.md)
  * [MSC - Mobile Switching Center](architecture/nss-network-switching-subsystem/msc-mobile-switching-center.md)
  * [HLR - Home Location Register](architecture/nss-network-switching-subsystem/hlr-home-location-register.md)
  * [VLR - Visitor Location Register](architecture/nss-network-switching-subsystem/vlr-visitor-location-register.md)
  * [AuC - Authentication Center](architecture/nss-network-switching-subsystem/auc-authentication-center.md)
  * [EIR - Equipment Identity Register](architecture/nss-network-switching-subsystem/eir-equipment-identity-register.md)
  * [VMS - Voice Mail Subsystem](architecture/nss-network-switching-subsystem/vms-voice-mail-subsystem.md)
  * [IWF - Interworking Function](architecture/nss-network-switching-subsystem/iwf-interworking-function.md)
* [OSS - Operation Support Subsystem](architecture/oss-operation-support-subsystem/README.md)
  * [OMC - Operation and Maintence Center](architecture/oss-operation-support-subsystem/omc-operation-and-maintence-center.md)
  * [NMC - Network Managment Center](architecture/oss-operation-support-subsystem/nmc-network-managment-center.md)
* [ABC - Administration & Billing Center](architecture/abc-administration-and-billing-center.md)

## GSM Channels

* [Intro](gsm-channels/intro.md)
* [Traffic Channels](gsm-channels/traffic-channels/README.md)
  * [TCH/F](gsm-channels/traffic-channels/tch-f.md)
  * [TCH/H](gsm-channels/traffic-channels/tch-h.md)
* [Signalling Channels](gsm-channels/signalling-channels/README.md)
  * [Broadcast Channels](gsm-channels/signalling-channels/broadcast-channels/README.md)
    * [FCCH - Frequency Correction Channel](gsm-channels/signalling-channels/broadcast-channels/fcch-frequency-correction-channel.md)
    * [✅ SCH - Synchronization Channel](gsm-channels/signalling-channels/broadcast-channels/sch-synchronization-channel.md)
    * [✅ BCCH - Broadcast Control Channel](gsm-channels/signalling-channels/broadcast-channels/bcch-broadcast-control-channel.md)
    * [✅ CBCH - Cell Broadcast Channel](gsm-channels/signalling-channels/broadcast-channels/cbch-cell-broadcast-channel.md)
  * [Common Control Channels](gsm-channels/signalling-channels/common-control-channels/README.md)
    * [Point-to-Multipoint Channels](gsm-channels/signalling-channels/common-control-channels/point-to-multipoint-channels/README.md)
      * [PCH - Paging Channel](gsm-channels/signalling-channels/common-control-channels/point-to-multipoint-channels/pch-paging-channel.md)
      * [RACH - Random Access Channel](gsm-channels/signalling-channels/common-control-channels/point-to-multipoint-channels/rach-random-access-channel.md)
      * [AGCH - Access Grant Channel](gsm-channels/signalling-channels/common-control-channels/point-to-multipoint-channels/agch-access-grant-channel.md)
  * [Dedicated Channels](gsm-channels/signalling-channels/dedicated-channels/README.md)
    * [✅ Point-To-Point Signalling](gsm-channels/signalling-channels/dedicated-channels/point-to-point-signalling/README.md)
      * [✅ SDCCH - Stand-alone Dedicated Control Channel](gsm-channels/signalling-channels/dedicated-channels/point-to-point-signalling/sdcch-stand-alone-dedicated-control-channel.md)
      * [✅ SACCH - Slow Associated Control Channel](gsm-channels/signalling-channels/dedicated-channels/point-to-point-signalling/sacch-slow-associated-control-channel.md)
      * [✅ FACCH - Fast Associated Control Channel](gsm-channels/signalling-channels/dedicated-channels/point-to-point-signalling/facch-fast-associated-control-channel.md)

## GSM Interfaces

* [✅ A interface](gsm-interfaces/a-interface.md)
* [✅ A-ter interface](gsm-interfaces/a-ter-interface.md)
* [✅ A-bis interface](gsm-interfaces/a-bis-interface.md)
* [✅ Um interface](gsm-interfaces/um-interface.md)

## PLMN - Public Land Mobile Network

* [Cell Id](plmn-public-land-mobile-network/cell-id.md)
* [LAI - Location Area Identification](plmn-public-land-mobile-network/lai-location-area-identification.md)
* [ARFCNs](plmn-public-land-mobile-network/arfcns.md)

## System Information Messages

* [✅ System information-1(SI1)](system-information-messages/system-information-1-si1.md)
* [✅ System information-2(SI2)](system-information-messages/system-information-2-si2.md)
* [System information-2bis(SI-2bis)](system-information-messages/system-information-2bis-si-2bis.md)
* [System information-2ter(SI-2ter)](system-information-messages/system-information-2ter-si-2ter.md)
* [System information-2 Quarter (SI-2Quater)](system-information-messages/system-information-2-quarter-si-2quater.md)
* [✅ System information-3 (SI3)](system-information-messages/system-information-3-si3.md)
* [System information-4 (SI4)](system-information-messages/system-information-4-si4.md)
* [System information-5 (SI5)](system-information-messages/system-information-5-si5.md)
* [System information-6 (SI6)](system-information-messages/system-information-6-si6.md)
* [System information-7 (SI7)](system-information-messages/system-information-7-si7.md)
* [System information-8 (SI8)](system-information-messages/system-information-8-si8.md)
* [System information-9 (SI9)](system-information-messages/system-information-9-si9.md)
* [System information-13 (SI13)](system-information-messages/system-information-13-si13.md)

## Docs

* [Page 2](docs/page-2.md)

## Paging Requests

* [Paging request type 1](paging-requests/paging-request-type-1.md)
* [Paging request type 2](paging-requests/paging-request-type-2.md)

## Messages for Mobility Management

* [Intro](messages-for-mobility-management/intro.md)
* [✅ Registration messages](messages-for-mobility-management/registration-messages/README.md)
  * [IMSI DETACH INDICATION](messages-for-mobility-management/registration-messages/imsi-detach-indication.md)
  * [LOCATION UPDATING ACCEPT](messages-for-mobility-management/registration-messages/location-updating-accept.md)
  * [LOCATION UPDATING REJECT](messages-for-mobility-management/registration-messages/location-updating-reject.md)
  * [LOCATION UPDATING REQUEST](messages-for-mobility-management/registration-messages/location-updating-request.md)
* [Security messages](messages-for-mobility-management/security-messages.md)
* [Connection management messages](messages-for-mobility-management/connection-management-messages.md)
* [Miscellaneous message](messages-for-mobility-management/miscellaneous-message.md)
