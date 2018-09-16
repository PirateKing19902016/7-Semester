# UNIT 3

# AGGREGATE PRODUCTION PLANNING AND THE MASTER PRODUCTION SCHEDULE

 - Aggregate planning is a high-level corporate planning activity. The aggregate production plan indicates production output levels for the major product lines of the company.


![u133](/CIM/Notes/src/u133.png)

<center><strong>Figure:  - Activities in a PPC system

 - The aggregate plan must be coordinated with the plans of the sales and marketing departments. Because the aggregate production plan includes products that are currently in production, it must also consider the present and future inventory levels of those products and their component parts. Because new products currently being developed will also be included in the aggregate plan. the marketing plans and promotions for current products and new products must be reconciled against the total capacity resources available to the company.

# MASTER PRODUCTION SCHEDULE (MPS)

 - The production quantities of the major product lines listed in the aggregate plan must he converted into a very specific schedule of individual products, known as the master production schedule (MPS). It is a list or the products to be manufactured, when they should be completed and delivered, and in what quantities. The master schedule must be based on an accurate estimate of demand and a realistic assessment of the company's production capacity. The MPS planning period, or horizon, can be of any length, but should be at least as long as a company’s longest cumulative lead time (the time it takes to complete a product from raw material to finished goods.). Many systems include a rough cut capacity planning (RCCP) capability, which compares certain MPS items of the master schedule to specified key resources of the plant (or multiple plants) to determine if the master schedule is workable, given current the plant capacity. If the master schedule is not achievable, the system modifies the MPS or the production plan (For example, reduce the amount of products to be produced or commit to increasing the capacity of the plant) until the master schedule is achievable.


![u134](/CIM/Notes/src/u134.png)

<center><strong>Figure:  - Modules of Master Scheduling

 - Master production schedule provides great flexibility in reflecting the overall production plans of management, allowing planned production to be based on predicted demand.

 - The master production schedule software is useful in many ways.

  - Enables the user to scan through the file starting at any point to easily locate data.

  - Accesses items by number or partial description.

  - Eases forecasting.

  - Allows interactive entry of requirement and replenishment orders on the master schedule including creation of firm planned orders.

  - Merges existing shop orders, purchase orders, and MRP planned orders into the master schedule for easy comparison with customer orders and sales forecast orders.

  - Maintains orders by exact date, allowing reports to be detailed or summarizes into a variety of user-defined periods.

  - Supports “what if” analysis by projecting into the future with adjustments to quantities.

  - Displays or prints how much of each inventory item is available to promise for delivery in current and future periods.

  - Identifies under or over-scheduled key work centres though rough cut capacity planning.

  - Pinpoints desired information responding to user-specified parameters.

# Material Requirements Planning (MRP)

 - Material Requirements Planning (MRP) is a computer-based production planning and inventory control system. MRP is concerned with both production scheduling and inventory control. It is a material control system that attempts to keep adequate inventory levels to assure that required materials are available when needed. MRP is applicable in situations of multiple items with complex bills of materials. MRP is not useful for job shops or for continuous processes that are tightly linked.

 - The major objectives of an MRP system are to simultaneously:

 1. Ensure the availability of materials, components, and products for planned production and for customer delivery,

 2. Maintain the lowest possible level of inventory,

 3. Plan manufacturing activities, delivery schedules, and purchasing activities.

 - MRP is especially suited to manufacturing settings where the demand of many of the components and subassemblies depend on the demands of items that face external demands. Demand for end items is independent. In contrast, demand for components used to manufacture end items depend on the demands for the end items. The distinctions between independent and dependent demands are important in classifying inventory items and in developing systems to manage items within each demand classification. MRP systems were developed to cope better with dependent demand items.

 - The three major inputs of an MRP system are the master production schedule, the product structure records, and the inventory status records. Without these basic inputs the MRP system cannot function. The demand for end items is scheduled over a number of time periods and recorded on a

 - Master production schedule (MPS). The master production schedule expresses how much of each item is wanted and when it is wanted. The MPS is developed from forecasts and firm customer orders for end items, safety stock requirements, and internal orders. MRP takes the master schedule for end items and translates it into individual time-phased component requirements. The product structure records, also known as bill of material records (BOM), contain information on every item or assembly required to produce end items. Information on each item, such as part number, description, quantity per assembly, next higher assembly, lead times, and quantity per end item, must be available. The inventory status records contain the status of all items in inventory, including on hand inventory and scheduled receipts. These records must be kept up to date, with each receipt, disbursement, or withdrawal documented to maintain record integrity.

 - MRP will determine from the master production schedule and the product structure records the gross component requirements; the gross component requirements will be reduced by the available inventory as indicated in the inventory status records.

# MRP Computations

 - We will illustrate MRP computations through examples.

# Example

 - Suppose you need to produce 100 units of product A eight week from now, where product A requires one unit of product B and two units of product C, while product C requires one unit of product D and two units of product E. How many units of each type do you need? In this example it is easy to compute the requirements of each item to produce 100 units of product A:

 - Req (B)  =  100,

 - Req (C)  =  200,

 - Req (D)  =  200,

 - Req (E)   =  400.

 - Suppose further that the lead-times for the products are as follows:

  - Product A, four weeks, product B three weeks, product C two weeks, products D and E one week each. Since the production lead-time for product A is four weeks, we must have products B and C available at the end of week four. Since product B has a lead time of three weeks, we need to release the production of product B by the end of the first week. Similarly, product C need to be released for production at the end of week two, while products D and E must be released for production at the end of week one A material requirements plan has been developed for product A based on the product structure of A and the lead-time needed to obtain each component. Planned order releases of a parent item are used to determine gross requirements for its component items. Planned order release dates are simply obtained by offsetting the lead times.

  - The computations and steps required in the MRP process are not complicated. They involve only simple arithmetic. However, the bill-of-materials explosion must be done with care. What may get complicated is the product structure, particularly when a given component is used in different stages of the production of a finished item.

# The Level of an Item

 - To form a useful bill of material matrix it is convenient to order the items by levels. The level of an item is the maximum number of stages of assembly required to get the item into an end product.

