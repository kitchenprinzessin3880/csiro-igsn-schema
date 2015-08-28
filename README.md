The schema represents descriptive metadata that are required for IGSN registration by the allocating agent (CSIRO).
Some of the elements in the metadata schema are specified as mandatory (e.g., sampleNumber, sampleName, isPublic, landingPage, sampleType and sampleCuration). 
A client must supply these elements during the sample registration process. 
I have re-used elements (e.g., sampleNumber and relatedResourceIdentifier) and data types (e.g., dateType and relationType) from the IGSN registry schema in the descriptive schema. 
The dateType has been extended to describe both time instant and interval.

Remarks / TO-DO* (Version 1: 25.08.2015)

    The XML schema has been fully validated. It includes *.xsd from the IGSN registry schema (v1.0).
    Mandatory elements : sampleNumber,sampleType,sampleName,Curator, landingPage
    Finalize controlled vocabularies - samplingFeatureType, Sample Types*
    Classification details will be provided by end-users (concept name, url)
    samplingMethod is specified by users; this element can be used to specify methods/instruments that are used to collect a sample.
    The XML schema incorporates some elements and data types from the standard IGSN scheme (top-level). Namespace should be assigned for the new elements, e.g.,igsn:sampleName vs csi:sampleName
    It would be good to used a controlled list for describing property/units (sampleSize)*
    The ownership information of samples is not supported.* 
