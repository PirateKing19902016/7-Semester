# COMPUTER AIDED PROCESS PLANNING

# INTRODUCTION

 - Process planning is concerned with determining the sequence of individual manufacturing operations needed to produce a given part or product. The resulting operation sequence is documented on a form typically referred to as operation sheet. The operation sheet is a listing of the production operations and associated machine tools for a work part or assembly. Process planning is an important stage of product development since production tooling like jigs, fixtures, special tools etc. can be designed only after the process is finalized. Like a group technology - based system utilizing classification and coding to retrieve parts, code numbers can be used for retrieval of existing and preferred manufacturing information. The principle of group technology is therefore discussed here as part of process planning. The importance of process planning lies in the fact that process plans have a direct bearing on the cost of the part. As new manufacturing processes and machines are introduced, process plans also undergo changes. Hence process planning is a dynamic activity. The continuous emphasis on cost reduction also requires the process plans to be updated to reduce the cost. Cost information can be included in a computer assisted process planning system, using an automatic time standards (ATS) system.

# PROCESS PLANNING

 - Manufacturing planning, process planning, material processing, process engineering and machine routing are a few titles given to the topic referred to here as process planning. Process planning is that function within a manufacturing facility that establishes which machining process and process parameters are to be used to convert a work material (blank) from its initial form (raw material) to a final form defined by an engineering drawing. Process planning is a common task in small batch, discrete parts metal working industries.

  - The process planning activity can be divided into the following steps:

  - Selection of processes and tools

  - Selection of machine tools/Manufacturing equipment

  - Sequencing the operations

  - Grouping of operations

  - Selection of work piece holding devices and datum surfaces (set ups)

  - Selection of inspection instruments

  - Determination of production tolerances

  - Determination of the proper cutting conditions

  - Determination of the cutting times and non-machining times (setting time,

  - inspection time) for each operation

  - Editing the process sheets.

 - All the information determined by the process planning function is recorded on a sheet called process plan. The process plan is frequently called an operation sheet, route sheet or operation planning sheet. This provides the instructions for the production of the part. It contains the operation sequence, processes, process parameters and machine tools used.

 - In conventional production system, a process plan is created by a process planner. It requires a significant amount of time and expertise to determine an optimal routing for each new part design. However, individual engineers will have their own opinions about what constitutes the best routing. Accordingly there are differences among the operation sequences developed by various planners. Efficient process planning requires the service of experienced process planners.


![u141](/CIM/Notes/src/u141.png)

 - Because of the problems encountered with manual process planning, attempts have been made in recent years to capture the logic, judgment and experience required for this important function and incorporates them into computer programs. Based on the features of a given part, the program automatically generates the sequence of manufacturing operations. The process planning software provides the opportunity to generate production routings which are rational, consistent and perhaps even optimal.

 - It has the following advantages:

  - Reduces the skill required of a planner.

  - Reduces the process planning time.

  - Reduces the process planning and manufacturing cost.

  - Creates more consistent plans.

  - Produces more accurate plans.

  - Increases productivity.

# Steps Involved in CAPP

 - Now-a-days, rapid progress is being made in the automation of actual production process and also the product design element. However, the interface between design and production presents the greatest difficulty in accomplishing integration. CAPP has the potential to achieve this integration. In general, a complete CAPP system has following steps :

 1. Design input

 2. Material selection

 3. Process selection

 4. Process sequencing

 5. Machine and tool selection

 6. Intermediate surface determination

 7. Fixture selection

 8. Machining parameter selection

 9. Cost/time estimation

 10. Plan preparation

 11. Mc tape image generation.

# APPROACHES TO COMPUTER-AIDED PROCESS PLANNING

 - In recent days, several computer-aided process planning systems are available for use for a variety of manufacturing operation.

 - These systems can broadly be clarified into two categories:

 - i. Variant computer aided process planning method.

 - ii. Generative computer aided process planning method.

 - The details of these are explained in next subsections.

# Variant Process Planning, Advantages and Disadvantages

 - Variant process planning approach is sometimes referred as a data retrieval method. In this approach, process plan for a new part is generated by recalling, identifying and retrieving an existing plan for a similar part and making necessary modifications for new part. As name suggests a set of standard plans is established and maintained for each part family in a preparatory stage. Such parts are called master part. The similarity in design attributes and manufacturing methods are exploited for the purpose of formation of part families. Using coding and classification schemes of group technology (GT), a number of methods such as coefficient based algorithm and mathematical programming models have been developed for part family formation and plan retrieval. After identifying a new part with a family, the task of developing process plan is simple. It involves retrieving and modifying the process plan of master part of the family.

 - The general steps for data retrieval modification are as follows:

# Establishing the Coding Scheme

 - A variant system usually begins with building a classification and coding scheme. Because classification and coding provide a relatively easy way to identify similarity among existing and new parts. Today, several classification and coding systems are commercially available. In some extreme cases, a new coding scheme may be developed. If variant CAPP is preferred than it is useful for a company to look into several commercially available coding and classification systems (e.g. DCLASS, JD-CAPP etc.). Now, it is compared with companies before developing their own coding and classification system. Because using an existing system can save tremendous development time and manpower.

  - Form the Part Families by Grouping Parts -
 - The whole idea of GT lies into group numerous parts into a manageable number of part families. One of the key issues in forming part families is that all parts in the same family should have common and easily identifiable machined features. As a standard process plan are attached with each part family, thereby reducing the total number of standard process plans.

  - Develop Standard Process Plans -
 - After formation of part families, standard process plan is developed for each part families based on common part features. The standard plan should be as simple as possible but detailed enough to distinguish it from other.

  - Retrieve and Modify the Standard Plans for New Parts -
 - Step1 to step 3 are often referred as preparatory work. Each time when a new part enters the systems, it is designed and coded based on its feature, using the coding and classification scheme, and than assigned to a part family. The part should be similar to its fellow parts in the same family. Also, family’s standard plan should represent the basic set of processes that the part has to go through. In order to generate detailed process routes and operation sheets to this part, the standard plan is retrieved from the database and modified. Modification is done by human process planar. After this stage parts are ready for release to the shop.  The success of aforementioned process planning system is dependent on selection of coding scheme, the standard process plan and the modification process, because the system is generally application oriented. It may be possible that one coding scheme is preferable for one company and same is not for other company.

 - Due to use and advancement of computers, the information management capability of variant process planning is much superior. Otherwise it is quite similar to manual experience-based planning.

# Advantages and Disadvantages of Variant CAPP

 - Following advantages are associated with variant process planning approach:

  - Processing and evaluation of complicated activities and managerial issues are done in an efficient manner. Hence lead to the reduction of time and labor requirement.

  - Structuring manufacturing knowledge of the process plans to company’s needs through standardized procedures.

  - Reduced development and hardware cost and shorter development time. This is an essential issue for small and medium scale companies, where product variety is not so high and process planner are interested in establishing their own process planning research activities.

# Disadvantages of Variant Process Planning Approach

 - Following disadvantages are associated with variant process planning approach

  - It is difficult to maintain consistency during editing.

  - Proper accommodation of various combinations of attributes such as material, geometry, size, precision, quality, alternate processing sequence and machine loading among many other factors are difficult.

  - The quality of the final process plan largely depends on the knowledge and experience of process planner. The dependency on process planner is one of the major shortcomings of variant process planning.


![u142](/CIM/Notes/src/u142.png)
# FRAMEWORK OF VARIANT PROCESS PLANNING ACTIVITY

 - Some of the most widely used process planning method developed by various company are mentioned as follows:

  - Mc Donnell-Douglas automation company under the direction and sponsorship of Computer Aided Manufacturing International (CAM-I) developed a system where CAPP can be used to generate process plan for rotational, prismatic and sheet metal part.

  - Organization for Industrial Research (OIR) and General Electric Company have developed and another process plan named as MIPLAN. It accommodates both rotational and prismatic part, and is based on MICLASS coding.


&nbsp;

# Generative Process Planning, Advantages and Disadvantages

 - In generative process planning, process plans are generated by means of decision logic, formulas, technology algorithms, and geometry based data to perform uniquely processing decisions. Main aim is to convert a part from raw material to finished state. Hence, generative process plan may be defined as a system that synthesizes process information in order to create a process plan for a new component automatically.

 - Generative process plan mainly consists of two major components:

  - Geometry based coding scheme.

  - Proportional knowledge in the form of decision logic and data.

# Geometry-based Coding Scheme

 - All the geometric features for all process such as related surfaces, feature dimension, locations, on the features are defined by geometry based coding scheme. The level of detail is much greater in generative system than a variant system.

 - For example, various details such as rough and finished state of the part are provided to transform into desired state.

# Proportional Knowledge in the Form of Decision Logic and Data

 - Process knowledge in the form of decision logic and data are used for matching of part geometry requirement with the manufacturing capabilities. All the methods mentioned above is performed automatically.

 - Operation instruction sets are automatically generated to help the operators to run the machines in case of manual operation. NC codes are automatically generated, when numerically controlled machines are used.