# Example

 - Consider a system with two end items, item 1 and item 2.

 - Item 1 requires two units of item A and one unit of item C.

 - Item 2 requires one unit of item B, one unit of item D and three units of item E.

 - Item A requires one unit of item B and two units of item F.

 - Item B requires two units of item C and one unit of item E.

 - Item C requires one unit of item F and three units of item G.

 - Item D requires two units of item B and one unit of item C.

 - The levels of the items are:

 - Level 0: Items 1 and 2.

 - Level 1: Items A and D.

 - Level 1: Items A and D.

 - Level 3: Items C and E.

 - Level 4: Items F and G.

# An Outline of the MRP Process

 - Starting with end items the MRP process goes through the following steps

 1. Establish gross requirements.

 2. Determine net requirements by subtracting scheduled receipts and on hand inventory from the gross requirements

 3. Time phase the net requirements.

 4. Determined the planned order releases


![u135](/CIM/Notes/src/u135.png)

# MRP Table

 - The planned order releases aggregated over all the end items will result in the gross requirements for level one item, the gross requirements for this items are then netted and time phased to determined their own order releases. The process is continued until all the items have been exploded. Table shows a typical MRP table.

# Example 3

 - MRP computations are shown in Table where the lead-time is two weeks. Here the planned releases were obtained by solving a Wagner-Whitin problem with time-varying demand. More often, however, MRP will plan releases in a lot-by-lot fashion.


![u136](/CIM/Notes/src/u136.png)

# Standard MRP Table

# Shortcomings of MRP

# Capacity

 - MRP expects the lead time to be constant regardless of how much work has been released into the production system, so it is implicitly assuming infinite capacity. This can create problems when production levels are at or near capacity. One way to address this problem is to make sure that the MPS is capacity feasible. Rough-cut capacity planning (RCCP) attempts to do this by checking the capacity of a few critical resources. RCCP makes use of the bill of resources (BOR) for each item on the MPS. The BOR specifies the number of hours required at each critical resource to build a particular end item and its components, and then aggregates the number of hours required at each critical resource over the end items in the MPS. RCCP then checks whether the available resources are enough to cover the MPS on each time bucket. Notice that RCCP does not perform time offsets, so the calculation of the number of hours required has to be done with time buckets that are large enough so that parts and their components can all be completed within a single time bucket. This usually makes RCCP an optimistic estimation of what can be done. Advanced MRP systems provide more detailed capacity analysis proposing alternative production schedules when the current plan is not feasible.

# Long Lead Times

 - There are many pressures to increase planned lead times in an MRP system. MRP uses constant lead times when, in fact, actual lead times vary considerably. To compensate, planners typically choose pessimistic estimates. Long lead times lead to large work-in-process (WIP) inventories.

# Nervousness

 - MRP is typically applied in a rolling horizon basis. As customer orders firm up, and forecasts become better, a new MPS is fed to MRP which produces updated planned order releases that may be very different from the original. Even small changes in the MPS can result in large changes in planned order releases.

# CAPACITY REQUIREMENTS PLANNING (CRP)

 - MRP does not consider available capacity and often formulates production plans not possible within a given specified plant capacity. Capacity Requirements Planning (CRP) takes planned orders from MRP and open (release) shop orders, and translates work orders into hours of work (pre-set standards) on a work centre basis. CRP then, using the cumulative lead times, allocates the work required for each order to the appropriate work centres for the time period that the order will be in that work centre. CRP considers many factors in allocating the load-queue time, move time, machine and many others. In scheduling, CRP can start from current date and schedule the job to completion (forward scheduling) or using the due date for the order, schedule backward to determine the start date of the job (backward scheduling).

 - There are two types of loading in CRP: finite and infinite. With finite loading, CRP considers the total capacity of a work centre and does not load beyond that point. Infinite loading loads all work for the period into the appropriate work centres then produces over and under load reports showing where more or less capacity are needed to efficiently handle the load. Although they may generate suggestions, most MRP systems require human intervention to help balance the capacity and load. A planner can decide whether delaying the order release, subcontracting the job, splitting the job into several smaller jobs, routing through an alternative work centre, or authorizing overtime will best eliminate the over-under load on the work centre and still get the job done on time. Another aspect of CRP is Input/Output control (I/O). I/O control monitors the amount of work going into and coming out of a work centre and compares it to a standard or expected amount. A back log will develop behind any work centre that continually puts out less work than it takes in. CRP and I/O control are good tools for monitoring the shop floor for bottlenecks and unused capacity.


![u137](/CIM/Notes/src/u137.png)

<center><strong>Figure:  - Modules of Capacity Requirement Plan

# The CRP software

  - Allows an unlimited planning horizon with user-defined reporting period lengths

  - Represents the load profile for each work centre.

  - Provides an effective analysis tool to help maximize facility utilization and minimize delays.

  - Gives advance knowledge of potential production bottlenecks so that the user can increase capacity, decrease the load or change the schedule to create a realistic production plan.

  - Monitors both current wok-in-process and planned production concurrently.

  - Displays the schedule load for any work centre.

  - Allows the user to test various “what-if” changes without affecting the “live” date.

  - Uses both forward and backward scheduling techniques around a “bottleneck” operation.

  - Reschedules any number of dependent shop orders when desired.

  - Prints the “work centre load report” with planned load subtotals for each reporting period.

  - Uses work centre efficiency factors in calculating capacity to match runtimes to reality.

  - Pinpoints desired information by accepting user-specified parameters on most reports.

  - Allows reports to be displayed on the screen for immediate inquiry.

