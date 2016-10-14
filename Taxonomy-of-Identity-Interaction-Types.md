## Taxonomy of Identity Interaction Types

Identity is socially constructed and contextual.  This is an over arching definition of identity that covers both the social and the technology aspects of it.  

We create the social contexts in which we interact with each other and via the communications in those interaction co-create and co-form identity who we are (inside) how we present ourselves to be this in turn influences how we are seen and and how we are seen in turn influences and has an affect of who we are inside. 

[Diagram] this may take me another day to get posted in here. 

We, that is human beings working together, create the technical systems that digital representations of identities exist.  The question that the design shop is looking at and IIW has been considering for 12 years and Planetwork before that began considering in 2000 is looking at how are people represented and empowered with the representation of themselves in the digital world their “digital identity”.  

It is important that there is not one type of interaction in identity. The contexts where we need digital identity are varied and understanding them clearly is the aim of this paper. 

The original computers didn’t even have different accounts for different users. These were created to support different researchers being able to login to mainframe computers.  This is the genesis of the “user-name” and password that we still have today. 

So this is the “one” computer in a lab and all the different users. 

Next we had Higher Education institutions creating accounts for students and faculty to access things like e-mail. 

#### School -> Student
#### School -> Faculty/Staff  (also see Business -> Empoloyee)

When looking at the history of identity we see that there is a reason that higher education has often lead in the field, because they were doing it first and at scale. They have organizations the size of very large enterprises and they also do not have a profit motive, but rather a motivation to serve their constituents, students and faculty. 

#### Business -> Employee
The other identity relationship that has been critical to the evolution of the industry is the relationship between the Business and its Employees. Businesses had a strong incentive to create tools and systems for their employees to login to the business systems they use to their jobs. This created a strong market for tools in this space. There was a whole flowering of companies with products in this area and a trade show for it Digital Identity World that I first attended in 2004.  

The field / context is called Enterprise Identity Management also known as Identity and  Access Management - IAM.  It is totally focused on employee authentication, and then authorization (permission) to the tools and system they use for doing their job. The term single-sign-on emerged in this market. How do you get employees to login “once” and have this work across all the enterprise systems they should have access too. this was solved in two ways one with a directory of employees - a common one in use is Microsoft’s Active Directory just referred to as AD. There was also the innovation of a standard that all the different applications speak so that they can support this ability to have single sign on - SAML - security assertion markup language. 
Specialized tools have arisen in the space such as Privileged Account Management for administrative accounts creating accountability amongst the employees that use those account. 

#### Business -> Consumer   Customer -> Business
The relationship between a business and its customers (or potential customers) is quite different then that between a business and its employees. This is one of the reasons that the user-centric identity community found itself forming in the shadow of the enterprise identity management.  The community that lead to IIW happening really connected first at Digital Identity World in the fall of 2004.  The arrows point both ways.  Businesses for their own digital systems have identifiers for their customers and collect data about their interactions with customers over time. This is what Customer Relationship Management software does. 

Customers interacting with a Business also bring their own identity with them to interact with business. At the most basic level they bring a name with them that is likely the one they use in other contexts. They also potentially have data and attributes about themselves that they could share.  The original vision for OpenID and LID that merged was that people could bring with them a URL based identifier for themselves to Businesses they interacted with. 

#### Busness -> Business
Businesses do Business with Businesses. They do this with employees who connect with and interact with their business partners. The conversation early on in the enterprise identity management market talked about federation - how do the employees of one company get recognized by another companies digital system. This is key for one reason in particular if Company A needs to have interactions with an employee from Company B…the Company B should be the one issuing and managing their identity.  This is a common enterprise challenge and another application of SAML is in supporting federations. A key issue with federation is the it is not just technical it also requires legal agreements between the companies - federation agreements. 

#### School -> School 
Since the early days of the internet in the 1960’s when it was an experimental network between higher education institutions its been doing federation. They have been working on innovating the standards needed for it. This has included standards that permit access to resources across institutions without revealing the identity of the person accessing the resource the profile of  SAML that does this is called Shibboleth. This sector continues to innovate extensively 