![u143](/CIM/Notes/src/u143.png)
# FRAMEWORK OF A DECISION TABLE

 - Manufacturing knowledge plays a vital role in process planning. The process of acquisition and documentation of manufacturing knowledge is a recurring dynamic phenomenon. In addition, there are various sources of manufacturing knowledge such experience of manufacturing personnel, handbooks, supplier of machine tools, tools, jigs and fixtures materials, inspection equipment and customers etc. Hence, in order to understand manufacturing information, ensuring its clarity and providing a framework for future modification, it is not only necessary but also inevitable to develop a good knowledge structure from wide spectrum of knowledge. Flowchart, decision trees, decision tables, algorithms, concepts of unit machined surfaces, pattern recognition techniques, and artificial intelligent based tools are used to serve the purpose. A brief discussion on decision table is given below.

 - The basic elements of decision tables are condition, action and rules. They are represented in the form of allocation matrix. Figure above is one such representation where condition states the goal that we want to achieve and action states the operation that we have to perform. On the basis of experience the expert rules are formed by entry values to establish the relationship between condition and action.

 - Table is one such representation where entry are of Boolean-types (true, false, don’t care). Similarly, in next table continuous value type entries are shown.

# Boolean Value-Type Entries

![u144](/CIM/Notes/src/u144.png)
 - * T : True; F : False

# Continuous Value-type Entries

![u145](/CIM/Notes/src/u145.png)
 - * T : true

 - The decision making process works as follow.

 - For a particular set of condition entries, look for its corresponding rule from that rule determine the action.

# Advantages of Generative Process Plan
 - Generative process plans have a number of advantages. Among the major ones are the following:

  - They rely less on group technology code numbers since the process, usually uses decision tree to categorize parts into families.

  - Maintenance and updating of stored process plans are largely unnecessary. Since, any plan may be quickly regenerated by processing through the tree. Indeed, many argue that with generable systems, process plans should not be stored since if the process is changed, and out-of-dated process plan might find its way back into the system.

  - The process logic rules however must be maintained up to dated and ready for use. This provides the process planner with an assurance that the processes generated will reflect state-of-the-art technology.

 - Description of various generative and variant and generative CAPP systems is mentioned Table.

# Some of the Variant and Generative CAPP Systems

![u146](/CIM/Notes/src/u146.png)
# Knowledge-based Process Planning
 - The main forces behind to apply knowledge-based (KB) techniques for CAPP is the requirement of large amount of human expertise in CAPP. Based on the previous discussion, one realizes that a productive CAPP system must contain tremendous amount of knowledge – facts about the machine and shop environment as well as rules about sequencing machining operations must be included. A traditional CAPP program cannot learn new knowledge without a programmer explicitly rewriting it. The rigidity of traditional methodology endangers the implementation of CAPP systems. A KB system stores knowledge in a special manner so that it is possible to add, delete and modify facts and rules in the knowledge base without rewriting the program, i.e. it learns new things according to embedded learning procedures.

 - A complete set of manufacturing knowledge is not equipped by any existing knowledge-based process planning system. Most of these systems focus on a small portion of the issues in the domain of automated process planning using an expert systems approach. Some of them are:

# EXCAP Family of Process Planning Systems
 - EXCAP, EXpert Computer-Aided Process Planning, developed by Davies and Darbyshire, is a knowledge-based system for rotational part process planning. EXCAP-A and EXCAP-Y are previous generations of the current member of the EXCAP family of process planning systems.

# GARI
 - GARI is the first AI-based CAPP program to appear in the literature. It is implemented in MACLISP and operates on CII-Honeywell Bull HB-68 computer under the MULTICS operating system. GARI utilizes production rules in its knowledge representation and generates a process plan from a model of the part. It emphasizes the “conflict resolution”. The knowledge is rather subjective and specialized. As a result, in the planning process, “compromises are often necessary.”

# TOM: Technostructure of Manufacturing
 - TOM is another production rule-based CAPP system written in PASCAL and runs on VAX computer. TOM was designed to accept input in two ways: (1) directly entering part desecration by the user, and (2) translating design data from COMPAC CAD system. TOM can deal with “holes” exclusively.

# SIPP: Semi-Intelligent Process Planner
 - SIPP is an AI-based CAPP system for the creation of metal parts using chip metal removal operations. It is written in PROLOG and utilizes “frames” as its knowledge representation scheme instead of using production rules. Frames are used to represent two types of knowledge:

 - (1) Information about the characteristics of various kinds of machinable surfaces, and

 - (2) The capabilities of various machining processes.

# SIPS
 - SIPS, another AI-based CAPP system which selects machining operations for the creation of metal parts, is a successor to SIPP. It is written in LISP and is currently being integrated into the AMRF (Automated Manufacturing Research Facility) project, where it is used to select machining operations on a feature by feature basis.

 - Like SIPP, SIPS also employs branch and bound search strategy for the least-cost-first solution in its inference engine. The basic difference between SIPP and SIPS is that SIPS used a new knowledge representation technique, called hierarchical knowledge clustering, instead of “flat” frames to represent problem-solving knowledge.

# TOLTEC
 - TOLTEC is a system equipped with some learning capability. It takes input as feature-based part description interactively. The features are represented in a frame structure. It generates output in a form of operations and their sequence.

# Turbo-CAPP
 - Turbo-CAPP is a knowledge-based CAPP system written in PROLOG and capable of:

  - Extracting and interpreting surface features from a 2 and 1/2-D CAD data base.

  - Performing intelligent reason for process planning.

  - Learning new process and machining capabilities.

  - Generating alternative process plans (based on the current status of the knowledge base).

  - Creating generic NC part programs for automated.

 - Turbo-CAPP is designed to handle strictly symmetric rotational parts. It employs a backward chining inference mechanism for plan generation. In the process of creating process plan and NC codes, the system must acquire knowledge from the user from time to time.

# XPS-2 Family of CAPP Systems
 - CAM-I started the first structured development of process planning systems. It then embarked on a form-feature based, generative planning project, XPS and accomplished with the completion of XPS-2 in 1987. The form feature used to implement XPS-2 were taken from a “feature taxonomy” developed by CAM-I.

# Other Knowledge-Based CAPP Systems

 - Rather than aforementioned Knowledge-Based CAPP System some other KB process planning systems are in existence:

 - i. CMPP (Austin, 1996) is a planning system for planning cylindrical parts (also for some non-cylindrical features). It performs dimension, tolerance, and stock removal analysis based on a sophisticated algorithm with the objective of optimizing tolerance capabilities of shop equipment.

 - ii. Hi-MAPP developed by Brenfi and Khoshnevis.

 - iii. Wolfe and Kung in 1984 developed a CAPP system, which reads part geometry from a PADL model and generates process plans automatically.

# Variant or Generative, Which to Use?

 - What CAPP approach (Variant or Generative) is better? This question has been constantly asked but, there is no definite answer to it.

 - Generally speaking, a variant system is better for manufacturing setting where similar parts are manufactured repetitively. Because parts are similar, Group Technology can easily be implemented and shows quick and significant return on investment (ROI). Because similar parts are produced repetitively, process plan can be retrieved, slightly modified and used, without going through too much trouble. On the other hand, generative process planning is better suited for a manufacturing environment in which part does not exhibit too much similarity and new part are introduced on a regular basis. In this case, benefits cannot be gained from Group Technology due to dissimilarity of parts. Because, new parts are regularly introduced, historical data does not have too much value to the process planner. However, aforementioned approach is a rough guideline for selecting the appropriate CAPP approach.

# FEATURE RECOGNITION IN CAPP

 - As we have seen that CAPP system usually serve as link in integrating the CAD and CAM. However, it is only the partial link due to lack of part feature information provided by existing CAD/ Drafting system. Part feature information is an essential data for CAPP. In other words, it is a tedious job for CAPP to understand the three dimensional geometry of the designed part from CAD system in terms of their engineering meaning related to assembly and manufacturing. Generally, all CAPP planning method and systems suffered from such type of problem and is referred as feature recognition in CAPP.

 - Hence, objective of feature recognition is to bridge the gap between the database and automated process planning systems by automatically distinguishing the feature of a part from the geometry and topological data stored in the CAD system. The essence of feature recognition can easily be understood by taking an example as shown in Figure. This figure is defined by a constructive solid geometry tree that represents a block primitive and a cylinder primitive combined by the Boolean operator “-”. Shape and dimension can easily be identified by these schemes but, some higher level information is not provided by this scheme such as, whether the hole is blind hole or through hole. Such types of information are called as feature. Hence, features play a vital role in CAPP. In order to identify features and to solve CAD / CAPP interface problem, feature recognition is one of the most efficient technique.

 - Feature recognition transforms a general CAD model into an application specific feature model. In general, a generic part feature recognition system must be able to resolve following issues.

  - Extract design information of a part.

  - Identify all surfaces of part.

  - Recognize reasons aboutndr interpret these surfaces in terms of Part features.

 - Once the features are classified, the automated planning system could develop the required process plan to make the part and hence, eliminate the need for a human to translate the CAD data into something that process planning system can understand.

 - Here, it is pertinent to mention that feature recognition is not only applicable to CAPP system but it can also be applied to various other engineering applications that require information about feature of parts classification and automated coding in GT.


![u147](/CIM/Notes/src/u147.png)
# ADVANCE LEVEL INFORMATION