# MRP II

 - Manufacturing Resource Planning (MRP II) embeds additional procedures to address the shortcomings of MRP. In addition, MRP II attempts to be an integrated manufacturing system by bringing together other functional areas such as marketing and finance. The additional functions of MRP II include forecasting, demand management, rough-cut capacity planning (RCCP), and capacity requirement planning (CRP), scheduling dispatching rules, and input/output control. MRP II works within a hierarchy that divides planning into long-range planning, medium range planning, and short-term control.

 - To assist planners in tracking some of the problems associated with inventory control, some kind of ‘feedback loop’ is needed in the M.R.P. process, not only to automatically re-schedule certain items (when possible), and avoid excessive manual effort in controlling the process, but to detect and report performance that is ‘out of spec’ (such as a vendor performance report to track on-time delivery performance). This ‘feedback loop’ is the defining factor for an ‘M.R.P. II’ system. Though many systems CLAIM to be an ‘M.R.P. II’ system, few actually fit the mould exactly. Still, with automatic rescheduling capabilities for work orders and/or repetitive build schedules, and ‘reschedule action’ reports for purchase orders and outside contracting, the amount of actual analysis is reduced significantly. Other information, such as vender performance reports and process utilization reports, also help to measure the ‘performance to plan’ capability of the manufacturing plant.

 - Even when the production plan is running at optimum performance, companies still often have serious problems with the manufacturing process. ‘Hidden Cost’ issues associated with manufacturing increase the total cost of manufacturing, but are extremely hard to track. Some of these ‘Hidden Costs’ can be caused by excessive P.O. rescheduling or excessive ‘crash buy’ programs, excess and/or obsolete inventory, or planning problems that cause incorrectly stocked finished goods (too much of one, not enough of the other) that result in shortages. Another ‘hidden cost’ issue might be frequent line stops related to a ‘limiting process’ (such as a wave solder machine or component inserter), as well as material shortages and excessive ‘kitting’ of common components. In addition, potential revenue losses from excessively long customer order lead times, or poor on-time customer delivery performance, are real problems, but very difficult to track and measure. As such, none of these problems are tracked nor reported by any ‘standard M.R.P.’ or ‘M.R.P. II’ system. To help solve these problems, and improve the company’s competitiveness and profitability, beyond existing capabilities, the M.R.P. system must go beyond the standard definition of ‘M.R.P. II’.

 - Manufacturing Resource Planning (MRP II) is defined by APICS (American Production and Inventory Control Society, Estd. 1957) as a method for the effective planning of all resources of a manufacturing company. Ideally, it addresses operational planning in units, financial planning in dollars, and has a simulation capability to answer what-if questions and extension of closed-loop MRP.

 - This is not exclusively a software function, but a marriage of people skills, dedication to data base accuracy, and computer resources. It is a total company management concept for using human resources more productively.

# MRP II is not

 - Many items on this list can be part of an MRP II, but are not solely what it is.

  - A computer system

  - Manufacturing control system

  - Inventory reduction plan Sales and Purchase System

  - Material Management

# Purpose

 - MRP II integrates many areas of the manufacturing enterprise into a single entity for planning and control purposes, from board level to operative and from five-year plan to individual shop-floor operation. It builds on closed-loop Material Requirements Planning (MRP) by adopting the feedback principle but extending it to additional areas of the enterprise, primarily manufacturing-related.

# Key functions and Features

 - MRP II is not a proprietary software system and can thus take many forms. It is almost impossible to visualize an MRP II system that does not use a computer, but an MRP II system can be based on either purchased / licensed or in-house software.

 - Almost every MRP II system is modular in construction. Characteristic basic modules in an MRP II system are:

  - Master Production Scheduling (MPS)

  - Item Master Data (Technical Data)

  - Bill of Materials (BOM) (Technical Data)

  - Production Resources Data (Manufacturing Technical Data)

  - Inventories and Orders (Inventory Control)

  - Purchasing Management

  - Material Requirements Planning (MRP)

  - Shop Floor Control (SFC)

  - Capacity planning or Capacity Requirements Planning (CRP)

  - Standard Costing (Cost Control)

  - Cost Reporting / Management (Cost Control)

  - Distribution Resource Planning (DRP)

 - Together with ancillary systems such as:

  - Business Planning

  - Lot Traceability

  - Contract Management

  - Tool Management

  - Engineering Change Control

  - Configuration Management

  - Shop Floor Data Collection

  - Sales Analysis and Forecasting

  - Finite Capacity Scheduling (FCS)

  - and related systems such as:

  - General Ledger

  - Accounts Payable (Purchase Ledger)

  - Accounts Receivable (Sales Ledger)

  - Sales Order Management

  - Distribution Requirements Planning (DRP)

  - [Automated] Warehouse Management

  - Project Management

  - Technical Records

  - Estimating

  - Computer-aided design/Computer-aided manufacturing (CAD/CAM)

  - CAPP

 - The MRP II system integrates these modules together so that they use common data and freely exchange information, in a model of how a manufacturing enterprise should and can operate. The MRP II approach is therefore very different from the “point solution” approach, where individual systems are deployed to help a company plan, control or manage a specific activity. MRP II is by definition fully integrated or at least fully interfaced.

 - MRP II systems can provide:

  - Better control of inventories

  - Improved scheduling

  - Productive relationships with suppliers

 - For Design / Engineering:

  - Improved design control

  - Better quality and quality control

 - For Financial and Costing:

  - Reduced working capital for inventory

  - Improved cash flow through quicker deliveries

  - Accurate inventory records

  - Timely and valid cost and profitability information

# Industry Specifics

 - MRP II systems have been implemented in most manufacturing industries. Some industries need specialized functions e.g. lot traceability in regulated manufacturing such as pharmaceuticals or food. Other industries can afford to disregard facilities required by others e.g. the tableware industry has few starting materials – mainly clay – and does not need complex materials planning. Capacity planning is the key to success in this as in many industries, and it is in those that MRP II is less appropriate.

 - This is not exclusively a software function, but a marriage of people skills, dedication to data base accuracy, and computer resources. It is a total company management concept for using human resources more productively.

