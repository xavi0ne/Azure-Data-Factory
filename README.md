# AZURE DATA FACTORY: The spot to learn about real-world use-cases leveraging ADF capabilities.   

Azure Data Factory (ADF) is Microsoft’s cloud-based data integration service. 
Think of it as the ETL/ELT tool in Azure — it helps you move, transform, and integrate data across different sources, both in the cloud and on-premises.

## CONTENTS

### Configure REST API Data Flow from SharePoint to AZ SQL Database

Summary: 

The ADF Data Flow loads data from a SharePoint list (via REST API), flattens it into rows, and compares it against existing rows in an Azure SQL table.

+ If a SharePoint item doesn’t exist in SQL (new ID) → insert it.
+	If it does exist in SQL → update it.
+	It’s essentially a delta load (upsert) pipeline from SharePoint into Azure SQL.

See the attached document for procedural guidance on how to configure REST API Data Flow from SharePoint to AZ SQL Database
