.. _doc-entity-fields:

Entity Fields
=============

.. contents:: :local:
    :depth: 3


Overview
---------

Fields are used to collect details of entity records. 

For example, a 'street name', a 'zip code', and a 'building number' may be fields of an 'address.' 

You can add new fields to any :term:`custom entity <Custom Entity>` or an extendible :term:`system entity <System Entity>`.

This guide describes how to create and modify the fields.


Actions
-------

.. _doc-entity-fields-create:

Create a Custom Entity Field
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. note:: See a short demo on `how to create a custom field <https://www.orocrm.com/media-library/create-custom-field>`_, or keep reading the step-by-step guidance below.

   .. raw:: html

      <iframe width="560" height="315" src="https://www.youtube.com/embed/DwXQG9dcB0k" frameborder="0" allowfullscreen></iframe>

1. In the main menu, navigate **System>Entities>Entities Management**.

2. On the **All Entities** page, click the required entity in the grid. 

3. On the entity view page, click the :guilabel:`Create Field` button in the upper-right corner of the page. 

4. Specify information for the basic entity field properties. See the descriptions of the basic properties in the `Basic Entity Field Properties <./entity-field-properties#basic-entity-field-properties>`__ section. 
   
   |

   .. image:: ../img/entity_management/new_entity_field.png

   |

5. Click :guilabel:`Continue` button. Depending on what has been selected for **Type**, the corresponding additional fields appear.

6. Specify information for additional properties. See the descriptions of the basic properties in the `Advanced Entity Field Properties <./entity-field-properties#advanced-entity-field-properties>`__ section.

7. Click **Save** in the upper-right corner of the page. 

8. After that, you may require to update the schema. For how to do it, see the `Update Schema <./entity-actions#update-schema>`__ section. 


Edit a Custom Entity Field
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. In the main menu, navigate **System>Entities>Entities Management**.

2. On the **All Entities** page, click the required entity in the grid. 

3. On the entity view page, click **Fields**. 

4. In the grid of the **Fields** section, click the required field.

5. Make the required changes according to the description provided in step 6 of the `Create a Custom Entity Field <./entity-fields#create-a-custom-entiry-field>`__ section.  

   .. important:: 
      The list of properties editable for system entity fields depends on configuration and is created in a way reasonable and safe for the system performance and operation.  

6. Click **Save** in the upper-right corner of the page. 

7. After that, you may require to update the schema. For how to do it, see the `Update Schema <./entity-actions#update-schema>`__ section. 


Alternatively, you can start editing an entity field from the entity view page by clicking the |IcEdit| **Edit** icon at the right end of the corresponding row.



Delete a Custom Entity Field
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. In the main menu, navigate **System>Entities>Entities Management**.

2. On the **All Entities** page, click the required entity in the grid. 

3. On the entity view page, click **Fields**. 

4. In the grid of the **Fields** section, choose the required entity field and click the |IcDelete| **Delete** icon at the right end of the corresponding row. 

5. In the **Deletion Confirmation** dialog box, click :guilabel:`Yes`.

6. After that, you may require to update the schema. For how to do it, see the `Update Schema <./entity-actions#update-schema>`__ section. 


Links
-----

For the detailed description of entity field types, see the `Entity Field Types <./entity-field-types>`__ guide. 

For the overview of the entities, see the `Entities <./entities>`__ guide. 



.. |IcPosition| image:: ../../img/buttons/IcPosition.png
   :align: middle

.. |IcDelete| image:: ../../img/buttons/IcDelete.png
   :align: middle

.. |IcEdit| image:: ../../img/buttons/IcEdit.png
   :align: middle

.. |IcView| image:: ../../img/buttons/IcView.png
   :align: middle
   
.. |IcRest| image:: ../../img/buttons/IcRest.png
   :align: middle
