.. _nugatewayredundantport:

nugatewayredundantport
===========================================

.. class:: nugatewayredundantport.NUGatewayRedundantPort(bambou.nurest_object.NUMetaRESTObject,):

Represents a redundant Port under a particular gateway object or redundant group object.


Attributes
----------


- ``vlan_range``: VLAN Range of the Port.  Format must conform to a-b,c,d-f where a,b,c,d,f are integers between 0 and 4095.

- ``name`` (**Mandatory**): Name of the Port

- ``last_updated_by``: ID of the user who last updated the object.

- ``permitted_action``: The permitted  action to USE/EXTEND  this port.

- ``description``: A description of the Port

- ``physical_name`` (**Mandatory**): Identifier of the Redundant Port. The name should be corresponding to the Physical Name of the ports belonging to this redundant instance.

- ``entity_scope``: Specify if scope of entity is Data center or Enterprise level

- ``port_peer1_id``: The master gateway peer port id.

- ``port_peer2_id``: The slave gateway peer port id.

- ``port_type`` (**Mandatory**): Type of the Port.

- ``use_user_mnemonic``: determines whether to use user mnemonic of the Port

- ``user_mnemonic``: user mnemonic of the Port

- ``associated_egress_qos_policy_id``: UUID of the Egress QOS Policy associated with this Vlan.

- ``status``: Status of the port.

- ``external_id``: External object ID. Used for integration with third party systems




Children
--------

================================================================================================================================================               ==========================================================================================
**class**                                                                                                                                                      **fetcher**

:ref:`numetadata.NUMetadata<numetadata>`                                                                                                                         ``metadatas`` 
:ref:`nuvlan.NUVLAN<nuvlan>`                                                                                                                                     ``vlans`` 
:ref:`nuglobalmetadata.NUGlobalMetadata<nuglobalmetadata>`                                                                                                       ``global_metadatas`` 
================================================================================================================================================               ==========================================================================================



Parents
--------


- :ref:`nuredundancygroup.NURedundancyGroup<nuredundancygroup>`

