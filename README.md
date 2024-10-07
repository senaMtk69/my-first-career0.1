# careerfield0.3

career fields

# Install
```bash
npm i install @career0.3/my-first-career0.3
```
# Usage

//Version: 3.0

import { Career, Field } from 'careerfields';

console.log( Career.getAllCareers())
console.log( Field.getAllFields())

# Installations

# Career.getCareerByName(careerName)

It accepts a valid careerName eg: 'Technology & IT' and returns Career Details.

type: json | ICareer
    
    'careerName': [ 'Technology & IT'],
    'fieldName': [ 'IT Systems Assistant', 'IT Support Technician', 'Junior Web Development', 'Help Desk Assistant'],
    
    'careerName': [ 'Marketing & Sales' ],
    'fieldName': [ 'Junior Marketing Coordinator', 'Sales Associate', 'Junior Content Creator', 'Social Media Assistant', 'Marketing Assistant', 'Sales Development Representative', 'Member Marketing', 'Certificate Validator'], 

    'careerName': [ 'Finance & Accounting' ],
    'fieldName': ['Finance Assistant', 'Financial Analyst Trainee', 'Junior Auditor', 'Accounts Payable Clerk', 'Junior Bookkeeper', 'Payroll Assistant', 'Junior Tax Analyst', 'Trainee Account Assistant'], 

# Field.getFieldNameAndCareer(fieldName, careerName)

    'careerName': [ 'Human Resources' ],
    'fieldName': ['HR Assistant', 'Junior Recruiter', 'Talent Acquisition Coordinator', 'HR Coordinator', 'Training Assistant' ],

    'careerName': [ 'Operations & Logistics' ],
    'fieldName': [ 'Operations Assistant', 'Junior Project Coordinator', 'Supply Chain Assistant', 'Logistics Coordinator', 'Procurement Assistant', 'Warehouse Associate' ],

    'careerName': [ 'Healthcare' ],
    'fieldName': [ 'Junior Medical Assistant', 'Healthcare Assistant', 'Pharmacy Technician', 'Junior Healthcare Administrator' ],

# Field.getFieldName(fieldName)

It accepts a valid fieldName eg 'Teachers Assistant, Adminstrative Assistant,...' and returns the Field Details.

    'careerName': [ 'Education' ],
    'fieldName': ['Teachers Assistant', 'Administrative Assistant', 'Admissions Assistant', 'Library Assistant', 'Curriculum Coordinator' ],

    'careerName': [ 'Creative & Design' ],
    'fieldName': [ 'Junior Graphic Designer', 'Creative Assistant', 'Junior Video Editor', 'Social Media', Content Designer' ],

# Career.getAllCareers

    'careerName': [ 'Customer Service' ],
    'fieldName': [ 'Customer Service Assistant', 'Call Center Representative', 'Junior Client Relations Specialist', 'Technical Support Assistant', 'Customer Success Coordinator', 'Junior Help Desk Support' ],

# Field.getAllFields
 
    'careerName': [ 'Engineering' ],
    'fieldName': [ 'Junior Mechanical Engineer', 'Junior Electrical Engineer', 'Engineering Technician', 'Junior Quality Assurance Engineer', 'Drafting Technician', 'Sheetmetal engineer', 'Artisan Assistant ],

    'careerName': ['Administration'],
    'fieldName': [ 'Administrative Assistant', 'Trainee Scanner', 'Trainee Admin Assistant', 'Trainee Marketing Assistant', 'Office Coordinator' ],

# Keywords

Careers Fields 