&nbsp;

# APPROACHES TO PART FEATURE RECOGNITION

 - The most robust description of any part is provided through solid modelling. Therefore, these appear to be a logical starting point for developing a feature recognition system. Henderson and Anderson developed a system called FEATURES to perform automatic feature recognition using data from solid modelling system. A FEATURE simulates the human interpretation of part features. The system consists of a feature recognizer, extractor, and organizer. For objects containing swept features, this system performs well. This approach is encouraging because, conceptually, it can be applied for complex parts. The FEATURES system uses the boundary representation (BREP) of a part, which denotes the faces, edges and vertices (FEV). Thus, features such as holes must be derived from more primitive data.

# A Brief Review and Recent Trends in Feature Recognition Research Author


![u148](/CIM/Notes/src/u148.png)

 - Representing FEV contained in a BREP graph. As a result a hole may be present as a collection of faces that must be recognized from the part data.  A number of approaches to part feature recognition for rotational as well as prismatic parts have been developed. These different approaches are enlisted as follows:

 - I. Syntactic Pattern Recognition

 - II. State Transition Diagram and Automata

 - III. Geometry Decomposition Approach

 - IV. Expert System Rule Logic

 - V. CSG (Set Theoretic) Approach

 - VI. Graph Based Approaches

 - The syntactic pattern recognition and/or expert logic approach are mainly applied for feature extraction of rotational part feature recognition. The complexity increases in case for prismatic parts due to lack of rotational property. In this case, the difficulty of both representation of a generic object and recognition of its feature increases extensively.

# GROUP TECHNOLOGY

 - Group technology is an operations management philosophy based on the recognition that similarities occur in the design and manufacture of discrete parts. Similar parts can then be arranged into part families. To implement such a system, some form of classification of parts and coding is required.

 - Part classification and coding is concerned with identifying the similarities and using these similarities to evolve a classification code. Similarities are of two types:

 - Design attributes (such as geometric shape and size), and Manufacturing attributes (the sequence of processing steps required to make the part).

 - In companies which employ several design engineers and manufacturing a diverse range of products, such classifications and coding has a number of other uses. One of the major benefits is avoiding the duplication of similar components. This can result in considerable savings in terms of design cost, processing cost and tooling cost. One prime necessity to realize this is to have a good design retrieval system.

 - The parts classification and coding is required in a design retrieval system, and in computer aided process planning the process routing is developed by recognizing the specific attributes of the part and relating these attributes to the corresponding manufacturing operations.

# PART FAMILIES

 - A part family is a collection of parts which are similar either because of geometry and size or because similar processing steps are required in their manufacture. The parts within a family are different, but their similarities are close enough to merit their identification as members of the part family. The major obstacle in changing over to group technology from a traditional production shop is the problem of grouping parts into families. There are three general methods for solving this problem.

  - Visual inspection

  - Production flow analysis

  - Parts classification and coding system

 - What is desirable in a computer integrated manufacturing environment is a software which will analyze the geometric model of the part and come out with a set of alphabetic/ numeric characters which can broadly embed similarities.

# PARTS CLASSIFICATION AND CODING SYSTEMS
 - Parts classification and coding systems can be grouped into three general types:

  - Systems based on design attributes

  - Systems based on part manufacturing attributes

  - Systems based on both design and manufacturing attributes

 - Systems in the first category are useful for design retrieval and to promote design standardization. Systems in the second category are used for computer-aided process planning, tool design, and other production related functions. The third category represents an attempt to combine the functions and advantages of the other two systems into a single classification scheme. The types of design and manufacturing attributes typically included in classification schemes are listed below:

# Part Design Attributes
  - Basic (External/Internal) shape

  - Axisymmetric/Prismatic/sheet metal

  - Length/diameter ratio

  - Material

  - Major dimensions

  - Minor dimensions

  - Tolerances

  - Tolerances

# Part Manufacturing Attributes

  - Major process of manufacture

  - Surface treatments/coatings

  - Machine tool/processing equipment

  - Cutting tools

  - Operation sequence

  - Production time

  - Batch quantity

  - Production rate

  - Fixtures needed

 - If we take a look at a machine tool manufacturing industry, large part families can be grouped as:

 - I. Heavy parts - beds, columns etc.

 - II. Shafts, characterized by large L/D ratios

 - III. Spindles (long shafts, screw rods included)

 - IV. Non-rounds (small prismatic parts)

 - V. Gears, disc type parts (whose L/D ratios are small)

 - From the manufacturing point of view, group technology can bring in considerable economy in tooling, set up time, part changeover times, machine specifications etc. The classification of components in groups can lead to formation of cells where similar components are machined. However, these considerations are extraneous to the process planning function.

# OPITZ CLASSIFICATION SYSTEM

# The Opitz coding system uses the following digit sequence:

# 12345 6789 ABCD

 - The basic code consists of nine digits, which can be extended by adding four more digits. The first nine digits are intended to convey both design and manufacturing data. The general interpretation of the nine digits is indicated below The first five digits, 12345, are called the “form code” and describe the primary design attributes of the part. The next four digits, 6789, constitute the supplementary code. It indicates some of the attributes that would be of use to manufacturing (work material, raw work piece shape, and accuracy). The extra four digits, ABCD, are referred to as the secondary code and are intended to identify the production operation type and sequence. The secondary code can be designed by the firm to serve its own particular needs. In the form code, the first digit identifies whether the part is a rotational or a nonrotational part. It also describes the general shape and proportions of the part.


![u149](/CIM/Notes/src/u149.png)
# SPECIFICATION SCHEME

![u150](/CIM/Notes/src/u150.png)
# CODING THE FIRST FIVE DIGITS

# PROCESS SELECTION

 - Selecting the manufacturing processes to transform the raw material into the finished part is based on matching requirements with process capabilities. Process capability is the data base of knowledge for each process. It includes:

 - i. The shape and size of part a process can produce

 - ii. The dimensions and geometric tolerances that can be obtained

 - iii. The surface finish attainable

 - iv. The material removal rate

 - v. The relative cost

 - vi. Technological parameters

 - Process engineering does not necessarily imply that all process selection is based on the information above. However, the more the information considered in selecting a process, the more complete the result will be. A computer aided process planning system functions based on this process capability information. Earlier it was mentioned that planning systems could be classified into variant and generative types. A variant planning system is a retrieval system and is analogous to planning based on experience. In the variant planning system, standard plans are stored based on component shape. These plans are then retrieved based on the similarity of a coded part. A generative system, however, makes processing, tooling and other decision via software logic.

# EXAMPLE

 - Given the part design, the form code for this part is discussed below.


![u151](/CIM/Notes/src/u151.png)

# EXAMPLE PART

 - The overall length/diameter ratio, L/D = 1.6, so the first code = 1. The part is stepped on both ends with a screw thread on one end, so the second digit code would be 5 the third digit code is 1 because of the through hole. The fourth and fifth digits are both 0, since no surface machining is required and there are no auxiliary holes or gear teeth on the part. The complete form code in the Opitz system is “15100”. To add the supplementary code, we would have to properly code the sixth through ninth digits with data on dimensions, material, starting work piece shape, and accuracy.

# PROCESS PARAMETERS FOR MACHINING

 - Surface finish, force and power constraints are directly affected by the process parameters feed, speed and depth of cut. Therefore, process selection becomes an iterative procedure:

  - First a process is selected and then the machining parameters are adjusted to accommodate the system constraints.

  - Selection of the machining parameters also affects the time and cost required to produce components.

  - Several machinability systems are currently marketed that recommend sets of parameters that either optimize machining cost, time or production rate, or simply retrieve data table or calculated values.

 - One extensively used data system is CUT DATA from Machinability Data Systems of USA. Recently computerized machinability systems have been introduced which facilitate quick selection of optimum process parameters.

# AUTOMATED MATERIAL HANDLING SYSTEMS AND ADVANCED MANUFACTURING SYSTEMS


&nbsp;

