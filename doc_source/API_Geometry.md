# Geometry<a name="API_Geometry"></a>

Information about where text detected by [DetectText](API_DetectText.md) is located on an image\.

## Contents<a name="API_Geometry_Contents"></a>

 **BoundingBox**   
An axis\-aligned coarse representation of the detected text's location on the image\.  
Type: [BoundingBox](API_BoundingBox.md) object  
Required: No

 **Polygon**   
Within the bounding box, a fine\-grained polygon around the detected text\.  
Type: Array of [Point](API_Point.md) objects  
Required: No

## See Also<a name="API_Geometry_SeeAlso"></a>

For more information about using this API in one of the language\-specific AWS SDKs, see the following:

+  [AWS SDK for C\+\+](http://docs.aws.amazon.com/goto/SdkForCpp/rekognition-2016-06-27/Geometry) 

+  [AWS SDK for Go](http://docs.aws.amazon.com/goto/SdkForGoV1/rekognition-2016-06-27/Geometry) 

+  [AWS SDK for Java](http://docs.aws.amazon.com/goto/SdkForJava/rekognition-2016-06-27/Geometry) 

+  [AWS SDK for Ruby V2](http://docs.aws.amazon.com/goto/SdkForRubyV2/rekognition-2016-06-27/Geometry) 