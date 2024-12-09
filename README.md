# ASSET-MANAGEMENT-SYSTEM
This project is an asset management system designed to efficiently handle the lifecycle of assets within an organization. It consists of multiple interconnected functional modules, each with specific responsibilities to ensure seamless operations.

The Employee Master module facilitates the management of employee information. It provides capabilities to add, edit, and view employee records with search and filtering options to distinguish between active and inactive employees. A structured user interface (UI) supports these functionalities through forms and data tables integrated with features like DataTables.net for advanced filtering and searching.

The Asset Master module focuses on managing assets by enabling the addition, editing, and viewing of detailed asset records, such as type, make, model, serial number, and unique IDs. It includes filters for asset type, make, and model, alongside a robust API layer to support CRUD operations.

The Asset Category Master streamlines categorization by managing asset groups like laptops, mobile phones, and other equipment. This module ensures categories are available as dropdown options in relevant forms and provides a dedicated UI for category CRUD operations.

The Stock View module provides a branch-wise overview of assets currently in stock. It displays stock totals, categorized by branch and includes a comprehensive view of the total asset value, ensuring inventory insights.

The Issue Asset and Return Asset modules manage the asset issuance and return processes. They update asset statuses, maintain detailed logs for audit purposes, and ensure accountability through forms and APIs that capture necessary details like employee and asset information and the reasons for return.

The Scrap Asset module addresses the end-of-life phase of assets by marking them as obsolete. This excludes the assets from active views while keeping them accessible for reports. Additionally, it captures comments for documentation.

Finally, the Asset History module provides a complete lifecycle overview of each asset, from acquisition to scrapping. The history is displayed in an intuitive timeline or table format, supported by APIs that fetch historical data for transparency and traceability.

This system is built with a focus on modularity, scalability, and usability, ensuring it meets the needs of organizations managing diverse assets efficiently.