# INDUSTRIAL ROBOTS

 - Robots perform several tasks in factories. Some of them are:

 - i. Movement of materials on the shop floor (Automated guided vehicles (AGV) or rail guided vehicle (RGV)

 - ii. Loading and unloading of components in machines (Gantry robot, machine mounted robot, free-standing robot)

 - iii. Inspection using vision sensors.

 - iv. Manufacturing operations like painting, welding, component insertion in printed circuit boards, sorting, automatic assembly, deburring, sampling, dispensing, marking, etc.

 - Robots are programmable machines with some human like capabilities. They are made up of mechanical components, a control system and a computer. These elements can be arranged in different ways and can vary in size and complexity to perform different tasks. Thus robots are available in a wide variety of types, which vary in their mechanical configuration, degrees of freedom of motion and type of drive and control systems. The degrees of freedom and working envelope provided by its geometric configuration are the two major selection factors of a robot. A number of different types of drive systems, each having its own advantages in cost and performance are used in robot technology. Robots are controlled by a variety of hardware and software systems. The more complex tasks usually require servo-control systems, which use sensors and microprocessors. The control system carries out the functions, which govern the robot’s motion.

 - Robotic systems are used in a CIM environment because of they have a number of economic and performance advantages over human labor or hard automation in many manufacturing applications, particularly in batch manufacturing. The major advantages are due to their re-programmability. Robots can be programmed by several techniques. Robot programs can be very simple or extremely complex, depending on the nature of the tasks and type of motion control involved. Robot programming is often done in high-level languages that provide functions for data processing, computation, sensing and manipulation. Robot manufacturers have developed different robot languages. The following sections give a detailed account of many of these aspects to enable the reader to understand the role of robots in a CIM environment.

# ELEMENTS OF A ROBOTIC SYSTEM

 - A robot is a system made up of several elements of hardware and software. These elements are illustrated below:


![u152](/CIM/Notes/src/u152.png)
# Elements of a Robotic System

# Mechanical Components:

 - They provide the physical robot motions and perform the various tasks. They include:

# i. Components of the robot manipulator:
  - A manipulator (the base and arm assembly).

  - End-of-arm tooling, such as a gripper or end effecter.

  - Actuators (motors or drives that move the links of the robot) and associated equipment.

  - Transmission elements like belts, pulleys, ball screws, gearing and other mechanical components.

# ii. Control system:
 - The control system is used to generate the necessary signals co-ordinate the movements of the robot. It includes:

  - Mechanical, hydraulic, pneumatic, electrical, or electronic (either open loop or closed loop) controls.

  - Sensors including cameras, amplifiers, and related hardware.

  - Equipment interfaces.

# iii. Computer system:
 - This provides the data processing capability necessary to interpolate the intermediate positions and control the movement of the links or arms the robot. It includes:

  - Microprocessor or a programmable logic controller or a personal computer

  - User interfaces (e.g. keyboard, display, teach pendant)

  - Control software to manipulate the robot for various applications.

 - Robots can be configured in many different ways by using various combinations of the above elements. Since robots are designed to perform tasks that might otherwise require humans, many of their basic features are like those of a human arm. For example, an articulated robot has arm, hand, wrist and gripper to reach, grasp and manipulate objects. They are driven by a power source, which provides the energy necessary for their movements. They can be programmed or can have an intelligent control system, controlled by neural, fuzzy or fuzzy neural techniques, which can acquire, store, process and perform on the basis of the data collected by sensors attached to the robot.

# CLASSIFICATION OF ROBOTS BASED ON MECHANICAL CONFIGURATION

 - Four basic robot arm geometries are used for industrial applications. These are illustrated below


![u153](/CIM/Notes/src/u153.png)
# Basic Classification of Robots

# Rectangular Co-ordinate Robots

 - This is also known as the Cartesian co-ordinate robots. A robot with this geometry has three linear axes using sliding joints, which are typically arranged in a cantilever configuration whose motion traces a box like shape. This type of configuration is ideal for straight-line and side-to-side movements. These robots can be used for tasks involving pick and place operations like material handling and loading and unloading of work pieces in machines.

# Cylindrical Co-ordinate Robots

 - This is also referred to as a rectilinear co-ordinate robot. A robot with this geometry has three axes of motion that trace the shape of a cylinder. It has a base unit, which rotates, a vertical extension, and a horizontal arm that moves in a line. This type is best suited for movements around a base.

# Spherical Co-ordinate Robots

 - This is also known as the polar co-ordinate robot. A robot with this geometry has three axes of motion that trace the shape of a sphere. It has a base unit that rotates, a main body that tilts, and arm that slides in and out.

# Revolute Co-ordinate Robots

 - This configuration is also known as anthropomorphic (i.e. like a human arm) or articulated arm or jointed arm. Such a robot has three axes of motion involving a base, a shoulder, and an “elbow” that rotate. Several variations of these basic geometries have also been developed to provide optimum performance for certain applications. Two of these are:

# i. “Gantry” or “box frame”

 - This is a rectangular co-ordinate configuration with all three linear axes of motion suspended above the work space. It can be made very rigid, which allows high precision and high acceleration. It also lends itself to modularity in design for a variety of configurations, including multiple arms. This type of robots is used for loading work pieces in CNC turning centres in flexible turning installations.


![u154](/CIM/Notes/src/u154.png)
# Gantry Robot

# Selective Compliance Assembly Robot Arm (SCARA):

 - This configuration shown below and is horizontally revolute. A robot of this type moves by sweeping over the workspace at a fixed horizontal distance before moving a vertical arm down. This permits a compact and relatively low cost design for small assembly tasks.


![u155](/CIM/Notes/src/u155.png)
# SCARA Robot

# Robot Anatomy

 - A robot joint is a mechanism that permits relative movement between parts of a robot arm. The joints of a robot are designed to enable the robot to move its end-effector along a path from one position to another as desired. The basic movements required for the desired motion of most industrial robots are:

 - horizontal
  - Rotational Movement –
 - This enables the robot to place its arm in any direction on a horizontal direction.

 - horizontal
  - Radial Movement -
 - This helps the robot to move its end-effector radially to reach distant points.

 - horizontal
  - Vertical Movement -
 - This enables the robot to take its end-effector to different heights.

 - These degrees of freedom, in combination with others or independently, define the complete motion of the end-effector. Individual joints of the robot arm are responsible for the accomplishment of different movements. The joint movements are in synergy with the relative motion of adjoining links. Depending on the nature of this relative motion, the joints are classified as prismatic or revolute.
<center><strong>Robot Classification
 - Robots are being classified on the basis of their physical configuration and control systems adopted. These classifications are briefly described as follows:

# Classification on the Basis of Physical Configurations

 - On the basis of physical configuration industrial robots are classified in four different types. They are:

 - i. Cartesian configuration,

 - ii. Cylindrical configuration,

 - iii. Polar configuration, and

 - iv. Jointed-arm configuration.

# Cartesian Configuration

 - Robots having Cartesian configurations consist of links connected by linear joints (L). As the configuration has three perpendicular slides, they are also called rectilinear robots. Robot having a similar configuration is known as Gantry Robots. Its structure resembles a gantry-type crane.

# Cylindrical Configuration

 - In the cylindrical configuration, robots have one rotatory (R) joint at the base and linear (L) joints succeed to connect the links. The space in which this robot operates is cylindrical in shape, hence the name cylindrical configuration.

# Polar Configuration

 - Polar robots have a work space of spherical shape. In general, the arm is linked to the base with a twisting (T) joint and rotatory (R) and or linear (L) joints. The designation of the arm for this arm can be TRL or TRR. Robots with the description of TRL are also called spherical robots. Those having the designation of TRR are called as articulated robots. It resembles a human arm in terms of configuration.

# Jointed-Arm Configuration

 - The combination of cylindrical and articulated configurations is known as jointed-arm configuration. The arm of the robot is connected to the base with a twisting joint. Rotatory joints are used to connect the links in the arm. Generally, the rotation takes place in the vertical plane. Popular robot falling under this category is called SCARA (Selective Compliance Assembly Robot Arm). It is basically used for the assembly purpose.

# Classification based on Control Systems

 - On the basis of the control systems adopted, robots are classified into the following categories:

 - a. Point-to-point (PTP) control robot

 - b. Continuous-path (CP) control robot

 - c. Controlled-path robot

# Point-to-Point (PTP) Control Robot

 - The PTP robot is capable of moving from one point to the other point. The locations are recorded in the control memory. The paths are not controlled by the path guide. Instead the desired path is traced by programming a series of points. Component insertion, spot welding, hole drilling, machine loading, unloading and crude assembly are some of the common applications of this type of robot.

# Continuous-Path (CP) Control Point

 - The movement along the controlled path is performed by the CP robot. Along the controlled path, with CP control, the robot can stop any specified point. In the robot’s control memory, all the points must be stored explicitly. Straight-line motion is being carried out by these types of robots. Some continuous-path controlled robots also have the capability to follow a smooth curve path that has been defined by the programmer. Here, the programmer manually moves the robot arm through the desired path and the controller unit stores a large number of individual point locations along the path in memory.

# Controlled-Path Robot

 - In controlled-path robots, the control equipment can develop paths of different geometry such as straight lines, circles, and interpolated curves with a high degree of accuracy. Good accuracy can be obtained at any point along the specified path. Only the start and finish points and the path definition function must be stored in the robot’s control memory. It is important to mention that all controlled-path robots have a servo capability to correct their path.

# Robotic Applications in the Industry

 - Work environment is one of the several characteristics that should be considered when selecting a robot application. The hazardous characteristics of industrial work tend to promote the substitution of robots for human labour. Hence, robots are being used in a wide field of applications in industry. Currently, robots are mostly used in the field of manufacturing. The applications can usually be classified into following characteristics:

 - i. Material handling

 - ii. Processing operations

 - iii. Assembly and inspection

 - Application of the robots in the industry must be technically and economically viable for the industry.

# Material Handling Applications

 - Material handling applications are those in which the robot moves the materials or parts from one place to another. The robot is equipped with a gripper type of end-effector to accomplish this type of transfer. The gripper must be designed to handle the specific part or parts that are to be moved. Within this application category are the following cases which are

 - i. Material transfer, and

 - ii. Machine loading/unloading.

 - In almost all the material handling applications, the part must be presented to the robot in familiar position and orientation.

# Material Transfer

 - These are the operations in which the robot picks up the parts at one location and place them at a new location. The basic application in this category is pick and place operation, where robot picks up a part and deposits at a new location. Transferring parts from one conveyor to another is a classic example of this application. However, palletizing is a more complex example of the material transfer application. Here, the robots must retrieve parts, cartons, or other objects from one location and deposit them onto a pallet or other container with multiple locations.

# Machine Loading/Unloading Operations

 - In machine loading and unloading operations, the parts are transferred into/from a machine. The three possible scenarios can be machine loading, machine unloading, machine loading and unloading. In the machine loading operations, the robot loads parts into machine, but the parts are unloaded from the machine by some other mechanism. In the unloading operations, the machines are unloaded using the robots. When both the earlier situations are present, then this can be placed into the third category.

 - Numerous applications of machine loading and unloading operations are as follows :

 - i. Die casting operations

 - ii. Metal machining operations

 - iii. Plastic molding

 - iv. Forging

 - v. Heat treating

 - vi. Press working

 - Robots as mentioned earlier are also used in the process industry. Numerous applications in this category are spot welding, continuous arc welding; spray painting, various rotating processes, and machining processes.

# Spot Welding

 - Spot welding is a metal joining process in which two sheet metal parts are fused together at localized points of contact. It has got a widespread use in the automobile industry. The end-effector used here is a spot welding gun used to pinch the car panels together and perform the resistance welding process.

# Continuous Arc Welding

 - Continuous arc welding is used to provide continuous welds rather than points in a spot welding process. As the working condition is tough, therefore automation is recommended in this case. The robotic cell consists of a robot, the welding apparatus (power unit, controller, welding tool, and wire feed mechanism), and a fixture that positions the components for the robot. The fixture might be mechanized with one or two degrees-of-freedom so that it can present different portions of the work to the robot for welding.

# Spray Coating

 - Spray coating makes use of a spray gun directed at the object to be coated. Fluid flows through the nozzle of the spray gun and is dispersed and applied over the surface of the object. Here, robot applications consist of spray coating appliances, automobile car bodies, engines, and other parts, spray painting of wood products, and spraying of porcelain coating on bathroom fixtures.

# Other Processing Applications

 - The list of other industrial processes that are being performed by robots is as follows:

 - i. Drilling, routing and other machining process.

 - ii. Laser cutting.

 - iii. Riveting.

 - iv. Grinding, wire brushing, and similar operations.

 - v. Water jet cutting.

 - In the next section, we detail the assembly and inspection operations performed by the robots.

# Assembly and Inspection

 - Assembly and inspection are hybrids of the previous two application categories: material handling and processing. Assembly and inspection applications can involve either the handling of materials or the manipulation of a tool. Assembly and inspection are traditionally labour-intensive, boring and highly repetitive activities. Hence, they are the fitting cases for the robotic applications.

 - Production rate is one of the important performance measures for such robotic applications. Therefore, industrially relevant problems have been presented and solved in the next section.

# CONVEYORS, AGVS, AUTOMATIC STORAGE AND RETRIEVAL SYSTEMS

 - A material-handling system can be simply defined as an integrated system involving such activities as handling, and controlling of materials. Materials include all kinds of raw material, work-in-progress, sub-assemblies, and finished assemblies. The main motto of an effective material-handling system is to ensure that the material in the right amount is safely delivered to the desired destination at the right time and at minimum cost. It is an integral part of any manufacturing activity. Role of AGVs and Robots have become strategic with respect to the modern material handling practices followed in the present day industry. The next section deals with the automated guided vehicles (AGVs).

# Automated Guided Vehicles

 - Automated guided vehicle systems (AGVs), commonly known as driverless vehicles, are turning out to be an important part of the automated manufacturing system. With the shift from mass production to mid-volume and mid-variety, flexible manufacturing systems, are increasingly in use. They require not only machine flexibility but also material-handling, storage, and retrieval flexibility. Hence, the importance of AGVs has grown in manifold. It is a battery-powered driverless vehicle with programming capabilities for destination, path selection, and positioning. The AGVs belongs to a class of highly flexible, intelligent, and versatile material-handling systems used to transport materials from various loading locations to various unloading locations throughout the facility. The capability related to collision avoidance is nicely inbuilt in AGVS. Therefore, the vehicle comes to a dead stop before any damage is done to the personnel, materials, or structures. They are becoming an integral part of flexible manufacturing system installations.

# Components of AGVS

 - There are four main components of an automated guided vehicle system. They are as follows:

  - The Vehicle:
 - It is used to move the material within the system without a human operator.

  - The Guide Path:
 - It guides the vehicle to move along the path.

  - The Control Unit:
 - It monitors and directs system operations including feedback on moves, inventory, and vehicles.

  - The Computer Interface:
 - It is connected with other computers and systems such as mainframe host computer, the Automated Storage and Retrieval System (AS/RS), and the Flexible Manufacturing System.


![u156](/CIM/Notes/src/u156.png)

 - Now-a-days, AGVS are versatile in nature and possess flexible material-handling system. They use modern microprocessor technology to guide a vehicle along a prescribed path and makes correction if the vehicle strays from the path. A system controller receives instructions directly from the host computer, communicates with other vehicles, and issues appropriate commands to each vehicle. To avoid collision, communication is necessary among the AGVs. To facilitate the communication, they are connected through a wire in the floor or by radio.

# Different Types of AGVS

 - There are different types of automated guided vehicles that are able to cater different service requirements. The vehicle types include:

  - AGVS towing vehicles

  - AGVS unit load transporters

  - AGVS pallet trucks

  - AGVS forklift trucks

  - AGVS light-load transporters

  - AGVS assembly line vehicles

 - The level of sophistication of the AGVS has increased to allow automatic positioning and pickup and drop-off (P/D) of cargo, and they also perform P/D services between machining work centers, storage racks, and the AS/RS. They are also capable of two-way travel on the same path and real-time dispatching under the control of the computer. The different types of AGVS are discussed in the section to follow.


![u157](/CIM/Notes/src/u157.png)

# AGVS Towing Vehicle

 - AGVS towing vehicles were the earliest variety to be introduced. A towing vehicle is an automated guided tractor. A wide variety of tractors can be used, such as flatbed trailers, pallet trucks, custom trailers, and bin trailers. Different types of loading equipment used for loading and unloading the trailer include an AGV-pulled train, hand pallet truck, cranes, forklift truck, automatic transfer equipment, manual labor, shuttle transfer, and programmed automatic loading and unloading device.

# AGVS Pallet Trucks

 - AGVS pallet trucks are designed to lift, maneuver, and transport palletized loads. It is used for picking up or dropping off loads from and on to floor level, than removing the need for fixed load stands. No special accessories are needed for loading and unloading the AGVS pallet except that the loads should be on a pallet. It is basically used in floor-level loading and unloading operation. Loading and unloading can be done in two ways viz. automatically or manually. For the transportation of load, the normal course followed by the vehicle is determined by the storage area destination. Normal operations carried out in pallet trucks are :

 - i. Loads are pulled off onto a spur,

 - ii. Lowering of the pallet forks to the floor,

 - iii. Pulling out from the pallet, and

 - iv. Finally automatically returns empty to the loading area.

# AGVS Forklift Trucks

 - An AGVS forklift truck has the capability to pick up and drop off palletized loads both at floor level and on stands, and the pickup height can be different from the drop-off height. They are capable of picking up and dropping off a palletized load automatically. It has the ability to position its forks at any height so that conveyors or load stands with different heights in the material-handling system can be serviced. AGVS forklift trucks are one of the most expensive AGVS types. Therefore, they are used in the case of full automation. The truck is accoutered with sensors at the fork end, so that it can handle high-level stacking on its own. These systems have the advantage of greater flexibility in integrating with other subsystems with various loading and unloading heights throughout the material handling system.

# AGVS Light Load Transporters

 - They are applied in handling small, light parts over a moderate distance and distribute the parts between storage and number of work stations.

# AGVS Assembly-Line Vehicles

 - AGVS assembly line vehicles are an acclimatization of the light-load transporters for applications involving serial assembly processes. The guided vehicle carries major sub-assemblies such as motors, transmissions, or even automobiles. As the vehicle moves from one station to the next, succeeding assembly operations are performed. After the loading of part onto the vehicle, the vehicle moves to an assembly area and stops for assembly. As the assembly process is completed, the operator releases the vehicle that proceeds to the next part’s staging area for new parts. After that the vehicle moves forward to the next assembly station. The process is repeated until the final unloading station is reached.

 - The main advantage of the AGVS assembly line is its lower expense and ease of installation compared with “hard” assembly lines. The line can be easily reconfigured by altering the guide path and by reprogramming. Variable speeds and dwell intervals can be easily programmed into the system. However, an extensive planning and complex computer control is needed in the case of overall integration. Some of the guiding factors determining the functioning of the AGVS are:

 - i. Guidance Systems

 - ii. Routing

 - iii. AGVS Control Systems

 - iv. Load Transfers

 - v. Interfacing with other subsystems

# Guidance Systems for AGVS

 - The main purpose of a guidance system is to keep the vehicle in the predestinated path. The main advantage of AGVS guidance system is that the guide path can be changed easily at low cost compared to the high cost of modifying fixed-path equipment such as conveyors, chains, and tow lines. Many guidance systems are available and their selection will depend on need, application, and environmental constraints. Some of the familiar guidance systems are wire-guided guidance system, optical guidance system, inertial guidance system, infrared guidance system, laser guidance system, and teaching-type guidance system.

# Routing of the AGVS

 - AGVS routing means determining how the vehicle conforms the path and takes a shortest path between the two points. The commonly used methods are: “frequency selection method” and the “path switch selection method”.

# AGVS Control Systems

 - Three types of AGVS control systems are available.

  - Computer-controlled system

  - Remote dispatch control system

  - Manual control system

# Computer Controlled System

 - Here, all the exchanges and AGVS vehicle movements are controlled and monitored by the system controller. The guide path controller controls the guide path of the AGVS and transfers the information to the AGVS process controller. Movements of AGVS vehicle are directly controlled by the AGVS process controller.

# Remote Dispatch Control System

 - Here, a human operator controls the movement of AGVS through a remote control station. The control system sends destination instructions directly to the vehicle.

# Manual Control System

 - In this type of system, the operator loads the vehicle and enters a destination into the onboard control panel of the vehicle. The efficiency of the system depends on the skill of the operator.

# FUNCTIONS OF STORAGE SYSTEM AND DEFINITION OF AS/RS

 - An automated storage/retrieval system (AS/RS) can be defined as a storage system under which a defined degree of automation is to be implemented to ensure precision accuracy and speed in performing storage and retrieval operations. These automated storage and mechanized systems eliminate human intervention in performing basic sets of operations that includes:

  - Removal of an item from a storage location automatically

  - Transferring the above item to a specific processing or interface point

  - After receiving an item from a processing or interface point, it is automatically stored at a predetermined location.

 - A list of possible objectives that a company may want to achieve by installing an automated storage system is presented in Table below.

# Objectives for Installing an Automated Storage System in a Factory


![u158](/CIM/Notes/src/u158.png)

# AS/RS COMPONENTS AND TERMINOLOGY

 - An AS/RS consists of one or more storage aisles that are serviced by a storage/retrieval (S/R) machine. The stored materials are held by storage racks of aisles. The S/R machines are used to deliver and retrieve materials in and out of inventory. There are one or more input/output stations in each AS/RS aisle for delivering the material into the storage system or moving it out of the system. In AS/RS terminology, the input/output stations are called pickup-and-deposit (P and D) stations.


![u159](/CIM/Notes/src/u159.png)
# Generic Structure of as AS/RS


&nbsp;



 - It is the three-dimensional space in the storage racks used to store a single load unit of material.

# Storage Racks

 - This structural entity comprises storage locations, bays and rows.

# Bay

 - It is the height of the storage rack from floor to the ceiling.

# Row

 - It is a series of bays placed side by side.

# Aisle

 - It is the spacing between two rows for the machine operations of AS/RS.

# Aisle Unit

 - It encompasses aisle space and racks adjacent to an aisle.

# Storage Structure

 - It is the rack framework, made of fabricated steel that supports the loads contained in the AS/RS and is used to store inventory items.

# Storage/Retrieval Machine

 - It is used to move items in and out of inventory. An S/R machine is capable of both horizontal and vertical movement. A rail system along the floor guides the machine and a parallel rail at the top of the storage structure is used to maintain its alignment.

# Storage Modules

 - These are the unit load containers used to hold the inventory items. These include pallets, steel wire baskets and containers, pans and special drawers. These modules are generally made to a standard base size capable of being stored in the structure and moved by the S/R machines.

# Pickup and Deposit (P/D) Stations

 - P/D stations are where inventory are transferred into and out of the AS/RS. They are generally located at the end of the aisles to facilitate easy access by the S/R machines from the external material-handling system. The location and number of P/D stations depends upon the origination point of incoming loads and the destination of output loads.

# TYPES OF AS/RS

 - Several important categories of AS/RS can be distinguished based on certain features and applications. The following are the principle types:

# Unit Load AS/RS

 - The unit load AS/RS is used to store and retrieve loads that are palletized or stored in standard-sized containers. The system is computer controlled. The S/R machines are automated and designed to handle the unit load containers. Usually, a mechanical clamp mechanism on the S/R machine handles the load. However, there are other mechanisms such as a vacuum or a magnet-based mechanism for handling sheet metal. The loads are generally over 500 lb per unit. The unit load system is the generic AS/RS.

# Mini Load AS/RS

 - This system is designed to handle small loads such as individual parts, tools, and supplies that are contained in bins or drawers in the storage system. Such a system is applicable where the availability of space is limited. It also finds its use where the volume is too low for a full-scale unit load system and too high for a manual system. A mini load AS/RS is generally smaller than a unit load AS/RS and is often enclosed for security of items stored.

# Deep-lane AS/RS

 - This is a high-density unit load storage system that is appropriate for storing large quantities of stock. The items are stored in multi deep storage with up to 10 items in a single rack, one load behind the next. Each rack is designed for flow-through, with input and output on the opposite side. Machine is used on the entry side of the rack for input load and loads are retrieved from other side by an S/R- type machine. The S/R machines are similar to unit load S/R machine except that it has specialized functions such as controlling rack-entry vehicles.

# Man-on-board AS/RS

 - This system allows storage of items in less than unit load quantities. Human operator rides on the carriage of the S/R machine to pick up individual items from a bin or drawer. The system permits individual items to be picked directly at their storage locations. This provides an opportunity to increase system throughput. The operator can select the items and place them in a module. It is then carried by the S/R machine to the end of the aisle or to a conveyor to reach its destination.

# Automated Item Retrieval System

 - This system is designed for retrieval of individual items or small product cartoons. The items are stored in lanes rather than bins or drawers. When an item is retrieved from the front by use of a rear-mounted pusher bar, it is delivered to the pickup station by pushing it from its lane and dropping onto a conveyor. The supply of items in each lane is periodically replenished and thus permitting first-in/first-out inventory rotation. After moving itself to the correct lane, the picking head activates the pusher mechanism to release the required number of units from storage.


&nbsp;

# LEAN MANUFACTURING SYSTEMS

 - Lean manufacturing or lean production are reasonably new terms that can be  traced to Jim Womack, Daniel Jones and Daniel Roos’ book, The Machine that changed the world [1991]. In the book, the authors examined the manufacturing activities exemplified by the Toyota Production System. Lean manufacturing is the systematic elimination of waste. As the name implies, lean is focused at cutting “fat” from production activities. It has also been successfully applied to administrative and engineering activities as well. Although lean manufacturing is a relatively new term, many of the tools used in lean can be traced back to Fredrick Taylor and the Gilbreaths at the turn of the 20th century. What Lean has done is to package some well-respected industrial/manufacturing engineering practices into a system that can work in virtually any environment.

# The 3 M’s of Lean

 - Lean manufacturing is a Japanese method focused on 3M’s. These Ms are: muda, the Japanese word for waste, mura, the Japanese word for inconsistency, and muri, the Japanese word for unreasonableness. Muda specifically focuses on activities to be eliminated. Within manufacturing, there are categories of waste. Waste is broadly defined as anything that adds cost to the product without adding value to it. Generally, muda (or waste) can be grouped into the following categories:

 1. Excess production and early production

 2. Delays

 3. Movement and transport

 4. Poor process design

 5. Inventory

 6. Inefficient performance of a process

 7. Making defective items

# Definition of “Lean”

 - •Half the hours of human effort in the factory

 - •Half the defects in the finished product

 - •One-third the hours of engineering effort

 - •Half the factory space for the same output

 - •A tenth or less of in-process inventories

# This was an early definition of Lean

 - Excess production results in waste because it captures resources too early and retains the value that is added until the product can be used (sold). In today’s highly changing society, many items produced before they can are sold to a specific customer often go obsolete before demand is realized. This means that a perfectly good product is often scrapped because it is obsolete. Producing a product simply to keep a production resource busy (either machine, operator or both) is a practice that should be avoided.

 - Delays, such as waiting for raw material, also result in the poor use of capacity and increased delivery time. Raw materials and component parts should be completed at approximately the time that they will be required by downstream resources. Too early is not good, but late is even worse.

 - Movement and transportation should always be kept to a minimum. Material handling is a non-value added process that can result in three outcomes:

 - 1) The product ends up at the right place at the right time and in good condition.

 - 2) The part ends up in the wrong place.

 - 3) The part is damaged in transit and requires rework or scrap.


