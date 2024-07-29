# TimeMaps - Online Personal Financial Literacy Software

<H3>Support and Upgrade Roadmap Overview</H3>

<p>
  This document outlines the proposed phases and steps to upgrade the architecture, technology stack and user interface for the following reasons, among others, and the basic solution support to be provided by        Softeknology, Inc.  Here are some of the objectives of this project.

  <ul>
    
    • Modernize Overall Solution  
    • Ensure Application Resiliency  
    • Implement Auto Scaling  
    • Enhance Data and Application Security  
    • Promote Source Code Maintainability  
    • Introduce User-Friendly Interface  
    • Decrease Operational Cost  
    
  </ul>

Implementing  [Cloud-Native](https://learn.microsoft.com/en-us/dotnet/architecture/cloud-native/definition) and [Microservice](https://learn.microsoft.com/en-us/azure/architecture/microservices/) 
architectures and principles we can achieve these objectives as well as many others.  Adopting Microsoft Azure, C#, .NET Core, ASP.NET Core and Blazor also help address many of these concerns.
</p>

<H3>Support Plan</H3>

<p>
  The application is Currently supported via email request.  Maintenance and application issues are being neglected.  Softeknology, Inc. proposes to assume the ongoing responsibility of supporting email requests as    well as any other client/customer concerns either by email or directly by phone.  Softeknology, Inc. will also assume responsibility for addressing any current application issues.
</p>

<p>
  Softeknology, Inc. will create a cloud-based source code repository for the current code base and conduct a comprehensive review of the user interface to document any current issues with the application.  Using     Azure DevOps and GitHub will achieve the following goals:

  <ul>

    • Ensure ongoing customer and application support.
    • Deliver a stable application to customers.
    • Provide a secure source code repository accessible from anywhere with internet access.
    • Furnish a repsoitory for documenting and backlogging any current application issues.
    • Standardization of static documentation.  Currently this includes PDF, Microsoft Word and Microsoft PowerPoint assets.

  </ul>

  Utilizing these same tools, a separate project will be set up for the upgrade project to keep new source code and project backlog items separate from the existing code base.
</p>

<H3>Upgrade Plan</H3>

<p>
  Because an abundance of data and source code currently exists, as opposed to a complete re-engineering of the application all at once, a multi-phased approach is being suggested.  This will minimize the time and    effort required to address some of the current issues and get a more viable product to market.
  
</p>

<H3>Phase One</H3>

<p>
  This phase begins with creating a new user interface that mimics the current applications features.  The next step involves integrating the new user interface with the existing datastore.  Finally, deploying the    new user interface and current datastore to an Azure environment will complete phase one.

<p>
  Phase one is considered complete when the new solution is operating in an Azure environment without issue.  The current code base and resources will remain in place as is, except for issue mitigation to support     existing customers.  Here are some of the actions that will take place in Phase one.

  <ul>

    • Create a new solution project and source code repository in Azure DevOps.  
    • Create a user-friendly interface in line with contemporary web application standards and practices.  
    • Standardize static content such as PDFs, Microsoft Word documents, and Microsoft PowerPoint presentations.    
    • Integrate the current data access layer with the new user interface.
    
  </ul>
  
</p>

<h3>Phase Two</h3>

<p>
  Phase 2 revolves around upgrading the current datastore and application data access layer.  The current datastore is based on a Microsoft SQL Server database and T-SQL stored procedures with ADO middleware.  A      comprehensive review of the current table structures, indexes, column constraints and stored procedures will be conducted to identify any potential improvements or consolidation.  
</p>

<p>
  Softeknology, Inc. is proposing implementing Azure SQL Database or Azure SQL Server Managed Instance, Microsoft Entity Framework Core as the new datastore and data access middleware layer and potentially            introducing Azure Cache  for Redis to boost overall application performance.  The following list outlines some considerations for this phase. 

  <ul>

    • Modern cloud-based architecture.  
    • Significant reduction in data access code due to techniques such as the generic repsoitory pattern.  
    • Reduction in operational cost.    
    • Simplified unit testing.
    • Significant reduction in datastore maintenance.    
    
  </ul>
  
</p>

<h3>Remtech, Inc. Responsibilities</h3>

<p>
  Remtech, Inc. will provide Softeknology, Inc. access to all resources required to perform support and upgrade processes outlined in this document.  This includes, but may not be limited to the following.

  <ul>

    • Current Application Source Code.  
    • Static Assets, PDF, Microsoft Word documents, Microsoft PowerPoint files  
    • Access codes and passwords to web hosting providers and email hosting providers.    
    • Access codes and passwords to database hosting providers
    • Any documentation related to releasing new versions of the application to production    
    • Any Documentation related to managing database changes and maintenance    
    
  </ul>
    
</p>

<h3>Alpha Phase Optional</h3>

<p>
  This phase would begin with moving the current solution to a Microsoft Azure environment and stabilizing the current code base.  The current code base and resources will remain in place as is, except for issue     mitigation, until the Alpha Phase is complete.
</p>

<p>
  The Alpha Phase is considered complete when, the current solution is operating in an Azure environment without issue and Customers are unaware of which environment they have been directed to. Here are some of      the actions that will take place in the Alpha Phase.

  <ul>
    
        • Move all resources to a Microsoft Azure platform.  This includes the web application, database and static resources.    

  </ul>
  
</p>
  

