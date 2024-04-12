# bankSimulator
<div></div>
It is a tool made for the VON to destroy the E-Commerce Space. 
<div></div><div></div>
<h2>Functions</h2>
<h3><b>1. PhotoshopFunctions</b></h3>
<h4><b>[a]. uploadImage(localPath, s3ID, s3Preset, s3BucketName, outputPath, awsRegion) </b> <div></div></h4>
Description: Takes the local JPEG and uploads it to a specific location in the AWS filepath.<div></div>
Parameters: localPath (path to local JPEG), s3ID (synonymous to UUID and the JPEG's name), s3Preset (type of image that needs to be SmartReplaced), s3BucketName (shop name), outputPath (path to AWS s3 Bucket), awsRegion (defaults to "us-east" but specifies AWS region).<div></div>
<h4><b>[b]. downloadImage(s3ID, s3Preset, s3BucketName, outputPath, awsRegion) </b> <div></div></h4>
Description: Downloads from AWS into a local drive. Also, defaults the location to downloads to "static/downloads/..." <div></div>
Parameters: s3ID (synonymous to UUID and the JPEG's name), s3Preset (type of image that needs to be SmartReplaced), s3BucketName (shop name), outputPath (path to AWS s3 Bucket), awsRegion (defaults to "us-east" but specifies AWS region).<div></div>
<h4><b>[c]. replaceSmartObject(s3InputPath, s3ReplacementImagePath, smartObjectLayerName, output_path, input_path, replacement_path, s3BucketName, awsRegion, file_type) </b> <div></div></h4>
Description: Primary function for the Javascript script. Replaces the template image with image through AWS.<div></div>
Parameters: s3InputPath (name of the template), s3ReplacementImagePath (name of the replacing image), output_path (the output location in AWS, defaults to "output/"), input_path (the input location in AWS, defaults to "input/"), replacement_path (the replacement location in AWS, defaults to "replacement/"), s3BucketName (shop name), awsRegion (defaults to "us-east" but specifies AWS region), file_type (defaults to "image/jpeg" but you can choose the type of image you want to output).<div></div>

<h3><b>2. GenerateDetails</b></h3>
<h4><b>[a]. generate_details(shopname, user_input):</b> <div></div></h4>
Description: Takes the general shopname and then generates a title, tag, and description with the user input, which usually involves thematic elements to the products.<div></div>
Parameters: shopname (the shop name), user_input (the type of product with thematic overlay).<div></div>

<h3><b>3. SheetListingFunctions</b></h3>
Will be updated.<div></div>

<h3><b>4. UI Window</b></h3>
Will be updated.<div></div>