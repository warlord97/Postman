# Postman

Approach:
1) Imported Impledge_QA_Exercise.postman_collection.json attached collection to Postman application.
2) Renamed the collection from Impledge_QA_Exercise to Impledge_QA_Shubham_Yadav.
3) Fixed Failing Test Cases: the test cases were getting failed beacuse in request.body the zip was not passed, after passing the zip: "06810" both the test cases passed.
4) Then Added a new request(Fetching Shipment) to this collection to fetch details of ShipmentId:shp_e0b570fd1d7d4b62bd206917eae5881a by finding the end point of the shipment api from easypost.com.
5) And added two test cases for this new request(Fetching Shipment) 1st case was to Verify selected_rate.retail_rate is equal to 12 and 2nd case was to Verify retail_rate is greater than list_rate. 
