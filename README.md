# phpinfofinder
This YAML template defines a scanner called phpinfo-finder, which checks for the presence of a phpinfo() endpoint on the web application being tested. The scanner makes HTTP requests to common paths where a phpinfo() file might be located, and uses a matcher to look for the presence of the string phpinfo(). The filter ensures that the response status is 200 OK.

You can customize this template to fit your specific use case by modifying the path list or the matchers section to include additional patterns that may indicate the presence of a phpinfo() file.
