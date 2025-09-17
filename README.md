# Ed-Fi
Ed-Fi Data Model 4.0
<img src="https://github.com/user-attachments/assets/9f13a30c-0fec-414a-af13-cda52a8f4c27" width="256px" />




## Data Tables
- addressTypeDescriptors
- calendars
- calendars_gradeLevels
- citizenshipStatusDescriptors
- classPeriods
    - classPeriods_meetingTimes
- classroomPositionDescriptors
- cohortScopeDescriptors
- cohortTypeDescriptors
- cohortYearTypeDescriptors
- contactTypeDescriptors
- countryDescriptors
- courseLevelCharacteristicDescriptors
- courses
    - courses_identificationCodes
    - courses_competencyLevels
    - courses_learningObjectives
    - courses_learningStandards
    - courses_levelCharacteristics
    - courses_offeredGradeLevels
- employmentStatusDescriptors
- entryTypeDescriptors
- gradeLevelDescriptors
- internetAccessDescriptors
- locations
- otherNameTypeDescriptors
- parents
    - parents_addresses
    - parents_addresses_periods
    - parents_electronicMails
    - parents_internationalAddresses
    - parents_languages
    - parents_languages_uses
    - parents_otherNames
    - parents_personalIdentificationDocuments
    - parents_telephones
- people
- personalInformationVerificationDescriptors
- raceDescriptors
- relationDescriptors
- schoolCategoryDescriptors
- schools
    - schools_educationOrganizationCategories
    - schools_gradeLevels
    - schools_addresses
    - schools_addresses_periods
    - schools_identificationCodes
    - schools_indicators
    - schools_indicators_periods
    - schools_institutionTelephones
    - schools_internationalAddresses
    - schools_schoolCategories
- schoolTypeDescriptors
- schoolYearTypes
- sections
    - sections_characteristics
    - sections_classPeriods
    - sections_courseLevelCharacteristics
    - sections_offeredGradeLevels
    - sections_programs
- sexDescriptors
- sourceSystemDescriptors
- staffClassificationDescriptors
- staffs
    - staffs_addresses
    - staffs_addresses_periods
    - staffs_ancestryEthnicOrigins
    - staffs_credentials
    - staffs_electronicMails
    - staffs_identificationCodes
    - staffs_identificationDocuments
    - staffs_internationalAddresses
    - staffs_languages
    - staffs_languages_uses
    - staffs_otherNames
    - staffs_personalIdentificationDocuments
    - staffs_races
    - staffs_recognitions
    - staffs_telephones
    - staffs_tribalAffiliations
    - staffs_visas
- staffSchoolAssociations
    - staffSchoolAssociations_academicSubjects
    - staffSchoolAssociations_gradeLevels
- staffSectionAssociations
- stateAbbreviationDescriptors
- studentParentAssociations
- students
- studentSchoolAssociations
    - studentSchoolAssociations_alternativeGraduationPlans
    - studentSchoolAssociations_educationPlans
- studentSectionAssociations
- studentIdentificationSystemDescriptors
- telephoneNumberTypeDescriptors
- termDescriptors
- visaDescriptors


## Actions
N/A

# Student Extensions Example 
File: C:\ProgramData\Tools4ever\NIM\config\reset\systems\<systemname>.json
```
{
    "schema": {
        "crud_objects": {
            "students": {
                "resources": {
                    "_ext": {
                        "tx": {
                            "studentId": "_:string*",
                            "censusBlockGroupSets": ["_:string*"],
                            "crisisEventSets": ["_:string*"],
                            "nonEnrolledStudentUILActivities": ["_:string*"]
                        }
                    }
                }
            }
        }
    }
}
```


# NIM Docs
The official NIM documentation can be found at: https://docs.nimsuite.com