![u160](/CIM/Notes/src/u160.png)

 - Two of the three outcomes are no desirable, which further leads to minimizing handling. Because material handling occurs between all operations, when possible, the handling should be integrated into the process, and the transport distances minimized.

 - A poorly designed process results in overuse of manufacturing resources (men and machines). There are no perfect processes in manufacturing. Generally, process improvements are made regularly with new efficiencies embedded within the process. Continuous process improvement is a critical part of Lean Manufacturing.

 - Excess inventory reduces profitability. Today, it is not uncommon for a manufacturer to store a supplier’s product at the production site. The supplier, right up until the time that they are drawn from inventory, owns the materials. In many ways this is advantageous to both the user and supplier. The supplier warehouses his material offsite, and the user does need to commit capital to a large “safety stock” of material.

 - Insufficient (or poor) process performance always results in the over utilization of manufacturing resources and a more costly product. There is no optimal process in that improvements can always be made; however, many processes operate far below the desired efficiency. Continuous process improvement is necessary for a manufacturing firm to remain competitive. Excess movement or unnecessary part handling should be the first targets of waste elimination.

 - Poor quality (making defects) is never desirable. Labor and material waste results from producing any defect. Furthermore, the cost of mitigating poor quality (rework) can often exceed the price of the product. A critical balance between processing speed and quality exists. A process should be run as fast as possible without sacrificing acceptable quality. From the above discussion, it should be obvious that waste is a constant enemy of manufacturing. Waste elimination should be an on-going process that focuses on improving a process regularly. Regular reviews and worker input should be conducted as often as allowable. The second “M” is for mura, or inconsistency. Inconsistency is a problem that increases the variability of manufacturing. Mura is evidenced in all manufacturing activities ranging from processing to material handling to engineering to management.

