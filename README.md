# Annie Community Edition - Project documentation

## What is Annie?

Annie is a chatbot that nudges students at the right times to offer them help, lowering the threshold to ask and receive support. When the barriers to learning are removed, students feel better and their studies proceed.

## What does the Community Edition mean?

Community Edition of Annie was created in collaboration between Annie Advisor Ltd and Association of Finnish Local and Regional Authorities. The team behind Annie Advisor [won an innovation challenge competition](https://klash.fi/opiskelijoiden-tueksi-kehitetty-annie-chatbot-on-saanut-hyvaa-palautetta-vantaan-variassa/) organized by Finnish Local and Regional Authorities. After the competition, Annie Advisor Ltd and Association of Finnish Local and Regional Authorities signed a deal to co-develop and pilot the solution with two education providers (City of Vantaa and Raisio Regional Education and Training Consortium, Raseko) as well as publish a Community Edition of Annie Chatbot with an open licence (CC BY-NC-SA).

Read the announcement (available in Finnish and in Swedish):

[Kuntaliiton Klash-kilpailun ratkaisu Annie Advisor tukee nuoria opintopolullaan](https://www.kuntaliitto.fi/ajankohtaista/2020/kuntaliiton-klash-kilpailun-ratkaisu-annie-advisor-tukee-nuoria-opintopolullaan)

[Annie Advisor, vinnare i Kommunförbundets Klash-tävling, stöder unga längs studievägen](https://www.kommunforbundet.fi/aktuellt/2020/annie-advisor-vinnare-i-kommunforbundets-klash-tavling-stoder-unga-langs-studievagen)

## This documentation

This documentation includes all public deliverables of the Nuoret Opintopolulle -project available for public reuse under the CC BY-NC-SA license.
This documentation is unfortunately only available in Finnish, for the purposes of the Nuoret Opintopolulle -project.

The documentation consist of the following parts:
- The architecture and the solution documentation
- Press releases and publications
- Steering group memorandums
- The source code (see section below)

## Where can I find the source code?

The Annie source code consists of two repositories:

[Annie UI](https://github.com/Annie-Advisor/Annie-API-CE) consists of two React web applications, one for managing the system (Annie Admin) and one for support professionals to receive students' support requests (Annie App).

[Annie API](https://github.com/Annie-Advisor/Annie-API-CE) is the backend of Annie, consisting of database (Annie DB) and an application programming interface (Annie API).

Please note that full deployment of the Annie chatbot requires also external components, such as an SMS gateway. [Contact the development team for more details](https://www.annieadvisor.com/en/contact-us)

## How to use the Annie API?

[Full documention of Annie API is available at SwaggerHub](https://app.swaggerhub.com/apis-docs/annie-advisor/annie-api/2.4.4#/)

## Is there a demo available?

Absolutely! [Demo version](https://demo.annieadvisor.com) of Annie is available for you to test. [Drop us a message](https://www.annieadvisor.com/en/contact-us) and we'll provide you with the demo credentials. 

