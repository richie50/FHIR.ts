# Changelog

## 1.1.3
---
### Updates (General)

* A CHANGELOG has now been implemented to better track updates made to the library

### Updates (R4)

* The `Extension` resource previous assigned all value[x] to type `string`. This has been corrected. Below is the list of all value types affected:

  * `valueCanonical` now requires a `Canonical` object 
  * `valueCode` now requires a `Code` object 
  * `valueInstant` now requires a `Instant` object 
  * `valueAddress` now requires a `Address` object 
  * `valueAnnotation` now requires a `Annotation` object 
  * `valueAttachment` now requires a `Attachment` object 
  * `valueCodeableConcept` now requires a `CodeableConcept` object 
  * `valueContactPoint` now requires a `ContactPoint` object 
  * `valueHumanName` now requires a `HumanName` object 
  * `valueMoney` now requires a `Money` object 
  * `valuePeriod` now requires a `Period` object 
  * `valueQuantity` now requires a `Identifier` object 
  * `valueRange` now requires a `Range` object 
  * `valueRatio` now requires a `Ratio` object 
  * `valueReference` now requires a `Reference` object 
  * `valueSampledData` now requires a `SampledData` object 
  * `valueSignature` now requires a `Signature` object 
  * `valueContactDetail` now requires a `ContactDetail` object 
  * `valueContributor` now requires a `Contributor` object 
  * `valueDataRequirement` now requires a `Timing` object 
  * `valueExpression` now requires a `DataRequirement` object 
  * `valueParameterDefinition` now requires a `Expression` object 
  * `valueRelatedArtifact` now requires a `ParameterDefinition` object 
  * `valueTriggerDefinition` now requires a `TriggerDefinition` object 
  * `valueDosage` now requires a `Dosage` object 

## 1.1.2
---
### Updates (R4)

* All instances of `_class` have been replaced with `class`. This affects the following:

  * ConsentProvision
  * Coverage
  * Encounter
  * EncounterClassHistory
  * SubstancePolymer
  * SubstanceSourceMaterialOrganismGeneral

## 1.1.1
---
### Updates (General)

* Updated spelling error in documentation
* Updated example in documentation

## 1.1.0
---
### Updates (R3)

* Updated FHIR.ts file to FHIR-R3.ts

### Updates (R4)

* All classes previously created have been replaced with classes generated from swagger