# MRP and MRPII: History and Evolution

 - Material Requirements Planning (MRP) and Manufacturing Resource Planning (MRPII) are predecessors of Enterprise Resource Planning (ERP), a business information integration system. The development of these manufacturing coordination and integration methods and tools made today’s ERP systems possible. Both MRP and MRPII are still widely used, independently and as modules of more comprehensive ERP systems, but the original vision of integrated information systems as we know then today began with the development of MRP and MRPII in manufacturing.

 - The vision for MRP and MRPII was to centralize and integrate business information in a way that would facilitate decision making for production line managers and increase the efficiency of the production line overall. In the 1980s, manufacturers developed systems for calculating the resource requirements of a production run based on sales forecasts. In order to calculate the raw materials needed to produce products and to schedule the purchase of those materials along with the machine and labor time needed, production managers recognized that they would need to use computer and software technology to manage the information. Originally, manufacturing operations built custom software programs that ran on mainframes.

 - Material Requirements Planning (MRP) was an early iteration of the integrated information systems vision. MRP information systems helped managers determine the quantity and timing of raw materials purchases. Information systems that would assist managers with other parts of the manufacturing process, MRPII, followed. While MRP was primarily concerned with materials, MRPII was concerned with the integration of all aspects of the manufacturing process, including materials, finance and human relations.

 - Like today’s ERP systems, MRPII was designed to integrate a lot of information by way of a centralized database. However, the hardware, software, and relational database technology of the 1980s was not advanced enough to provide the speed and capacity to run these systems in real-time, and the cost of these systems was prohibitive for most businesses. Nonetheless, the vision had been established, and shifts in the underlying business processes along with rapid advances in technology led to the more affordable enterprise and application integration systems that big businesses and many medium and smaller businesses use today (Monk and Wagner).

# MRP-I and MRPII: General Concepts

 - Material Requirements Planning (MRP) and Manufacturing Resource Planning (MRPII) are both incremental information integration business process strategies that are implemented using hardware and modular software applications linked to a central database that stores and delivers business data and information.

 - MRP is concerned primarily with manufacturing materials while MRPII is concerned with the coordination of the entire manufacturing production, including materials, finance, and human relations. The goal of MRPII is to provide consistent data to all players in the manufacturing process as the product moves through the production line.

 - Paper-based information systems and non-integrated computer systems that provide paper or disk outputs result in many information errors, including missing data, redundant data, numerical errors that result from being incorrectly keyed into the system, incorrect calculations based on numerical errors, and bad decisions based on incorrect or old data. In addition, some data is unreliable in non-integrated systems because the same data is categorized differently in the individual databases used by different functional areas.

 - MRPII systems begin with MRP, Material Requirements Planning. MRP allows for the input of sales forecasts from sales and marketing. These forecasts determine the raw materials demand. MRP and MRPII systems draw on a Master Production Schedule, the breakdown of specific plans for each product on a line. While MRP allows for the coordination of raw materials purchasing, MRPII facilitates the development of a detailed production schedule that accounts for machine and labor capacity, scheduling the production runs according to the arrival of materials. An MRPII output is a final labor and machine schedule. Data about the cost of production, including machine time, labor time and materials used, as well as final production numbers, is provided from the MRPII system to accounting and finance.

# Just In Time (JIT)

 - Just-in-time manufacturing was a concept introduced to the United States by the Ford motor company. It works on a demand-pull basis, contrary to hitherto used techniques, which worked on a production-push basis. To elaborate further, under just-in-time manufacturing (colloquially referred to as JIT production systems), actual orders dictate what should be manufactured, so that the exact quantity is produced at the exact time that is required. Just-in-time manufacturing goes hand in hand with concepts such as Kanban, continuous improvement and total quality management (TQM). Just-in-time production requires intricate planning in terms of procurement policies and the manufacturing process if its implementation is to be a success

 - Highly advanced technological support systems provide the necessary back-up that Just-in-time manufacturing demands with production scheduling software and electronic data interchange being the most sought after.

# Advantages

 - Following are the advantages of Adopting Just-In-Time Manufacturing Systems

  - Just-in-time manufacturing keeps stock holding costs to a bare minimum. The release of storage space results in better utilization of space and thereby bears a favorable impact on the rent paid and on any insurance premiums that would otherwise need to be made.

  - Just-in-time manufacturing eliminates waste, as out-of-date or expired products; do not enter into this equation at all.

  - As under this technique, only essential stocks are obtained, less working capital is required to finance procurement. Here, a minimum re-order level is set, and only once that mark is reached, fresh stocks are ordered making this a boon to inventory management too.

  - Due to the aforementioned low level of stocks held, the organizations return on investment (referred to as ROI, in management parlance) would generally be high.

  - As just-in-time production works on a demand-pull basis, all goods made would be sold, and thus it incorporates changes in demand with surprising ease. This makes it especially appealing today, where the market demand is volatile and somewhat unpredictable.

  - Just-in-time manufacturing encourages the 'right first time' concept, so that inspection costs and cost of rework is minimized.

  - High quality products and greater efficiency can be derived from following a just-in-time production system.

  - Close relationships are fostered along the production chain under a just-in-time manufacturing system.

  - Constant communication with the customer results in high customer satisfaction.

  - Overproduction is eliminated when just-in-time manufacturing is adopted.

# Disadvantages

 - Following are the disadvantages of Adopting Just-In-Time Manufacturing Systems

  - Just-in-time manufacturing provides zero tolerance for mistakes, as it makes re-working very difficult in practice, as inventory is kept to a bare minimum.

  - There is a high reliance on suppliers, whose performance is generally outside the purview of the manufacturer.

  - Due to there being no buffers for delays, production downtime and line idling can occur which would bear a detrimental effect on finances and on the equilibrium of the production process.

  - The organization would not be able to meet an unexpected increase in orders due to the fact that there are no excess finish goods.

  - Transaction costs would be relatively high as frequent transactions would be made.

  - Just-in-time manufacturing may have certain detrimental effects on the environment due to the frequent deliveries that would result in increased use of transportation, which in turn would consume more fossil fuels.

# Precautions

 - Following are the things to remember When Implementing a Just-In-Time Manufacturing System

  - Management buy-in and support at all levels of the organization are required; if a just-in-time manufacturing system is to be successfully adopted.

  - Adequate resources should be allocated, so as to obtain technologically advanced software that is generally required if a just-in-time system is to be a success.

  - Building a close, trusting relationship with reputed and time-tested suppliers will minimize unexpected delays in the receipt of inventory.

  - Just-in-time manufacturing cannot be adopted overnight. It requires commitment in terms of time and adjustments to corporate culture would be required, as it is starkly different to traditional production processes.

  - The design flow process needs to be redesigned and layouts need to be re-formatted, so as to incorporate just-in-time manufacturing.

  - Lot sizes need to be minimized.

  - Workstation capacity should be balanced whenever possible.

  - Preventive maintenance should be carried out, so as to minimize machine breakdowns.

  - Set-up times should be reduced wherever possible.

  - Quality enhancement programs should be adopted, so that total quality control practices can be adopted.

  - Reduction in lead times and frequent deliveries should be incorporated.

  - Motion waste should be minimized, so the incorporation of conveyor belts might prove to be a good idea when implementing a just-in-time manufacturing system.

