---
layout: default
title: Curriculum Vitae
---

## Curriculum Vitae

|         |    |
| ------------- |-------------|
| **Name**    | drs. B. (Benjamin) Wegman |
| **Address** | Lambrecht van Dalelaan 33, 2015 ER Haarlem, The Netherlands |
| **Born**    | 31 March 1978 |
| **Phone**   | +31 651 154 155 |
| **Email**   | wegman@shader.nl |

### Contract work

#### Vereniging ROB / RDC inMotiv Nederland BV (2013 - )

Implementing phase 2 of the [ROB Net](http://www.rob-net.nl) project.

* C#, ASP.NET MVC4, [MassTransit](https://github.com/MassTransit/MassTransit), [SignalR](https://github.com/signalR/SignalR), WCF, SQL Server
* Lead developer, lead architect, SCRUM master

#### RDC inMotiv Nederland BV (2011 - 2013)

Implemented the new [ROB Net](http://www.rob-net.nl) system. ROB Net is a transaction system for handling all repair, maintenance and tire activities for leased vehicles (cars, trucks, trailers and motorcycles). It replaced a previous version of the system.

The primary goal for the new system is to allow for more flexibility, scalability and improved interoperability. We realised this goal by implementing a publish/subscribe service bus architecture and separating all components of the system. We were able to quickly scale out the system, add multiple external connections to other system and have better insight insight into the performance of the system.

During the two year development cycle we used an incremental delivery strategy to minimize operational risk. Four major production releases were made with minimal downtime for the users. The biggest hurdle for this phased migration to work was to have both the old system and the new system co-exist.

The co-existence was realised by creating a special translation and interface component that marshalled data from the old system into the new system and vice-versa using the messaging infrastructure. With neither system being aware that the other existed this allowed for continued development of the new system, minimal changes in the old system and getting the new system production-ready faster and with reduced risk.

The ROB Net system is used daily by 7000+ users and processes 2.8M+ (&euro; 500M+) requests anually.

* C#, ASP.NET MVC4, [MassTransit](https://github.com/MassTransit/MassTransit), [SignalR](https://github.com/signalR/SignalR), WCF, SQL Server
* Lead developer, lead architect, SCRUM master

#### Crossing Channels (2008 - 2010)

Worked on projects for [SGC](http://www.degeschillencommissie.nl/home), [Kuoni](http://www.kuoni.nl), [Rode Kruis](http://www.rodekruis.nl) and [VUMC](http://www.vumc.nl).

* C#, ASP.NET WebForms, LLBLGen, SQL Server
* Senior developer

##### Large bank/mortgage broker in the Netherlands

Integration of an investment back-end with a new web-based mortgage system. Responsible for technical design and client communication.

* C#, ASP.NET WebForms, WCF, SQL Server
* Senior developer, integration architect

#### Electrolux Home Products BV (2007 - 2008)

Implementing the websites [mijnapparaten.nl](http://mijnapparaten.nl) and [mijnservice.nl](http://mijnservice.nl) supporting the after-sales of the AEG, Electrolux and Zanussi brands in The Netherlands.

The sites allow both consumers and retailers to have direct access to the planning systems of the Electrolux after-sales organization. This allows them to make appointments and get technical information on the appliances.

* C#, ASP.NET WebForms, DotNetNuke, LLBLGen

#### United Retail BV (2004 - 2007)

The largest home appliance franchise retail organizations in The Netherlands.

##### UniFact Backoffice

Implementing the central invoice processing system. All invoices from product suppliers (both producers and wholesalers) for each of the 500+ retailers is processed with this system. Its key component is the invoice validation routine which uses information on all available products (price, discounts, taxes etc.) and checks if the invoice is correct.

A large amount of the invoices is processed using EDIFact. The transfer from manual entry to EDI has allowed for a dramatic cost reduction.

##### UniFact Frontoffice

Implementing systems for internal and external communication. All information regarding products, prices and bonusses is communicated using this system to all franchisers.

* C#, WinForms, SQL Server replication
* Lead developer, lead architect, product owner

### Contributions

Contributor to [SignalR](https://github.com/signalR/SignalR) and [MassTransit](https://github.com/MassTransit/MassTransit).

### Knowledge

|Area|Level|
|----|-----|
|C# 5|+++|
|ASP.NET MVC|+++|
|SignalR|+++|
|LLBLGen|+++|
|JavaScript|+++|
|CSS|+++|
|Microsoft SQL Server|+++|
|TFS|+++|
|Git|+++|

### Education

#### Vrije Universiteit - Amsterdam (1996 - 2002)
* Distributed systems (MSc)

#### Hermann Wesselink College - Amstelveen (1990 - 1996)
* VWO

### Languages

* **Nederlands** &mdash; fluent in speech and writing
* **English** &mdash; fluent in speech and writing

### Company

Since 1996 owner of Shader BV, a small company in The Netherlands focused on increasing the business value of IT systems.
