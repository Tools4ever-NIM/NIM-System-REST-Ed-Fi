# NIM-System-REST-Ed-Fi
Ed-Fi

Student Extensions Example (C:\ProgramData\Tools4ever\NIM\config\reset\systems\<systemname>.json)
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
