# CrawlSitemapXML
## This Jmeter scripts crawl sitemap.xml of any website
To run the Jmeter script, follow below steps

1. create **Scripts** folder under Jmeter folder
2. download and save the file into **Script** folder
3. open command prompt and run below command

  ***jmeter -n -t ..\Scripts\SitemapXML.jmx -Jdomain=<domain_name_value>***

e.g. 

**jmeter -n -t ..\Scripts\SitemapXML.jmx -Jdomain=www.abc.com**

For futher details, please refer blog https://testautomationcookbook.wordpress.com/2019/10/11/how-to-hit-all-urls-of-sitemap-xml-in-jmeter/
