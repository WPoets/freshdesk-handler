# freshdesk-handler
Simple php wrapper for calling freshdesk v2 API in Awesome Enterprise

here is how to call the this

[freshdesk_api.call method='POST' api_key='{template.api_key}' domain='{template.domain}' url_segment='tickets' data='{template.data}' o.set='template.api_response' /] 

here url_segment is the API endpoint you want to call.
