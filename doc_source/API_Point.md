# Point<a name="API_Point"></a>

The X and Y coordinates of a point on an image\. The X and Y values returned are ratios of the overall image size\. For example, if the input image is 700x200 and the operation returns X=0\.5 and Y=0\.25, then the point is at the \(350,50\) pixel coordinate on the image\.

An array of `Point` objects, `Polygon`, is returned by [DetectText](API_DetectText.md)\. `Polygon` represents a fine\-grained polygon around detected text\. For more information, see [Geometry](API_Geometry.md)\. 

## Contents<a name="API_Point_Contents"></a>

 **X**   
The value of the X coordinate for a point on a `Polygon`\.  
Type: Float  
Required: No

 **Y**   
The value of the Y coordinate for a point on a `Polygon`\.  
Type: Float  
Required: No

## See Also<a name="API_Point_SeeAlso"></a>

For more information about using this API in one of the language\-specific AWS SDKs, see the following:

+  [AWS SDK for C\+\+](http://docs.aws.amazon.com/goto/SdkForCpp/rekognition-2016-06-27/Point) 

+  [AWS SDK for Go](http://docs.aws.amazon.com/goto/SdkForGoV1/rekognition-2016-06-27/Point) 

+  [AWS SDK for Java](http://docs.aws.amazon.com/goto/SdkForJava/rekognition-2016-06-27/Point) 

+  [AWS SDK for Ruby V2](http://docs.aws.amazon.com/goto/SdkForRubyV2/rekognition-2016-06-27/Point) 