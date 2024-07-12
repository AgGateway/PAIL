# Precision Ag Irrigation Language

The files on this repo represent a reference implementation for a schema for S632 (ISO 7673) standards. They are distributed for reference purposes and will be superseded. 

Technology has come a long way in helping growers irrigate their land in smarter ways. Producers can invest in soil mapping, install various types of pumping plants and flow meters, use soil sensors, put a VSI (Variable Speed Irrigation) or VRI (Variable Rate Irrigation) system on center pivots, and tie these together through a few software applications. However, none of these tools actually talk effectively or efficiently to each other. This lack of integration remains a key barrier to the use of precision irrigation technologies. Precision irrigation relies upon the capture and analysis of multiple sets of data from various sensors and databases. The purpose of the PAIL (Precision Agriculture Irrigation Language) project is to enable this communication by providing a common set of data standards. These standards will represent weather, soil moisture, irrigation system and other relevant data, currently stored in a variety of Original Equipment Manufacturer (OEM) formats, in an industry-wide format that can be used by irrigation data analysis and prescription programs. The PAIL data standards exist to support integrated irrigation solutions by making it easier to request and receive relevant data from a variety of equipment, manufacturers and data servers.


## XML Schemas

At present, there are two XSD schemas available.

PAIL_Common_023.xsd This schema contains the basic data classes and definitions used throughout the PAIL (ISO 7673) standard.

PAIL_Ops_029.xsd This schema contains the classes and definitions specific to irrigation operations 

There is also a prototype JSON schema ...
## Examples

Ops-Example-1.1.xml  
Ops-Example-2.1.xml  
Ops-Example-3.1.xml  
Ops-Example-4.1.xml  
Ops-Example-5.1-Chemigation (polygon).xml  
Ops-Example-5.1-Chemigation.xml  
Ops-Example-8.1-Drip.xml  

## External Links

- [AgGateway](https://github.com/AgGateway/PAIL/blob/main/aggateway.org)
- [AgGateway Public PAIL portal](https://github.com/AgGateway/PAIL/blob/main)
- [AgGateway PAIL Wiki (you must be an AgGateway member to access this wiki)](https://aggateway.atlassian.net/wiki/spaces/PAIL/overview)
- [PAIL Flyer](https://s3.amazonaws.com/aggateway_public/AgGatewayWeb/News/CommunicationsKit/AgGatewayPAIL_72219.pdf)
- [ASABE S632-1](https://elibrary.asabe.org/abstract.asp?aid=49749&t=3&dabs=Y&redir=&redirType=) [ASABE S632-3](https://elibrary.asabe.org/abstract.asp?aid=49803&t=3&dabs=Y&redir=&redirType=)
- [ISO 7673-1](https://www.iso.org/standard/83602.html), [ISO 7673-2](https://www.iso.org/standard/83600.html), [ISO 7673-3](https://www.iso.org/standard/83601.html)


## Value Proposition for Participating Companies
There are three main advantages for vendors who adopt the PAIL data standards:
1. Financial Benefits: By reducing the time and effort currently required of growers to interact with multiple vendor products, vendors increase the likelihood of purchase of their irrigation products and services by removing the barrier to growers of having to learn multiple data systems.
2. Technological Benefits: Vendors can enable their equipment or software to interact with an irrigation application without having to rewrite specific code every time a partner’s software program or application is changed.
3. New Market Opportunities: Working in partnership or in short-term alliances, vendors can create new market opportunities with data-driven products and services.
## Value Proposition for Growers
Growers are inundated with many types of data. Common themes the PAIL Team has heard:
- Growers spend too much time trying to sort through data that comes to them through different portals or websites
- Each piece of farm equipment not only sends its own data, but does so in a different format, through its own data portal
- User interfaces vary, and many are difficult to understand
- The issues above hamper the conversion of data to meaningful, actionable information
- Using a mixed fleet (different brands) of equipment compounds the issues above
### For growers who want to improve their irrigation practices:
- Irrigation systems that use the PAIL data standards will provide them more accurate and precise data because their irrigation equipment will be able to exchange data with Farm Management Information Systems.
- Growers will no longer have to consult with a third party just to integrate all of the data from different in-field irrigation equipment.
- Systems that use the PAIL data standards making efficient practices more understandable, and simplify the way data is “moved around the web.
## Benefits and features
### As an Ag Irrigation Equipment and Service Provider, I want to help my customers:
* Get the best data for making irrigation decisions without jumping through hoops
* Plan and track their irrigation efficiency so they can use less water while improving yield
### As an Ag Irrigation Equipment and Service Provider, I want to help my team to:
* Spend less time rewriting code every time a partner’s software program or application is changed.
* Interact with other manufacturers, increasing our market reach
