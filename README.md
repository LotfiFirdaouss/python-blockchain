# python-blockchain
python blockchain built for Incident Management in ITSM

Request to use from postman:

*To print all incidents: [GET] http://localhost:5000/chain

*To add an incident: [POST] http://localhost:5000/transaction/new
with following parameers:

{
    "number":1,
    "incident_state":1,
    "active":true,
    "caller_id":567,
    "opened_by":1209,
    "opened_at":"23-12-2021",
    "location":132,
    "impact":2,
    "urgency":3,
    "cmdb_ci":45,
    "problem_id":10
}

*Add the block of transition(s): [GET] http://localhost:5000/mine
