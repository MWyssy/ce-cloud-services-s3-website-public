## Which AWS service might you use to create your own domain name? Something more memorable and shorter

    - Route 53 can be used as a DNS service to register a domain name, and route traffic.

## When using that service what will you need to configure in order to "point" it at your S3 bucket website?

    - To point Route 53 to a website hosted in an S3 bucket, you need to create a new record in the hosted zone containing the domain name you want to use. In the record we need to specify the following values: Routing Policy, Record Name (Domain Name), Alias (Alias to S3 website endpoint), Record Type (IPv4 address), and the default value of 'Yes' for the Evaluate Target Health value.
