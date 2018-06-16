# SharePoint Development with the CSOM and REST API

<h4>Three Implementations</h4>
<pre>
<h5>.NET Managed : Files Locate in <System Root>\ISAPI</h5>
<li>Microsft.Sharepoint.Client</li>
<li>Microsft.Sharepoint.Client.Runtime</li>

<h5>Silverlight : Files Locate in <System Root>\LAYOUTS\ClientBin</h5>
<li>Microsft.Sharepoint.Client.Silverlight</li>
<li>Microsft.Sharepoint.Client.Silverlight.Runtime</li>
  
<h5>ECMA Script (Javascript) : Files Locate in <System Root>\LAYOUTS</h5>
<li>SP.js</li>
<li>SP.Core.js</li>
<li>SP.Runtime.js</li>
</pre>

<h4>Authentication</h4>
<pre>
.Net Managed OM pass window credentials by default (log in user can call)
or
can override default
1.ClientContext.AuthenticationMode
-can set "Anonymous that no credentials (can see web without login)
-Default credentials
-FormsAuthentication
2.ClientContext.Credentials - set Windows credentials
3.ClientContext.FormsAuthenticationLoginInfo - with user/pass
</pre>
