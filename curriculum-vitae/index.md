---
layout: default
title: Curriculum Vitae
---

### Curriculum Vitae

|         |    |
| ------------- |-------------|
| **Name**    | drs. B. (Benjamin) Wegman | 
| **Address** | Lambrecht van Dalelaan 33, 2015 ER Haarlem, The Netherlands | 
| **Born**    | 31 March 1978 | 
| **Phone**   | +31 651 154 155 | 
| **Email**   | wegman@shader.nl | 

#### Contract work

##### RDC inMotiv Nederland BV (2011 - 2013)

Implementing the [ROB Next](http://www.rob-net.nl) system. ROB Next is a transaction system for handling all repair, maintenance and tire activities surrounding leased vehicles (cars, trucks, trailers and motors). It has replaced a previous version of the system.

Primary goal for the new system is to allow for more flexibility, scalibility and better interoperability. We realised this by implementing a publish/subscribe service bus architecture and separating all components of the system.

During the two year development period we used an incremental delivery strategy to minimize operational risk. Four releases have been made into production with minimal downtime for the users. The biggest hurdle for this phased migration to work was to have both the old system and the new system co-exist. 

The co-existence was realised by creating a special translation and interface component that marshalled data from the old system into the new system (and vice-versa) using its messaging infrastructure. With neither system being aware that the other existed this allowed for continued development of the new system, minimal changes in the old system and getting the new system production-ready faster and with reduced risk.

The ROB Next system is used daily by 7000+ users and processes 2.8M+ (&euro; 500M+) requests anually.

* C#, ASP.NET MVC4, [MassTransit](https://github.com/MassTransit/MassTransit), [SignalR](https://github.com/signalR/SignalR), SQL Server 2008 R2
* Lead developer, lead architect, SCRUM master.

##### Crossing Channels (2008 - 2010)

##### Electrolux Home Group Sweden (2009)

##### Electrolux Home Products BV (2007 - 2008)

##### United Retail BV (2004 - 2007)



#### Contributions

Contributor to [SignalR](https://github.com/signalR/SignalR) and [MassTransit](https://github.com/MassTransit/MassTransit).

#### Knowledge

|Area|Level|
|----|-----|
|C# 5|+++|
|ASP.NET MVC|+++|
|SignalR|+++|
|LLBLGen|+++|
|JavaScript|+++|
|TFS|+++|
|Git|+++|

#### Education

##### Vrije Universiteit - Amsterdam (1996 - 2002)
* Distributed systems (MSc)

##### Hermann Wesselink College - Amstelveen (1990 - 1996)
* VWO

#### Languages

* **Nederlands** &mdash; fluent in speech and writing
* **English** &mdash; fluent in speech and writing

#### Company

Since 1996 owner of Shader BV, a small company in The Netherlands focused on increasing the business value of IT systems.
