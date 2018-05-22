### Set a Promotion Value's code [PUT /values/promotions/{id}/code]

+ Request (application/json)
    + Headers
    
            {{header.authorization}}

    + Attributes
        + code (string, required) - {{code.set}}
        + secure (boolean, optional) - {{code.secure}}
        
    + Body
    
            {
                "code": "c3d177ff950b4e2796e341f65976e1b1",
                "secure": true
            }

+ Parameter
    + id (string) - the id of the Promotion to update the code of.

+ Response 200 (application/json)
    + Attributes
        + code (string, optional) - {{value.code}}

    + Body

            {
                "code": "…e1b1"
            }