# How to display dynamic data within the ASPxGridView (Live Data) without full grid updating using the ASPxCallback control


<p>This example demonstrates how to implement live data grid updating without refreshing the entire grid. This approach is useful if it is necessary to update only some ASPxGridView columns.</p><br />
<p>I have used the <a href="http://documentation.devexpress.com/#AspNet/CustomDocument3664"><u>ASPxCallback</u></a> control to send a callback to the server. On the server side, data for all currently displayed live data columns is written to the callback result. Then, in the client-side <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxCallbackScriptsASPxClientCallback_CallbackCompletetopic"><u>ASPxClientCallback.CallbackComplete</u></a> event handler, ASPxGridView cells are filled with data obtained from the server. I have used the <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxGridViewGridViewDataColumn_DataItemTemplatetopic"><u>DataItemTemplate</u></a> with the <a href="http://documentation.devexpress.com/#AspNet/CustomDocument11590"><u>ASPxLabel</u></a> control in live data columns to update cell data on the client side.</p><p><br />
<strong>See also:</strong><br />
<a href="http://demos.devexpress.com/ASPxGridViewDemos/DataBinding/Live.aspx"><u>ASPxGridView - Data Binding - Live Data demo</u></a></p>

<br/>


