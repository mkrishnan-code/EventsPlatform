# EventsPlatform
Meetings and Events experience

Goal: Create a Platform where Attendees and Organizers can access, manage and have a personalized experience

Web Application Contraints: Multi Tenant - which requires separation of data and concerns, role based access, mobile first - reactive

AI-enablement: personalized agenda & session recommendation  , AI Q/A aummarization (possibly with RAG), forecasting for organizers (ML can be used based on historical events)

Automation: Registration, approval and notification workflows (managed in relational DB)
Incident alerts for Organizers/participants

Assumptions: Participants can be authenticated withing the enterprise against an enterprice managed user accounts systems. New users can use external auth like google auth to register



