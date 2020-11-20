# nuclei-templates

Custom template files for https://github.com/projectdiscovery/nuclei

  * developer_notes.yaml - Because devs love to comment stuff they shouldn't
  * header_user_id.yaml - Looking for usernames in the response headers
  * api_endpoints.yaml - Common api endpoints for some quick info disclosure
  * shell_scripts.yaml - Some common shell scripts
  * header_sqli.yaml - Try to trigger some SQL errors through extra SQL in the headers
  * graphql_get.yaml - Get based graphql because I think the current POST based one misses a lot
  * artifactory_deploy.yaml - Artifactory repositories with anonymous deploy user permissions
  * header_reflection.yaml - Looks for request headers that are reflected back in the response headers (Updated Nov-18-2020)
  * header_reflection_body.yaml - Looks for request headers that are reflected back in the html body (Updated Nov-18-2020)
  * base64_strings.yaml - Extracts base 64 encoded strings from the url source (I need to find an easy way to decode it now)
  * AEM_misconfig.yaml - Some vulnerable paths I've had luck with on older unpatched Adobe Experience Maker (AEM) sites 
  
Please use responsibly :) and I'd love to know if you have any luck getting bounties with these or if you have any feedback / requests.

