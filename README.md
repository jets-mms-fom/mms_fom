The MMS FOM is the data dictionary used by the JETS architecture, an HLA-based architecture designed to enable interoperability for medical simulation and training systems.

The repository includes xml files for each module within the FOM, along with a PDF that provides a full description of the MMS FOM.

The latest MMS FOM V4.0.0 contains the following updates from the previous V3 version:
* Added “nasal” enumerator to MedicationAdministrationRouteEnum.
* Added “packedRedBloodCells” to MedicationEnum.
* Added “unconscious” and “paralyzed” to LevelOfConsciousnessEnum.
* Added “shivering” attribute to Signs class.
* Fixed several enumerators in the Signs class.
* In BodyLocationRecord, changed the fmaid attribute from string to integer.
* Reverted the body location change to attributes specifically in objects relating to patient forms.
* Added MagicVitals interaction to allow force-overrides of vital signs, if needed.
* Added VitalsDisplayControl interaction and VitalsDisplayStatus object, intended to control the visibility of vital signs on a patient monitor.
* Updated the Facility object and removed unused facility child objects.
* The new Facility object is used to define location, role of care, type, and patient capacity of each facility.
* Added FederateAssociation object to allow a federate to declare which patient(s) and facility(ies) it is interested in.
* Added CasualtyState object used to place a patient in a facility and indicate its triage/evacuation priority.
* Added MagicTransfer interaction to allow the initiation of a patient transfer without a vehicle modeling federate.


For more information, please contact jets@ivirinc.com

For additional detail on JETS, see https://jets-systems.com/

This work is licensed under CC BY-ND 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-nd/4.0/
