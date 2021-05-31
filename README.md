
(draft) This repository contains some examples from decades of work on intelligent databases going back to the eighties.  I've seen many AI ice-ages come and go, with the periodic winds of hype causing a lot of heat (and mirages).  Code examples and documentation are included in the folders to show the thought processes involved as data science technologies expanded.  From these excursions into the data manscape I have attempted to create a travelogue of the highlights and potential pitfalls of various paths.  I have included these as LESSONS LEARNED, highlighting elements where I went astray, was misled by the hyperboles of the day, or was influenced by other factors (including my own stupidity!).
I hope these can be of help to others in this exciting adventure.  The main lesson learned is that there isn't anything new under the sun.  You don't have to reinvent the wheel if you get a flat, and you can find help in the past.  You can find people thinking about thinking about the world back to Aristotle.  The latest fad (like pop) music isn't necessarily the best or most sophisticated.


I started out in the pre-windows, pre-mac era using dBaseIII and Clipper as my data engines and applying AI techniques to them.  Expert systems, intelligent from ends and natural language query engines were at the fore.  I used VP-Expert extensively, as well as NeuroShell.  They were a forward and backward chaining rule system, and a back-propagation framwork, respectively.  The first two programming languages I bought for my 512k IBM 8086 XT were Texas Instrument Scheme and Turbo Prolog.  For frameworks I used the Borland suite of Turbo tools until their demise.  But to be honest, I was glad to leave the bloated CF++ corpus behind.  Likewise the successor Java, which I think followed the same gluttonous route of glomming on the excess.  The leaness of modern functional approaches, the languages that ride on top the JVM like Scala and Clojure, plus now the rise of Julia all are great advancements.  Although, to be a grumpy old boomer, I think the latest AI hype is being made by many script-kiddies playing around with Pythion libraries and just twiddling with parameters that they don't have the math background to appreciate.  

Object oriented programming hit a wall because everything is not a noun, likewise not every AI/ML problem is best solved with bigger data sets and more layers.

The project folders are:

Deep Tunnel.  This contains notes on the work I did on the Milwaukee Deep Tunnel project for a combined sewer water abatement program.  One of the main tunnels went into a time-and -materials phase with subsequent over-payements to contractors.  Their billing information was mainly Lotus spreadsheets detailing costs per month.  The other data required to analyze this were PERT/GANTT project schedules, contracts, the epertise of engineering consultants, inspector reports.  I created a semantic-model of what project costs were acceptable and what elements were over-billed.  This involved an autmated cost-coding system that binned costs into appropriate areas such as machinery, labor and compared them to what was specified in the project schedule.  The main system was written in Clipper 5.0 (with its new object based system,  Level 5 Object)

Environmnental Concepts Incorporated.

Electric Power Research Institute.

WEA Trust Patee-Provider Matching and ETL

Wisconsin Department of Health and Social Services,  Juvenile Offenders Social Worker Reporting System.



