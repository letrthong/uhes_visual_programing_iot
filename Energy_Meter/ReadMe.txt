https://www.aranacorp.com/power-measurement-with-arduino-and-ina219/
https://learn.microsoft.com/en-us/dotnet/api/iot.device.adc.ina219?view=iot-dotnet-latest


https://learn.microsoft.com/en-us/dotnet/api/iot.device.adc.ina219?view=iot-dotnet-latest

function get_product(product_id){
    bodyObject = {
        "productId" : product_id
    }
   return post_method_user(bodyObject, "/api/v1/info/retail/product/get");
}


retail_get_product(email, request_body_json)