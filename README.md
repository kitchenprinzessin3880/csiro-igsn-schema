The schema represents descriptive metadata that are required for IGSN registration by the allocating agent (CSIRO).
Some of the elements in the metadata schema are specified as mandatory (e.g., sampleNumber, sampleName, isPublic, landingPage, sampleType and sampleCuration). 
A client must supply these elements during the sample registration process. 
I have re-used elements (e.g., sampleNumber and relatedResourceIdentifier) and data types (e.g., dateType and relationType) from the IGSN registry schema in the descriptive schema. 
The dateType has been extended to describe both time instant and interval.

    The XML schema has been fully validated. It includes *.xsd from the IGSN registry schema (v1.0).

Remarks / TO-DO* (Version 1: 16.10.2015)
    * Finalize controlled vocabularies - sampleTypes,MaterialTypes,samplingMethods
    * Classification details will be provided by end-users (concept name or url?)
    * The XML schema incorporates some elements and data types from the standard IGSN scheme (top-level). Which Namespace should be assigned to new elements?, e.g.,igsn:sampleName vs csi:sampleName