# Conclusion

 - Just-in-time manufacturing is a philosophy that has been successfully implemented in many manufacturing organizations.

 - It is an optimal system that reduces inventory whilst being increasingly responsive to customer needs, this is not to say that it is not without its pitfalls.

 - However, these disadvantages can be overcome with a little forethought and a lot of commitment at all levels of the organization.

# ENTERPRISE RESOURCE PLANNING (ERP)

 - Enterprises to-day employ a mixture of several approaches to manufacturing. They include:

  - Make to stock

  - Design to order

  - Make to order

  - Assemble to order

 - It must be possible to operate the company in all these modes. The emerging trend of amalgamations, acquisitions and strategic alliances among competing corporations required more capable software to manage such multi-facility enterprises. Another challenging task is the co-ordination of manufacturing in facilities which are geographically dispersed. For example, a multinational company will have divisions and subsidiaries in U.S.A, Canada, UK, India, Germany, Korea and Japan. An Indian multinational company may have plants in Poland, Belgium and UK. Each country will have its own currency and tax laws. This requires multi currency functionality for the planning software. The need for managing the entire enterprise within a more global, tightly integrated closed-loop solution has led to the evolution of ERP software.

 - The core activity in ERP is the creation of an integrated data model, covering employees, customers, suppliers etc. A distinguishing feature of the ERP software is that it incorporates best practices. This means that the manufacturing solution developed using ERP is an optimum one.

 - The implementation of an ERP system includes the following stages:

 - i. Definition of the scope of the project

 - ii. Identification of the objectives and deliverables

 - iii. Project organization

 - iv. Identifying an executive responsible for successful implementation of ERP

 1. Establish a senior management steering committee

 2. Establish a project team

 3. Define the role of consultants

 4. Work plan developmentv.

 - v. Assessment of the business of the company - where it is to day and where it

 - vi. should go

 - vii. Education of key managers

 - viii. Cost/benefit analysis

# MODULES IN TYPICAL ERP SOFTWARE

 - The important modules in typical ERP software are:

 - i. Finance Module

 - The finance module extracts financial transactions from the sales and manufacturing areas and posts them to the general ledger. The main elements of finance module are:

  - General ledger

  - Accounts payable

  - Accounts receivable

  - Cash management

  - Fixed Assets

  - Financial statement

  - Budget

  - Cost allocation

 - ii. Distribution Module

 - This module manages finished goods, raw materials and services. Sales orders are managed by this module. Inventory control, location control, Distribution Requirements planning and replenishment control are part of distribution module. The business objects of this module are:

  - Item control

  - Cost accounting

  - Purchase control

  - Sales control

  - Sales and marketing information

  - Electronic data interchange

  - Replenishment order control

  - Inventory control

  - Lot control

  - Location control

  - Distribution requirements planning

 - iii. Manufacturing Module

 - This module is designed to control all the operations related to manufacture. The business objectives of this module are:

  - Engineering Data Management

  - Item control

  - Bill of materials

  - Routing

  - Master production schedule

  - Materials requirement planning

  - Capacity requirement planning

  - Repetitive manufacturing

  - Shop floor control

  - Hours accounting

  - Project budget

  - Product configuration and classification

  - Project control

  - Quality management

 - iv. Service Module

  - Service module deals with repair and warranty related activities. The functions

  - of this module are:

  - Installation control

  - Contract control

  - Service order control

  - Service analysis control

 - v. Transportation module

 - The functions of this module are:

  - Employee control

  - Address control

  - Fleet management

  - Fuel control

  - Hours and expense control

  - Transport control

  - Packing control

  - Warehouse control

 - vi. Process Module

 - The process module helps companies to keep track of the manufacture of products.

 - vii. Project Module

 - The project module consists of

  - Estimating

  - Definition

  - Budget

  - Planning

  - Requirement

  - Progress

  - Monitoring

  - Invoicing

 - viii. Tools Module

 - Tools Module covers the following:

  - Software installation

  - Application configuration

  - User management

  - Device management

  - Job management

  - Database management

  - Audit management

  - Text management

  - Menu management

  - SQL queries

  - Application development and customization

  - Documentation


![u138](/CIM/Notes/src/u138.png)
# Fig. Supply Chain

 - ix. Utilities Module

 - The utilities module is used to import and export data among different ERP systems. Other Modules of ERP packages are:

  - Materials management

  - Supply chain management

  - Quality management

  - Human resource management

  - Plant maintenance

  - Treasury

# CNC Controller

 - The CNC controller is the brain of a CNC system. A controller completes the all important link between a computer system and the mechanical components of a CNC machine. The controller's primary task is to receive conditioned signals from a computer or indexer and interpret those signals into mechanical motion through motor output. There are several components that make up a controller and each component works in unison to produce the desired motor movement.

 - The word “controller” is a generic term that may refer to one of several devices, but usually refers to the complete machine control system. This system may include the protection circuitry, stepper or servo motor drivers, power source, limit switch interfaces, power controls, and other peripherals. Owners, operators, designers, and builders of CNC devices should understand the tasks performed by these components and how they affect machine performance.

 - The following sections will discuss the primary task of each component in the controller and how they work together to create a complete CNC system.

 - Recently a new generation of CNC controllers has been marketed by several manufacturers. Some of their important features are:

# I. Automatic determination of optimum tool path:

 - By using data that is interactively input to define the workpiece contours artificial intelligence is employed to determine the optimum approach point and tool path to eliminate unnecessary tool movement. As a result, the overall machining cycle is minimized.

# II. Feed spindle orientation:

 - By the use of a digitally controlled AC spindle motor, spindle orientation is fast and precise.

# III. Automatic feedrate override:

 - Even though only one feedrate is programmed for a machining cycle such as a pocket milling, the optimum feedrate for both the in-feed direction and corner cutting is automatically determined. Also when milling pockets, the feedrate is automatically changed when machining with full cutter width and when machining with partial cutter width to maintain the optimum cutting conditions for the minimum machining time.

