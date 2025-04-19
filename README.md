# Building-Search-Engine-using-Machine-Learning-Technique
 👉  Search engines provide a simple interface for searching for user query and displaying results in  the form of the web address . This project proposed a search engine using Machine Learning  technique that will give more relevant web pages at top for user queries.
# Key INsights:
1. EXISTING SYSTEM : Information retrieval is to retrieve the information resources that we are interested in or extract whatever information we need. Information Retrieval (IR) may deal with the organization, storage, retrieval and evaluation of information from documents, particularly textual information. But we cannot give the ranks to those document.
2.PROPOSED SYSTEM : In this project author is using machine learning algorithms called SVM and XGBOOST to predict search result of given query and building search engine with machine learning algorithms. To train this algorithm author is using website data and then this data will be converted to numeric vector called TFIDF (term frequency inverse document frequency). TFIDF vector contains average frequency of each word. The proposed search engine is very useful for finding out more relevant URLs for given keywords.
 # SYSTEM DESIGN:
 1. UML DIAGRAMS:UML stands for Unified Modeling Language. UML is a standardized general-purpose modeling language in the field of object-oriented softwarengineering. The standard is managed, and was created by, the Object Management Group The goal is for UML to become a common language for0 creating models of object-oriented computer software. In its current form UML is comprised of two major components a Meta-model and a notation. In the future, some form of method or process may also be added to or associated with, UML the unified Modeling Language is a standard language for specifying, Visualization, Constructing and documenting the artifacts of 
software system, as well as for business modeling and other non-software systems. the UML represents a collection of best engineering practices that have provensuccessful in the modeling of large and complex systems.
2.CLASS DIAGRAM: The class diagram is used to refine the use case diagram and define a detailed design of the system. The class diagram classifies the actors defined in the use case diagram into a set of interrelated classes. The association between the classes can be either an "is-a" or "has-a" relationship.
# SYSTEM TESTING: 
1.UNIT TESTING: Unit testing, a testing technique using which   individual modules are tested to determine if there are issues by the developer himself.it isconcerned with functional correctness of the standalone modules. The main aim is to isolate each unit of the system to identify, analyses and fix the defects.

2.DATA FLOW TESTING:Data flow testing is a family of testing strategies based on selecting paths through the program’s control flow in order to explore sequence of events related to the status of Variables or data object. Dataflow Testing focuses on the points at which variables receive and the points at which these values are used. 

3.INTEGRATION TESTING: Integration Testing done upon completion of unit testing, the units or modules are to be integrated which gives raise too integratiotesting. The purpose of integration testing is to verify the functional, performance, and reliability between the modules that are integrated.
# Tools and Technologies:
1.Python:Pands,Numpy,matplotlib,Seaborn,Scipy.stats
2. Technology: Machine Learning.
# CONCLUSION: 
Search engines are very useful for finding out more relevant URLs for given keywords. Due tothis, user time is reduced for searching the relevant web page. For this, Accuracy is a very important factor. From the above observation, it can be concluded that XGBoost is better in terms of accuracy than SVM and ANN. Thus, Search engines built using XGBoost and PageRank algorithms will give better accuracy.
