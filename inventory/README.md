OJBJECTIVE:

<ol>
<li> Creat a source in S3 that can store inventory information. </li>

<li> Create Inventory Repository</li>

  <ul>
    <li>Lambda function that creates an inventory file in S3.  </li>
      --  Why S3:  Need something that will pass the IT Security standards.  Launching an RDS instance or managing causes to much overhead
      -- Define what file format will be used to read inventory
    -  Create Lambda function that updates existing file
  </ul>

<li> Create method to read the inventory Repository </li>

    -  Create an Json capability that APi platform can read.
       --  Leverage API Gateway for published service.

</ol>
