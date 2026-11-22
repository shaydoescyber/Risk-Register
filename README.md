# Risk-Register
Risk register project for a mock real estate company 

# Company Profile
**Name:** Summit Ridge Property Group\
**Industry:** Residential and commercial property management and brokerage\
**Founded:** 2008, headquartered in Lansing, MI, with branch offices in Grand Rapids and Detroit\
**Size:** 50 employees (17 agents, 15 property managers, 10 maintenance, 3 admin, 3 finance, 2 IT)\
**Annual revenue:** $19M (about 60% management fees, 40% sales commissions)\
**Portfolio:** 2,400 managed rental units and roughly 320 transactions per year

# Key systems:
- Property management platform (SaaS) for leases, rent collection, and maintenance tickets
- CRM for leads and agent pipelines
- E-signature and transaction management tool
- Online tenant portal with payment processing
- Smart lock and building access systems at 18 properties
- Shared drive holding scanned IDs, leases, and closing documents

# IT environment: 
2-person IT team plus an outsourced MSP, about 180 devices including agents’ personal phones and laptops (BYOD), no formal security staff, and MFA on only a few admin accounts.

# Compliance obligations: 
Fair Housing Act, state real estate licensing rules, PCI DSS (tenant payments), FTC Safeguards-style data protection for client financial info, and state breach-notification laws.

# Known potential for weak spots:
- Wire fraud and business email compromise targeting closing payments
- Agents using personal email and unmanaged devices for client documents
- Tenant portal and rent payment data held by a third-party vendor
- Smart lock vendor with little security oversight
- Single-point dependency on one property management platform
- Seasonal surge hiring with rushed onboarding and shared logins
- Property damage and liability exposure across older buildings

# All Documents 
https://drive.google.com/drive/folders/1qsl1uUDKGbC6gACx-ssIXkttQIHDgjMF?usp=sharing