# IV. Simultaneous S, M and T functions:

 - Simultaneous operation of different units, such as the ATC and Machine table indexing, A T C and pallet changer can performed to greatly reduce machine’s non-cutting time.

# V. High speed tapping:

 - The digitally controlled spindle motor allows spindle rotation and Z axis feed to be synchronized. This advanced design makes high speed, high precision tapping possible without the use of the floating tap holder. This is also referred as rigid tapping.

# VI. High speed cutting of complex contours:

 - For complex contours that require interpolation by extremely small increments, the faster processing of speed of the 32 or 64 bit processor results in a much higher vectorial feed rate than that of conventional CNC systems.

# VII. D N C interface:

 - The 32 or 64 bit CNC mounted on a machine can be linked with a host computer and transmit and receive data. By DNC interface, information can be shared.

# VIII. MAP compatibility:

 - The 32 bit CNC controller is designed for MAP (Manufacturing Automation Protocol) compatibility - the international communication standards to be used by equipment in an automated factory.

# IX. Background communication:

 - The high speed 32 bit microprocessors can handle communications of variety of data - programs, parameters, tool data and programs with a host computer simultaneously while in automatic operation.

# X. Absolute position detection:

 - If equipped with absolute position detection function, a machine does not have to return to the home position prior to beginning operation. This is especially advantageous for a machining center controlled by host computer.

# XI. Tool life management, Tool breakage detection and recovery:

 - These functions resident in the individual machine’s memory can be communicated with the host computer, thereby facilitating centralized tool management.

# XII. Automatic centering:

 - By the use of a touch sensor mounted in the spindle, measurement of datum holes and surfaces is performed. Based on the measurement results, the work co-ordinate system is automatically shifted and machining begins.

# XIII. Adaptive feed rate control:

 - By continually monitoring the load on the spindle motor and Z- axis servo motor, optimum cutting conditions are maintained. When an overload condition is detected, the programmed feedrate is automatically overridden. As the cutting load becomes smaller, the feed rate will automatically return to the programmed value.

# XIV. Process management and program layout displays:

 - The interconnections between processes and subprograms and processes with commonly used tools are indicated on these displays for convenient program restarts.

# XV. Automatic tool length measurement:

 - Tool length can be automatically measured and registered in memory to greatly reduce tool setting time. One setting of the measurement cycle allows up to 13 tools to automatically processed. (This process is semi-automatic for face mills and boring bars in that the tool must first be manually positioned over the measurement unit).

# XVI. Workpiece co-ordinates:

 - When using a tool (such as an edge finder) to establish a workpiece datum point, all that is required is to enter the tool radius. The necessary calculations are performed automatically to set the work piece zero position. When the optional touch sensor is used the angular offset co-ordinates can also be set. This allows high machining accuracy to be obtained even with simple fixtures.

# XVII. Tool path storage:

 - The tool path storage function can be used to store in memory the point where a tool breaks during the cutting plus the path used to retract the cutter for servicing. This allows fast and smooth program restarting.

# XVIII. Automatic cutting conditions editing:

 - Programmed spindle speeds and feed rate are easily altered by override keys according to actual machining conditions. By pushing an appropriate key, the programmed cutting conditions are automatically edited by the override amount on an individual tool basis.

# XIX. Modal information display:

 - The modal information display indicates which G, M, S, f codes are effective. This is extremely convenient for error-free restart of EIA / ISO programs. The modal information display indicates which G, M, S, f codes are effective. This is extremely convenient for error-free restart of EIA / ISO programs.

# XX. Deflection compensation:

 - Automatic compensation can be performed for the displacement at one axis in relation to another axis used as the datum.

# XXI. Large reduction of component parts:

 - With a 32 or 64 bit microprocessor as the core, large capacity memory chips, customs LSI’s and other state of the art technology used to the maximum, the number of parts is considerably smaller than that of conventional CNC system resulting in a highly reliable and compact design.

# XXII. Ladder circuit display:

 - The open and close status of individual circuits is displayed on the ladder chart on CRT display to help pinpoint the cause of problems.

# XXIII. Optimization of cutting conditions:

 - Several CNC systems access cutting tool databases as well as cutting parameter databases. The interactive programming facilities enable the operator of the machine tool to input the features of the drawing in the CNC system. The system responds with appropriate tool selection and cutting parameter selection. Techniques are also incorporated to optimize the parameters.

# Understanding Interpolation/Motion Control

 - Say for example, you wish to move only one linear axis in a command. You want to move the axis to a position one inch to the right of program zero. In this case, the command X1 would be given (assuming the absolute mode is instated). The machine would move along a perfectly straight line during this movement (since only one axis is moving).

 - Now let's say you wish to include a Y axis movement to a position one inch above program zero in Y (with the X movement). We'll say you are trying to machine a tapered or chamfered surface of your workpiece in this command. For the control to move along a perfectly straight line to get to the programmed end point, it must perfectly synchronize the X and Y axis movements. Also, if machining is to occur during the motion, a motion rate (feed rate) must also be specified. This requires linear interpolation.

 - During linear interpolation commands, the control will precisely and automatically calculate a series of very tiny single axis departures, keeping the tool as close to the programmed linear path as possible. With today's CNC machine tools, it will appear that the machine is forming a perfectly straight line motion. However, Figure 1 shows what the CNC control is actually doing during linear interpolation.

 - In similar fashion, many applications for CNC machine tools require that the machine be able to form circular motions. Applications for circular motions include forming radii on turned workpieces between faces and turns, and milling radii on contours on machining centers. This kind of motion requires circular interpolation. As with linear interpolation, the control will do its best to generate as close to a circular path as possible.

 - Depending on the machine's application, you may find that you have other interpolation types available. Again, CNC control manufacturers try to make it as easy as possible to program their controls. For example, many machining center users perform thread milling operations on their machines. During thread milling, the machine must move in a circular manner along two axes (usually X and Y) at the same time a third axis (usually Z) moves in a linear manner. This allows the helix of the thread to be properly machined. This motion resembles a spiraling motion (though the radius of the spiral remains constant). Knowing that their customers need this type of motion for thread milling, CNC machining center control manufacturers offer the feature called helical interpolation.

 - Yet another type of interpolation may be required on turning centers that have live tooling. For turning centers that can rotate tools (like end mills) in the turret and have a C axis to rotate the workpiece held in the chuck, polar coordinate interpolation can be used to mill contours around the periphery of the workpiece. Polar coordinate interpolation allows the programmer to flatten out the rotary axis, treating it as a linear axis for the purpose of making motion commands.

