# Paging request type 1

This message is sent on the CCCH by the network to up to two mobile stations to trigger channel access by these.&#x20;

The mobile stations are identified by their TMSI or IMSI. See Table 9.22/GSM 04.08.&#x20;

The L2 pseudo length of this message is the sum of lengths of all information elements present in the message except the P1 Rest Octets and L2 Pseudo Length information elements.

![](<../.gitbook/assets/image (1).png>)

![](<../.gitbook/assets/image (20).png>)

This message is sent from the network on the Common Control Channel (CCCH) to prompt one or up to two mobile stations to initiate channel access.&#x20;

The targeted mobile stations are identified using their Temporary Mobile Subscriber Identity (TMSI) or International Mobile Subscriber Identity (IMSI).

The L2 pseudo length, which is crucial for message integrity, is calculated by summing the lengths of all present information elements except for the P1 Rest Octets and L2 Pseudo Length information elements. For further details, refer to Table 9.22 in GSM 04.08.
