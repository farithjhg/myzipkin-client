# myzipkin-client

How to test it?

http://localhost:8002/zipkin-client/customer/100/vehicledetails
http://localhost:8002/zipkin-client/customer/101/vehicledetails
http://localhost:8002/zipkin-client/customer/102/vehicledetails

About the traces:

this.tracer.addTag("customerid", cid.toString());
			
s.logEvent("DB query started");

...

s.logEvent("DB query completed");