#### Business -> Governmnet
Businesses need to manage their relationships with governments and vise versa. They do this via employees who work for them. Right now it is not clear If governments have in any systemic way worked to address how to support this type of interaction.  It seems that some sort of privileged account management tool would be good approach. I have heard that in some European contexts particular employees have to use their government issued ‘citizen’ identity to authenticate into government systems as an agent of the business. 


#### Government -> Citizen (Constituent - governments also interact with non-citizens)
The Government Citizen relationship is a special one. It is in some ways at the core of identity systems at least in the west. When people begin life their parents apply for and get a certificate of birth. This document then becomes the basis of activity including enrolling the child in school, or in sports leagues.  Then as we grow older this certificate lets us open a bank account and get a drivers license and then a passport.  The government in this case is the authoritative around a key attribute -  date of birth.  They are the “attribute” provider for this particular attribute.  This document is typically issued by a provincial/state level government (in Canada and Australia) and  in the United States this issued at the county level (there are 5400 counties in the US). 

When a child is born they are also given a by the federal government a Social Security Number (in Canada this is called a Social Insurance Number) this provides the federal government a persistent correlatable identifier for each person relative to their interactions with the government particularly as it relates to taxation and issuance of social security payments. The government issues this number to you - it is also the authoritative source for this attribute. 

The challenge for governments is that they are both attribute or identity providers AND many interactions the government has with citizens involve their interaction with the government they are the relying party - they need to trust the attributes provided by a different part of the government. 

#### Government -> Governmnet
There is more then one level of government - how are these supported in interacting with each other? I don’t know that I have seen an work specifically around this problem area. The European work on eIDAS does identify this use-case area. 

#### Citizen -> Citizen   (Although I like Netizen)
This is Citizen to Citizen  (although I lean towards the tern Netizen rather then Citizen) a lot of what is happening on social media sites is about how interacting with other people (along with interacting with the underlying service or business). In the context of this the service or business rather then selling something to the individual they are monetizing the people. 

Early interactions on the web and in online communities or even just usenet list serves were primarily in this realm - people relating to people without a commercial or other incentive. 


#### Civil Society -> Citizens
Businesses connect to people for a whole set of reasons that have to do with selling them goods or services.  There is a vast number of organizations that are set up within civil society these include religious congregations, sports leagues, dance and musical troops, voluntary associations.  All of them need to interact with their constituency.   There are also a whole set of organizations that provide social services to clients that also need to interact with them. While the dynamic can be similar to the B -> C relationship is its own set of use cases that needs to be considered. 

#### Citizens -> Self Organizing
With the advent of digital identities for people new possibilities for informal organization of people emerges. Often this informal grouping happens on platforms like Facebook where people form a “group” about xyz.  There is also the possibility outside of these commercial platforms how do people just connect and organize in their local neighborhoods. 

#### Delegation and Stewardship 
With many of the above identity constellations there is also the need to consider how delegation and stewardship can work effectively at scale. Because the starting point of the whole field was the  employer - employee relationship where delegation and stewardship were not needed.  When we get out into the world of people across their whole lifecycle of humans. Parents are the stewards of their children’s identities until they are old enough to manage them themselves. There are physically and mentally disabled people who through their whole lives have a need for identity stewardship relative to online interactions. Then there is the case of elders who are to old to manage their identities on their own. In the middle are fully capable people who want to delegate one aspect of identity transactions say filing tax returns to a professional to do it for them. 

#### Schools -> Children
#### Schools -> Parents 
How schools relate to children in K-12 and their parents is a area of emerging practice. There are a lot of concerns from activist about how children and the data they generate in their educational interactions are used and how they influence how children are treated as they move through the educational system. 


#### Business -> Kids
This is one of the few areas that is well regulated (albeit with outdated regulation) with a law called COPPA that requires parental consent for the collection of data about minors. 


#### So with all of this context what does it have to do with the Design Shop. 
There is a large focus on the blockchain as some utopian place that self-sovereign identity will happen. I invite all of those thinking about this model of identity to consider the above range of  use-case contexts and how the technology is actually useful in addressing the information exchange and transaction goals of parites involved AND how the power imbalances inherent in those relationships are address along with why/how the most powerful party actually has an incentive to change their behavior and adopt this new way of doing things. 