# The 5 S’s of Lean

 - Much of Lean manufacturing is applying “common sense” to manufacturing environments. In implementing Lean, 5 S’s are frequently used to assist in the organization of manufacturing. The 5 S’s are from Japanese and are:

  - Seiri (sort, necessary items)

  - Seiton (set-in-order, efficient placement)

  - Seison (sweep, cleanliness)

  - Seiketsu (standardize, cont. improvement)

  - Shitsuke (sustain, discipline)


![u161](/CIM/Notes/src/u161.png)

# AGILE MANUFACTURING SYSTEMS

 - World-class performance is a moving target that requires constant attention, effort and the process is a never ending journey. In the past, economies of scale ruled the manufacturing world and everybody knew that mass production and full utilization of plant capacity was the way to make money. This style of manufacturing resulted in inflexible plants that could not be easily reconfigured, and were associated with swollen raw materials, work-in-process and finished goods inventories. For the elimination of excess inventory, shortened lead-times, requirement of flexibility in the flow lines and to enhance the advanced levels of quality in both products and customer service, industry analysts have popularized the terms `world-class manufacturing’ and agile manufacturing.

 - Facing the competitive market, industrial manufacturers are hard pressed to adopt novel strategies and technologies to enhance product quality, to cut manufacturing cost and to reduce product lead time. Agile Manufacturing is primarily a business concept. Its aim is quite simple - to put our enterprises way out in front of our primary competitors. In Agile Manufacturing, our aim is to combine our organization, people and technology into an integrated and coordinated whole. Agile manufacturing can be defined as the capability to survive and prosper in a competitive environment of continuous and unpredictable change by reacting quickly and effectively to changing markets, driven by customer-designed products and services.

 - The concept of agility refers to a business model which makes an organization immune to damage caused by unpredictable events and changing circumstances. This is achieved by the organization being able to react and adapt rapidly. The coming surprises of the future will not make an agile enterprise vulnerable because that enterprise will have already put in place a set of business practices, organization-wide culture changes and technology which will allow it to be prepared for any change in circumstances, market forces or customer needs. Agile Manufacturing is a combination of speed and flexibility that is difficult to achieve because it requires radical changes to traditional thinking.

 - The concept of Agile Manufacturing is built around the synthesis of a number of enterprises that each have some core skills or competencies which they bring to a joint venturing operation, which is based on using each partner’s facilities and resources. Central to the ability to form these joint ventures is the deployment of advanced information technologies and the development of highly nimble organizational structures to support highly skilled, knowledgeable and empowered people. Agile Manufacturing builds on what is good in lean manufacturing and uses what can be adapted to western cultures, but it also adds the power of the individual and the opportunities afforded by new technologies.

 - Agile Manufacturing enterprises will be capable of rapidly responding to changes in customer demand. They will be able to take advantage of the windows of opportunities that, from time to time, appear in the market place. With Agile Manufacturing it is possible to develop new ways of interacting with customers and suppliers. The customers will not only be able to gain access to the products and services, but will also be able to easily access and exploit the competencies, so enabling them to use these competencies to achieve the things that they are seeking. The goal of this paper is to review several different aspects of agile manufacturing (AM) and to identify key aspects of agile manufacturing and outlook for the future of agile manufacturing technologies.

# Comparison of Agile manufacturing and other manufacturing methods:

 - In traditional manufacturing system the long cycle time is with the high inventory which causes delay in the goods delivery. The problem here is the lack of strategy and no employee involvement and financial secrecy and record inaccuracy. In the context of world class manufacturing the advantages are long term profitability, productivity improvement and less time to market in contrast to the traditional manufacturing system. The agile manufacturing system focuses in the integration of design and manufacturing and every aspect of manufacturing under one roof.

 - In Contrast to the traditional manufacturing strategy, the agile manufacturing concentrates on the customer enrichment, competitiveness through co-operation and this could be achieved by integration of the people, information and technology on a same roof. This could also be achieved by highly educated and trained workforce. Enhancing the competitiveness among the competitors and built the cooperation from all the enterprises and thus influence the knowledge sharing and sharing the technological innovations.

# Needs of agile manufacturing system

 - The key to agility however, lies in several places. An agile enterprise needs highly skilled and knowledgeable people who are flexible, motivated and responsive to change. An agile enterprise also needs new forms of organizational structures which engender non-hierarchical management styles and also stimulate and support individuals as well as cooperation and team working. Agile manufacturing enterprises also need advanced computer based technologies to integrate information and to share the knowledge base. To achieve Agile Manufacturing, enterprises will have to bring together a wide range of knowledge in the design of a manufacturing system that encompasses suppliers, customers. It should also addresses all dimensions of the system including organization, people, technology, management accounting practices, etc. Most importantly the inter-related nature of all these areas needs to be recognized and an interdisciplinary manufacturing systems design method adopted as standard practice.

 - This means going beyond the multidisciplinary approaches that are currently being adopted and looking at areas between professions.

# Challenges of Agile manufacturing

 - Interdisciplinary design will form the basis of designing Agile Manufacturing systems in the new knowledge intensive era. Interdisciplinary design however, means more than just applying knowledge from other domains, such as psychology and organizational science, to the design of Agile Manufacturing systems. It also implies looking into the unexplored areas between these disciplines and the areas where they overlap, to find a new insights, new knowledge, new and original solutions. This is one of the most important challenges that managers and system designers and integrators will face in the years ahead. The interdisciplinary design leads us to new approaches and new ways of working and of thinking. However, to successfully adopt an interdisciplinary design method, we also need to:

  - Challenge the present design strategies and develop new and better approaches;

  - Question the established and cherished beliefs and theories, and develop new ones to replace those that no longer have any validity;

  - Consider how to address organization, people and technology, and other issues in the design of manufacturing systems, so that the systems can achieve the better performance for the agile manufacturing environment and for the people who form a part of this system.

  - Make use of the innovative technology in a way that makes human skill, knowledge, and intelligence more effective and productive which allows industries to tap into the creativity and talent of all people in an enterprise.

 - The challenges that face with respect to all these issues are enormous. In the world of manufacturing the challenges and problems are very complex. There are a massive number of interconnections between the various components and elements. A manufacturing enterprise is so complex that, in the past, it has been impossible to cope with it as a whole, and it has been necessary to reduce it into manageable areas which have tended to be examined separately.

# Agile Manufacturing World Wide Scenario

 - The Agile Manufacturing Enterprise Forum (AMEF) at the Iacocca Institute of Lehigh University was created to disseminate the ideas of agile manufacturing and to increase the pace and scope of the transition to an agile manufacturing industry. The Agile Manufacturing Initiative aims to develop, demonstrate, and evaluate the advanced design, manufacturing and business transaction processes in the agile environment. The Concurrent Technologies Corp. (CTC) is developing an agile manufacturing test bed to provide Department of Defense (DoD) with increased weapon system readiness and added system mobility. The Agile Aerospace Manufacturing Research Center (AAMRC) at the University of Texas at Arlington is conducting research on agile business practices, business process identification and characterization, and enabling technologies. The Manufacturing Research, Education and Outreach Program at the University of Illinois at Urbana-Champaign is developing computer integrated manufacturing and machine tool systems. The Electronic Agile Manufacturing Research Institute (EAMRI) at Rensselaer Polytechnic Institute (RPI) is focusing on electronics product realization in distributed manufacturing environments using improved information infrastructures and architectures. Agile manufacturing makes use of modern information technology to form virtual enterprises, which agilely respond to the changing market demands. A virtual enterprise, different from a traditional enterprise, is constructed by partners from different companies, who collaborate with each other to design and manufacture high quality and customized products. It is product-oriented; team-collaboration styled, and featured as fast and flexible. Frequent and dynamic interactions among partners in agile manufacturing enterprises entail the crucial role of an Agile Manufacturing Information System (AMIS). It is up to the AMIS to provide partners with integrated and consistent information, as well as to manage partner transactions accessing the information.

# Transition to Agile Manufacturing

 - All the relevant dimensions of Agile manufacturing, such as organization, people, technology, management accounting, etc. are however, all written in different books and taught by different people. To make the transition to Agile Manufacturing we need to:

  - Examine and define the underlying conceptual framework on which Agile Manufacturing enterprises will be built.

  - Explore and understand the nature of the mass production paradigm and the nature of the cultural and methodological difficulties involved in the transition to Agile Manufacturing.

  - Define a methodology for designing a 21st century manufacturing enterprise. The agile manufacturing is based on a systems perspective o technology, organization and people, tied to clear business vision and goals. This will help the researchers to understand the full complexity of designing a 21st century manufacturing enterprise that is agile manufacturing system.

# Characteristics of Agile Manufacturing

 - The characteristics of agile manufacturing are at the strategic level where strategic dimensions of agile manufacturing are identified as follows:

 1. Enriching the customer - an agile company is one that is perceived by its customers as enriching them in a significant way, not only itself

 2. Cooperating to enhance competitiveness – cooperation internally and with other companies is an agile competitor's operational strategy of first choice

 3. Organizing to master change and uncertainty - an agile company is organized in such a way as to allow it to thrive on change and uncertainty, its structure is flexible enough to allow rapid configuration of human and physical resources;

 4. Leveraging the impact of people and information - an agile company's management nurtures an entrepreneurial company culture that leverages the impact of people and information on operations.

 - From these strategic dimensions of agility, one can move to consider the tactical and technological dimensions. In this effort, the AMRIs are concerned with research and development efforts to better understand the enabling technologies for agile manufacturing.

 - The benefits of Agile Manufacturing are Short time-to market, fast new product development, Short/fast order processing, Low volumes, Low quantities, High product mix, Configurable components, Fast supplier deliveries, Short lead times, Short cycle times, Highly flexible and responsive processes, Highly flexible machines and equipment, Use of advanced CAD/CAM, Quick changeover, Empowered employees.

# Reconfigurable Manufacturing Systems

 - In an era when new product styles are being introduced with ever-shortening life cycles, the cost of designing, building, and installing a new manufacturing system every time a new part or product must be produced is becoming prohibitive, both in terms of time and money. One alternative is to reuse and reconfigure components of the original system in a new manufacturing system. In modern manufacturing engineering practice, even single model manufacturing systems are being built with features that enable them to be changed over to new product styles when this becomes necessary. These kinds of features include:

  - Ease of mobility. Machine tools and other production machines designed with a three point base that allows them be readily lifted and moved by a crane or forklift truck. The three-point base facilitates leveling of the machine after moving

  - Modular design of system components. This permits hardware components from different machine builders to be connected together

  - Open architecture in computer controls. This permits data interchange between software packages from different vendors.

  - CNC workstations. Even though the production machines in the system are dedicated to one product, they are nevertheless computer numerical controlled to allow for upgrades in software, engineering changes in the part currently produced, and changeover of the equipment when the production run finally ends

# HOLONIC MANUFACTURING SYSTEMS

# Holon

 - The holonic concept was developed by the philosopher Arthur Koestler in order to explain the evolution of biological and social systems. On the one hand, these systems develop stable intermediate forms during evolution that are self-reliant. On the other hand, in living and organizational systems it is difficult to distinguish between “wholes” and “parts”: almost everything is both a whole and a part, at the same time. These observations led Koestler to propose the word “holon”, which is a combination of the Greek word “holos”, meaning whole, and the Greek suffix “on”, meaning particle or part, as in proton or neutron. Koestler observed that, in living organisms and in social organizations, which are entirely self-supporting, noninteracting entities did not exist. Every identifiable unit of organization, such as a single cell in an animal or family unit in a society, comprises more basic units (plasma and nucleus, parents and siblings), while at the same time forming a part of a larger unit of organization (a muscle tissue or a community). The strength of holonic organization, or holarchy, is that it enables the construction of very complex systems that are nonetheless efficient in the use of resources, highly resilient to disturbance (both internal and external), and adaptable to changes in the environment in which they exist. Within a holarchy, holons may dynamically create and change hierarchies. Moreover, holons may participate in multiple hierarchies simultaneously. Holarchies are recursive in the sense that a holon may itself be an entire holarchy that acts as an autonomous and cooperative unit in the first holarchy.

 - The stability of holons and holarchies stems from holons being self-reliant units, which have a degree of independence and handle circumstances and problems on their particular level of existence without asking higher-level holons for assistance.

 - Holons can also receive instructions from and, to a certain extent, be controlled by higher-level holons. This self-reliant characteristic ensures that holons are stable and able to survive disturbance. The subordination to higher-level holons ensures the effective operation of the larger whole.

# Holonic Manufacturing Systems – HMS

 - The application of holonic concepts to manufacturing was initially motivated by the inability of existing manufacturing systems

 - (i) To deal with the evolution of products within an existing production facility and

 - (ii) To maintain satisfactory performance levels outside normal operating conditions. Suda introduced the concept of holonic manufacturing in the early 1990s to address the challenge for manufacturing in the 21st century.

 - Teams of industry experts, scientists, and engineers from the world’s leading industrial nations worked together from 1992 to 1994 to build and test a framework for international collaboration in intelligent manufacturing systems (IMS). The experiences of teams coming together from Australia, Canada, Europe, Japan and the USA to work for one year on collaborative “test case” projects formed part of a two-year feasibility study that began in February 1992. This feasibility study proved that this kind of international collaboration could achieve significant results in a relatively short time.

 - A holonic manufacturing system is based on the concept of “holonic systems”, developed by Arthur Koestler. Holons in a holonic manufacturing systems assist the operator in controlling the system: holons autonomously select appropriate parameter settings, find their own strategies and build their own structure. Koestler also points out that holons are autonomous self-reliant units, which have a degree of independence and handle contingencies without asking higher authorities for instructions. Simultaneously, holons are subject to control from (multiple) higher authorities. The first property ensures that holons are stable forms, which survive disturbances. The latter property signifies that they are intermediate forms, which provide the proper functionality for the greater whole. Finally, Koestler defines a holarchy as a hierarchy of self-regulating holons that function

 - a) As autonomous wholes in supra ordination to their parts,

 - b) As dependent parts in subordination to controls on higher levels,

 - c) In coordination with their local environment.

 - Work in the HMS program has translated these concepts to the manufacturing world, viewing the manufacturing system as one consisting of autonomous modules (holons) with distributed control. The goal is to attain the benefits that holonic organization provides to living organisms and societies, in manufacturing, i.e., stability in the face of disturbances, adaptability and flexibility in the face of change, and efficient use of available resources. The HMS concept combines the best features of hierarchical and heterarchical organization. It preserves the stability of hierarchy while providing the dynamic flexibility of heterarchy. The HMS consortium developed the following list of definitions to help understand and guide the translation of holonic concepts into a manufacturing setting

 - Holonic Manufacturing Systems

  - Holon: An autonomous and cooperative building block of a manufacturing system for transforming, transporting, storing and/or validating information and physical objects. The holon consists of an information processing part and often a physical processing part. Figure below shows the holon general architecture widely used in the field. A holon can be part of another holon.

  - Autonomy: The capability of an entity to create and control the execution of its own plans and/or strategies.

  - Cooperation: A process whereby a set of entities develops mutually acceptable plans and executes those plans.

  - Holarchy: A system of holons that can cooperate to achieve a goal or objective. The holarchy defines the basic rules for the cooperation of the holons and thereby limits their autonomy.

  - Holonic manufacturing system: a holarchy that integrates the entire range of manufacturing activities from order booking through design, production, and marketing to realize the agile manufacturing enterprise.


![u162](/CIM/Notes/src/u162.png)
# Holon general architecture

# CAPACITY REQUIREMENTS PLANNING (CRP)

 - MRP does not consider available capacity and often formulates production plans not possible within a given specified plant capacity. Capacity Requirements Planning (CRP) takes planned orders from MRP and open (release) shop orders, and translates work orders into hours of work (pre-set standards) on a work centre basis. CRP then, using the cumulative lead times, allocates the work required for each order to the appropriate work centres for the time period that the order will be in that work centre. CRP considers many factors in allocating the load-queue time, move time, machine and many others. In scheduling, CRP can start from current date and schedule the job to completion (forward scheduling) or using the due date for the order, schedule backward to determine the start date of the job (backward scheduling).

 - There are two types of loading in CRP: finite and infinite. With finite loading, CRP considers the total capacity of a work centre and does not load beyond that point. Infinite loading loads all work for the period into the appropriate work centres then produces over and under load reports showing where more or less capacity are needed to efficiently handle the load. Although they may generate suggestions, most MRP systems require human intervention to help balance the capacity and load. A planner can decide whether delaying the order release, subcontracting the job, splitting the job into several smaller jobs, routing through an alternative work centre, or authorizing overtime will best eliminate the over-under load on the work centre and still get the job done on time. Another aspect of CRP is Input/Output control (I/O). I/O control monitors the amount of work going into and coming out of a work centre and compares it to a standard or expected amount. A back log will develop behind any work centre that continually puts out less work than it takes in. CRP and I/O control are good tools for monitoring the shop floor for bottlenecks and unused capacity.


![u163](/CIM/Notes/src/u163.png)
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
