

## SolutionsByText: Wrapper for consuming [`solutions by text REST API`](https://www.solutionsbytext.com/api-support/api-documentation/>)



### Installation

        pip install SolutionsByText

### Usage

        #!/usr/bin/env python

        from solutions_by_text import carrier

        carrier_object = carrier.CarrierLookUp(api_key='API_KEY', org_code='ORG_CODE', phone='PHONE_NUMBER')
        response = carrier_object.get()