# The Three Most Basic Motion Types:

 - While your particular CNC machine may have more motion types (depending on your application), let's concentrate on the three most common types available on almost all forms of CNC equipment. After briefly introducing each type of motion, we'll show an example program that stresses the use of all three.

 - These motion types share two things in common. First, they are all modal. This means they remain in effect until changed. If, for example, several motions of the same kind are to be given consecutively, the corresponding G code need only be specified in the first command.

 - Second, the end point of the motion is specified in each motion command. The current position of the machine will be taken as the starting point.

 1. Rapid Motion (Also Called Positioning)

 - This motion type is used to command motion at the machine's fastest possible rate. It is used to minimize non-productive time during the machining cycle. Common uses for rapid motion include positioning the tool to and from cutting positions, moving to clear clamps and other obstructions, and in general, any non-cutting motion during the program.

 - You must check in the machine tool builder's manual to determine a machine's rapid rate. Usually this rate is extremely fast (some machines boast rapid rates of well over 1000 rpm), meaning the operator must be cautious when verifying rapid motion commands. Fortunately, there is a way for the operator to override the rapid rate during program verification.

 - The command almost all CNC machines use to initiate rapid motion is G00. Within the G00 command, the end point for the motion is given.

 - Control manufacturers vary with regard to what actually happens if more than one axis is included in the rapid motion command. With most controls, the machine will move as fast as possible in all axes commanded. In this case, one axis will probably reach its destination point before the others. With this kind of rapid command, straight line movement will not occur during rapid and the programmer must be very careful if there are obstructions to avoid. With other controls, straight line motion will occur, even during rapid motion commands.

 2. Straight Line Motion

 - This motion type allows the programmer to command perfectly straight line movements as discussed earlier during our discussion of linear interpolation. This motion type also allows the programmer to specify the motion rate (feed rate) to be used during the movement. Straight line motion can be used any time a straight cutting movement is required, including when drilling, turning a straight diameter, face or taper, and when milling straight surfaces.

 - The method by which feedrate is programmed varies from one machine type to the next. Generally speaking, machining centers only allow the feed rate to be specific in per-minute format (inches or millimeters per minute). Turning centers also allow feed rate to be specified in per-revolution format (inches or millimeters per revolution).

 - A G01 word is commonly used to specify straight line motion. Within the G01, the programmer will include the desired end point in each axis.

 3. Circular Motion

 - This motion type causes the machine to make movements in the form of a circular path. As discussed earlier during our presentation of circular interpolation, this motion type is used to generate radii during machining. All feed rate related points made during our discussion of straight line motion still apply.

 - Two G codes are used with circular motion. G02 is commonly used to specify clockwise motion while G03 is used to specify counter clockwise motion. To evaluate which to use, you simply view the movement from the same perspective the machine will view the motion. For example, if making a circular motion in XY on a machining center, simply view the motion from the spindle's vantage point. If making a circular motion in XZ on a turning center, simply view the motion from above the spindle. In most cases, this is as simple as viewing the print from above.

 - Additionally, circular motion requires that, by one means or another, the programmer specify the radius of the arc to be generated. With newer CNC controls this is handled by an R word that simply states the radius. With older controls, directional vectors (specified by I, J, and K) tell the control the location of the arc's center point. Since controls vary with regard to how directional vectors are programmed, and since the R word is becoming more and more popular for radius designation, our examples will show the use of the R word. If you wish to learn more about directional vectors, refer to your control manufacturer's manual.

# Example

 - Program Showing Three Types of Motion

 - In this particular example, we are milling around the outside of a workpiece contour. Notice that we are using a one-inch diameter end mill for machining the contour and we are programming the very center of the end mill. Later, during key concept number four, we will discuss a way to actually program the workpiece contour (not the cutter centerline path).


![u139](/CIM/Notes/src/u139.png)

 - While you may not understand all commands given in this program, concentrate on understanding what is happening in the motion commands (G00, G01, and G02/G03). With study, you should be able to see what is happening. Messages in parentheses are provided to document what is happening in each command.

 - Keep in mind that CNC controls do vary with regard to limitations with motion types. For example, some controls have strict rules governing how much of a full circle you are allowed to make within one circular command. Some require directional vectors for circular motion commands instead of allowing the R word. Some even incorporate automatic corner rounding and chamfering, minimizing the number of motion commands that must be given. Though you must be prepared for variations, and you must reference your control manufacturer's programming manual to find out more about your machine's motion commands, at least this presentation has shown you the basics of motion commands. You should be able to adapt to your particular machine and control with relative ease.

