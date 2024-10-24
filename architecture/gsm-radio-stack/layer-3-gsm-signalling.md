# Layer 3 − GSM signalling

### CM - Connection Management Layer

The CM layer is the topmost layer of the GSM protocol stack.&#x20;

This layer is responsible for Call Control, Supplementary Service Management, and Short Message Service Management.&#x20;

Each of these services are treated as individual layer within the CM layer.&#x20;

Other functions of the CC sublayer include call establishment, selection of the type of service (including alternating between services during a call), and call release.

Read More about it on `Paging Requests Messages`

### MM - Mobility Management Layer

The MM layer is stacked above the RR layer. It handles the functions that arise from the mobility of the subscriber, as well as the authentication and security aspects.&#x20;

Location management is concerned with the procedures that enable the system to know the current location of a powered-on MS so that incoming call routing can be completed.

### RR - Radio Resource Management Layer&#x20;

The RR layer is the lower layer that manages a link, both radio and fixed, between the MS and the MSC. For this formation, the main components involved are the MS, BSS, and MSC.&#x20;

The responsibility of the RR layer is to manage the RR-session, the time when a mobile is in a dedicated mode, and the radio channels including the allocation of dedicated channels.
