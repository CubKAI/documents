<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
<meta content="text/html; charset=utf-8" http-equiv="Content-Type" />
</head>
<body>

<h1>Project Types Differences</h1>

<h3 id="DocIntro">Overall</h3>
<p>While base functionalities are identical for all versions of ASP.NET Zero, 
there are still some differences between different versions. In this document, 
we will highlight these differences.</p>
<h4>ASP.NET Core v.s. ASP.NET MVC 5.x</h4>
<p>Beginning from <a href="https://docs.aspnetzero.com/documents/common/latest/Change-Logs">v4.1</a>, we are more focused to
<strong>ASP.NET Core</strong> based solutions (rather than ASP.NET MVC 5.x) 
since ASP.NET Core is Microsoft&#39;s new ASP.NET version. That means our new major 
features will be implemented for ASP.NET Core version (.NET Core &amp; Full .Net 
Framework).</p>
<h4>Angular v.s. Angularjs 1.x</h4>
<p>Beginning from <a href="https://docs.aspnetzero.com/documents/common/latest/Change-Logs">v4.1</a>, we are more focused to 
<strong>Angular</strong> based solution (rather than Angularjs 1.x) since Angular is Google&#39;s 
new SPA framework. That means our new major features will be implemented for 
Angular framework. </p>
<h3>Version Differences Table</h3>
<p>The table below shows <strong style="color: red">only the differences, not all features</strong>.</p>

<table class="table">
<thead>
<tr>
	<th>Feature</th>
	<th>ASP.NET Core &amp; Angular</th>
	<th>ASP.NET Core &amp; JQuery</th>
	<th>ASP.NET MVC 5.x &amp; Angularjs</th>
	<th>ASP.NET MVC 5.x &amp; JQuery</th>
</tr>
</thead>
<tbody>
<tr>
	<td>User Interface (theme)</td>
	<td>Metronic v5.x</td>
	<td>Metronic v5.x</td>
	<td>Metronic v4.6.x</td>
	<td>Metronic v4.6.x</td>
</tr>
	<tr>
	<td>ORM</td>
	<td>EF Core</td>
	<td>EF Core</td>
	<td>EF 6.x</td>
	<td>EF 6.x</td>
	</tr>
<tr>
	<td>Xamarin Application</td>
	<td>OK</td>
	<td>OK</td>
	<td>-</td>
	<td>-</td>
</tr>
<tr>
	<td>Power Tools (Rapid Application Development Tool)</td>
	<td>OK</td>
	<td>OK</td>
	<td>-</td>
	<td>-</td>
</tr>
<tr>
	<td style="height: 37px">Tenant Subscription Management &amp; Paypal Integration</td>
	<td style="height: 37px">OK</td>
	<td style="height: 37px">OK</td>
	<td style="height: 37px">-</td>
	<td style="height: 37px">-</td>
</tr>
<tr>
	<td>Host Statistics Dashboard</td>
	<td>OK</td>
	<td>OK</td>
	<td>-</td>
	<td>-</td>
</tr>
<tr>
	<td>Identity Server Integration</td>
	<td>OK</td>
	<td>OK</td>
	<td>-</td>
	<td>-</td>
</tr>
<tr>
	<td>Social Logins (Facebook, Twitter, Microsoft, Google+)</td>
	<td>OK (Facebook, Google)</td>
	<td>OK (all)</td>
	<td>OK (all)</td>
	<td>OK (all)</td>
</tr>
<tr>
	<td>Two Factor Auth</td>
	<td>SMS, Email, Google Auth</td>
	<td>SMS, Email, Google Auth</td>
	<td>SMS, Email</td>
	<td>SMS, Email</td>
</tr>
<tr>
	<td>Application Setup Screen</td>
	<td>OK</td>
	<td>OK</td>
	<td>-</td>
	<td>-</td>
</tr>
</tbody>
</table>

<p>See <strong>development guide</strong> documents for details of all features 
in different versions:</p>
<ul>
	<li><a href="https://docs.aspnetzero.com/documents/aspnet-core-mvc/latest/Features-Mvc-Core">ASP.NET Core &amp; jQuery</a></li>
	<li><a href="https://docs.aspnetzero.com/documents/aspnet-core-angular/latest/Features-Angular">ASP.NET Core &amp; Angular</a></li>
	<li><a href="https://docs.aspnetzero.com/documents/aspnet-mvc-angularjs/latest/Development-Guide-Mvc-Angularjs">ASP.NET MVC 5.x &amp; jQuery</a></li>
	<li><a href="https://docs.aspnetzero.com/documents/aspnet-mvc-angularjs/latest/Development-Guide-Mvc-Angularjs">ASP.NET MVC 5.x &amp; Angularjs 1.x</a></li>
</ul>
</body>

</html>