# SOME FEATURES OF MODERN CNC SYSTEMS

  - Advanced hardware architecture:
 - Custom built very large scale integrated circuits (VLSI) which can handle several functions in a single chip are used in modern CNC systems. This way, the benefits of reduced component count and improved reliability are realized.

  - Software modularity:
 - Each function is written as a discrete module - (structured programming). Additional software features can be added at any time to upgrade the control without affecting the software.

  - Adaptive control:
 - Reduces the production time by maximizing the utilization of the machine tool. It acts on measurement taken from external sensors (In-process measurement) and modifies the cutting conditions suitably.

  - Conversational programming:
 - The system featuring conversational programming are termed “user friendly” since they are designed with the operator in mind. One example of such a friendly feature is graphic display. With this feature, the operator can create the part drawing on screen and simulate the tool paths in the preparatory phase (Prior to machining). The operator can program in complete safety and be sure that nothing is omitted. The operator can also check the correctness of the part program on graphic display.

  - Programming flexibility:
 - In addition to conversational part programming language, high level language commands like IF-THEN ELSE, GO TO etc., can be used to extend the program’s power. Higher mathematical functions can be used to calculate square roots, trigonometric functions etc.

  - DNC link:
 - This is discussed separately in detail later.

  - Color graphics:
 - This provides visual interface between the operator and CNC. Part cross sections can be highlighted. Operating instructions and warning display can be colour coded for more clarity.

  - Machine interface:
 - A high-level language like C is used for programming the machine logic in PC (example: GE 2000 MC). In AB8600, high-level language SIPROM (System Interface-Programming) is used.

  - Automatic selection of cutting speeds:
 - If we specify the tool material and work material, C N C System selects cutting speed and feed from cutting condition technology database.

  - Automatic selection of tools and sequencing of tools:
 - If operation is specified, system selects corresponding tools and sequence of tools. Systems like Mazak Fusion 640 provides this knowledge based approach.

  - Optimization of machine program:
 - This feature will be useful for components with large number of drilling, tapping operations, or repetitive end milling tool paths as in the case of machining of dies and molds etc.

  - Display of finished component:
 - Today CNC systems offer a feature to display the finished component together with dimensions. Sectioning and rotation of the model of the finished part are also possible.

  - Background programming:
 - It is a common facility available in CNC systems. The user can run, edit and simulate another program while a program is being executed on the machine tool.

  - Digital CNC:
 - The new breed of CNC controls uses digital technology. The introduction of digital CNC has brought increased speed and precision to machine tool builders. The PC based open architecture controls incorporate such features like acceleration with jerk limitation, direct NURBS interpolation, use of high level languages, execution of large CNC programs from hard disc and increased number of zero offsets. In some of the systems the CNC and drive amplifiers are on the some board at the digital level.

  - Look ahead feature:
 - The control system scans 150 or more blocks ahead of the block that is being executed and carries out interpolation and calculates the acceleration and deceleration requirements in the case of generation of complex tool paths. This helps to produce accurate profiles in high speed machining.

# DIRECT NUMERICAL CONTROL (DNC)

 - Early NC machines used a tape reader for storing and inputting the program into the memory of the NC machine tool. Because of the unreliability of the tape reader as well as the low speed of operation NC engineers were searching for a suitable alternative. The advent of CNC in mid-sixtees opened up the possibility of improving the performance of NC machines by interfacing them with minicomputers. Yet another significant technological development was the interfacing of several NC machines with a computer, which can store the part programs and transfer them to the NC machine concerned as and when needed. The computer is connected between the tape reader and the NC machine thereby bypassing the tape reader. This system was therefore called as behind the tape reader system (BTR). This development became very popular with NC machine users because of a number of significant advantages.

 - (i) A number of NC machines can be connected to a single computer. In many cases a single computer can manage all the machines on a shop floor.

 - (ii) Programs in full or in segments can be transferred to the NC machines in a multiplexing mode.

 - (iii) The computer can be conveniently used for program editing.

 - (iv) Since the computer has large memories there is no limitation on the number or size of programs stored.

 - (v) The computer can be used for other tasks like program creation using computer aided part program generation software as well as for operation management tasks like production planning, scheduling etc.

 - With the development of CNC, DNC concept was extended to CNC machines also mainly for part program management. The DNC computer (sometimes referred to as host computer) could serve a number of CNC machines in shop floor. The DNC computer stores all the part programs and transfers the part programs to the CNC machines in response to the requests of the operators.


![u140](/CIM/Notes/src/u140.png)

 - A DNC System

 - DNC systems are generally designed for 4, 8, or 16 CNC machines. However, with the wide spread acceptance of the local area network concept, the possibility of connecting more CNC machine in a DNC network has become a reality. The concepts of Internet, Intranet and Extranet have further enlarged the scope of distributed numerical control.

# OBJECTIVES OF DNC

 - DNC serves many purposes and is now considered as essential for the efficient management of CNC machine tools in the shop floor. The main objectives of implementing DNC are given below:

 1. Upload and download CNC programs to and from machine tools simultaneously and directly from the CNC systems.

 2. Easy editing of the existing programs.

 3. Eliminating the use of manual switch boxes to multiplex CNC machines.

 4. Organizing and cataloguing of all programs for instant access.

 5. Eliminating the need for manually punching the program at the keyboard thereby

 6. Saving considerable costly machine time.

 7. Eliminating the need for paper tape in the old generation of NC machines.

 8. Copy programs to and from the floppy discs and other media to the DNC computer.

 9. Compare files edited at the CNC to the original program.

 10. Rename or delete or update programs or create new programs.

 11. Show pictures of set ups for graphic catalogue of set up and machining operations.

 12. Providing system transaction files of all activity on the DNC computer.

 13. Pass word protection at different points of the CNC system wherever the operator could cause damage to the NC code by overwriting.

 14. Tool length offsets from tool pre-setters can be transferred directly to machine tool controls. It is also possible to connect co-ordinate measuring machines to DNC networks.

# DISTRIBUTED NUMERICAL CONTROL

 - Sometimes the abbreviation DNC is used to denote distributed numerical control. A computer network for manufacturing may consist of a main frame computer, CAD/CAM work stations, DNC host computer and the CNC systems connected to it. This configuration can be beneficially used for NC data processing. Any complex calculations required for generating NC data can be transferred to the more powerful mainframe computer. Thus the NC DATA processing is done at different hierarchical levels. In a way many of the DNC systems today are in fact distributed processing systems.

# FUNCTIONS OF A DNC SYSTEM

 - The functions of a DNC system can be summarized as below:

# i. Part Program management:
 - Part program stored in the hard disc can be routed to appropriate machines in the network depending upon the schedule.

# ii. Shop floor editing:
 - Program can be edited or modified to take into account design changes, tool changes or machine changes.

# iii. Shop floor graphics:
 - The tool path simulation can be carried out on the shop floor.

# iv. Data collection:
 - The DNC computer can be used for shop floor data collection for scheduling and monitoring.

# v. Shop scheduling:
 - Since NC program dispatch is interlinked with the schedule, the DNC computer can be used for scheduling.

# vi. Statistical Process Control (SPC):
 - The SPC function can be integrated into the working of the DNC computer as it can be interfaced with the shop floor data collection function.

# vii. Tool offset management:
 - Tool offset data is sent to appropriate machine by this function.

 - The DNC network systems are usually UNIX, Novell or Windows based. They have multitasking capabilities and Ethernet, arcnet or token ring interfaces. They may also have Limited CAD/CAM capabilities. Efficient built-in security systems will take care of unauthorized access.
