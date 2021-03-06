.. _nuconnectionendpoint:

nuconnectionendpoint
===========================================

.. class:: nuconnectionendpoint.NUConnectionendpoint(bambou.nurest_object.NUMetaRESTObject,):

None


Attributes
----------


- ``ip_address``: IP Address of the end point.

- ``ip_type``: IPv4 or IPv6.

- ``ipv6_address``: IPv6 address of the end point.

- ``name`` (**Mandatory**): Name of the connection endpoint.

- ``last_updated_by``: ID of the user who last updated the object.

- ``description``: A description of the connection endpoint.

- ``end_point_type``: Indicates if this endpoint is the source/destination of a network connection.

- ``entity_scope``: Specify if scope of entity is Data center or Enterprise level

- ``external_id``: External object ID. Used for integration with third party systems




Children
--------

================================================================================================================================================               ==========================================================================================
**class**                                                                                                                                                      **fetcher**

:ref:`numetadata.NUMetadata<numetadata>`                                                                                                                         ``metadatas`` 
:ref:`nuglobalmetadata.NUGlobalMetadata<nuglobalmetadata>`                                                                                                       ``global_metadatas`` 
================================================================================================================================================               ==========================================================================================



Parents
--------


- :ref:`nuinfrastructureaccessprofile.NUInfrastructureAccessProfile<nuinfrastructureaccessprofile>`

