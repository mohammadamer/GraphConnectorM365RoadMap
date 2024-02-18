# Ingest M365 Roadmap content in Microsoft 365 using Microsoft Graph connectors using C# and .NET

## Summary

This sample contains a Microsoft Graph connector that shows how to Ingest M365 Roadmap content in Microsoft 365 using Microsoft Graph connectors. For each file, it M365 Roadmap content, maps them to the external connection's schema and ingests the content retaining the content and metadata. The ingested content is set to be visible to everyone in the organization.

## Version history

Version|Date|Comments
-------|----|--------
1.0|Feb 18, 202|Initial release

## Prerequisites

- [Microsoft 365 Developer tenant](https://developer.microsoft.com/microsoft-365/dev-program)
- [.NET 8](https://dotnet.microsoft.com/download/dotnet/7.0)
- Microsoft PowerShell

## Minimal path to awesome

- Clone this repository 
- add the information about the Entra ID app in user secrets
- Build the project: `dotnet build`
- Change the working directory to the path to where the project file is present.
- Create the external connection: `./connector create-connection` (this will take several minutes)
- Ingest the content: `./connector load-content`
