# CAP Application Repositories

This repository contains links to multiple SAP CAPM projects covering authentication, audit logging, associations, foreign key constraints, side-by-side extensions, OData adaptations, file attachments, PostgreSQL integration, and the use of actions and functions.

## Table of Contents (Total Repositories: 11)

1. [CAP Application with Audit and Authentication Features](#cap-application-with-audit-and-authentication-features)
2. [Audit Log Feature in SAP CAPM using System-Versioned Tables in HANA DB](#audit-log-feature-in-sap-capm-using-system-versioned-tables-in-hana-db)
3. [CAPM Audit Logging with @changelog Annotation](#capm-audit-logging-with-changelog-annotation)
4. [SAP BTP CAPM: Composition and Association](#sap-btp-capm-composition-and-association)
5. [CAP List Report Project](#cap-list-report-project)
6. [CAP Foreign Key Constraints](#cap-foreign-key-constraints)
7. [CAP Side-by-Side Extension](#cap-side-by-side-extension)
8. [CAP OData V4 to OData V2 Adapter](#cap-odata-v4-to-odata-v2-adapter)
9. [CAP Attachments Plugin](#cap-attachments-plugin)
10. [Using PostgreSQL in SAP BTP CAP Application](#using-postgresql-in-sap-btp-cap-application)
11. [CAP Functions and Actions - Bookstore API](#cap-functions-and-actions---bookstore-api)

---

## CAP Application with Audit and Authentication Features  
**Repository:** [cap-auth](https://github.com/vasusena1234/cap-auth)

This project demonstrates authentication and authorization in an SAP CAP application using SAP BTP security mechanisms with RBAC controls for different entities.

## Audit Log Feature in SAP CAPM using System-Versioned Tables in HANA DB  
**Repository:** [cap-audit-log](https://github.com/vasusena1234/cap-audit-log)

Implements an audit log using system-versioned tables in HANA DB to track changes in the `Books` entity with a `Books_History` table for historical records.

## CAPM Audit Logging with @changelog Annotation  
**Repository:** [CAPM_Auditlogging](https://github.com/vasusena1234/CAPM_Auditlogging)

Uses the `@changelog` annotation to enable automatic change tracking for `ID` and `TEMP` fields in a CAPM-based application.

## SAP BTP CAPM: Composition and Association  
**Repository:** [cap-composition-association](https://github.com/vasusena1234/cap-composition-association)

Demonstrates Composition and Association concepts in SAP BTP CAPM, including deep insert functionality and entity relationships.

## CAP List Report Project  
**Repository:** [cap-listreport](https://github.com/vasusena1234/cap-listreport)

An SAP BTP Cloud Foundry application featuring Standalone and Managed App Routers with draft functionality for versioning and concurrent editing prevention.

## CAP Foreign Key Constraints  
**Repository:** [cap-foreignkey](https://github.com/vasusena1234/cap-foreignkey)

Implements foreign key constraints in a bookshop model using `assert_integrity: db` to enforce database-level referential integrity.

## CAP Side-by-Side Extension  
**Repository:** [cap-extension](https://github.com/vasusena1234/cap-extension)

Extends SAP S/4HANA functionality by consuming external OData V2 services from the SAP Sales Order API.

## CAP OData V4 to OData V2 Adapter  
**Repository:** [cap-odatav4-to-odatav2](https://github.com/vasusena1234/cap-odatav4-to-odatav2)

Exposes an OData V4 service while supporting OData V2 for backward compatibility using the `@cap-js-community/odata-v2-adapter` package.

## CAP Attachments Plugin  
**Repository:** [cap-attachments](https://github.com/vasusena1234/cap-attachments)

Enables file attachment integration in CAP applications using the `@cap-js/attachments` plugin for the `Books` entity in a Fiori List Report UI.

## Using PostgreSQL in SAP BTP CAP Application  
**Repository:** [cap-postgres-db](https://github.com/vasusena1234/cap-postgres-db)

This project demonstrates how to set up and use a PostgreSQL database in an SAP BTP CAP application. It provides:
- Database schema definitions (`schema.cds`)
- Sample data (`Books.csv`)
- Configuration for multi-target deployment (`mta.yaml`)
- Security configurations (`xs-security.json`)
- Steps to deploy and test the persistence of PostgreSQL in SAP BTP Cloud Foundry.

## CAP Functions and Actions - Bookstore API  
**Repository:** [cap-functions-and-actions](https://github.com/vasusena1234/cap-functions-and-actions)

This project showcases the use of functions and actions in a Bookstore API built with SAP CAP. It includes:
- **Actions**: Adding books, updating stock, deleting books, applying discounts.
- **Functions**: Fetching stock levels, searching books by title.
- **Service Definition (`srv/cat-service.cds`)**: Defines API endpoints for books.
- **Business Logic (`srv/cat-service.js`)**: Implements the logic for CRUD operations and custom actions/functions.

---

## Contributions & Feedback  
Feel free to contribute to these projects or raise issues/suggestions. For any questions, reach out via the respective repositories. 🚀
