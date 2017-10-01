# AppForSharePointOnlineWebToolkit
Fixes and improvements for SharePoint Add-in Web Toolkit (for SharePoint Online)

1. Fixed invalid redirect when access token has expired, but refresh token can still be used.
2. Changed SharePointContextFilterAttribute to authentication filter (this causes execution on earlier request stage and allows to write authorization filters that connect to SharePoint).