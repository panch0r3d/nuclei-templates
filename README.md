# nuclei-templates

Custom template files for https://github.com/projectdiscovery/nuclei

  * developer_notes.yaml - Because devs love to comment stuff they shouldn't
  * header_user_id.yaml - Looking for usernames in the response headers
  * api_endpoints.yaml - Common api endpoints for some quick info disclosure
  * shell_scripts.yaml - Some common shell scripts
  * header_sqli.yaml - Try to trigger some SQL errors through extra SQL in the headers
  * graphql_get.yaml - Get based graphql because I think the current POST based one misses a lot
  * artifactory_deploy.yaml - Artifactory repositories with anonymous deploy user permissions
  * header_reflection.yaml - Looks for request headers that are reflected back in the response headers 
  * header_reflection_body.yaml - Looks for request headers that are reflected back in the html body
  
Please use responsibly :) and I'd love to know if you have any luck getting bounties with these or if you have any feedback / requests.

