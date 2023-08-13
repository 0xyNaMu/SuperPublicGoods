<p align="center">

# Good for which Public? Super Public Goods 

</p>

<div align="center">
    <h4>
        <a href="/CONTRIBUTING.md">
            👥 Framework
        </a>
        <span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
        <a href="/CODE_OF_CONDUCT.md">
            🤝 Mechanism
        </a>
        <span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
        <a href="link">
            🔎 Research
        </a>
        <span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
        <a href="link">
            🗣️ Next Steps
        </a>
    </h4>
</div>

| Super Public Goods is a platform designed to enable RetroPGF Round 3 badgeholders to create templates fellow badgeholders can use during the allocation process leveraging, in a systematic and UX friendly way, others background knowledge when evaluating projects and help improve the current information gap badgeholders that are not familiar with a specific category might have.
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

This project leverages, Sismo to create private identities based on the ownership of an attestation to select a template, EAS Attestations given to badgeholders, WorldID to prevent multiple templates being created by one badgeholder, Covalent data from Zora NFTs to indicate adoption.



## 📦 Problem(s)

                                If we want to fund public goods for the Optimism Collective we first need to define: what is good for the collective? Which mechanisms can we use to coordinate and share these ideas that are more efficient than hours long posts in a forum? 
Do members of the collective have the same perceived sense of what good means? Good within which spheres of influence? Which good is more desirable vs other goods?  

## Why is this a problem?
  An innability to identify what is good for the Optimism Collective creates a false dycotomy in which badgeholders don't know what to reward and Public Good builders don't know what is most valuable to the Optimism Collective. 
  
  ### Underfunding Public Goods: 

Projects that are unable to measure and communicate the impact of the work they have done will leave money on the table that badgeholders would have been willing to commit given the right information. Taken to the extreme, if not enough resources are allocated to a project, the public good being provided by it may cease to exist. 

 ### Top-down incomplete evaluations: 
 
In the second round of RetroPGF, badgeholders were given limited guidance on how to assess the impact of the proposed projects. This presented a dual-edged problem. 

On one hand, the badgeholders, responsible for evaluating the projects, encountered difficulties when they had to assess projects in fields that were outside of their areas of expertise or familiarity. Without sufficient resources or context-specific knowledge, their ability to thoroughly evaluate the effectiveness and potential impact of these projects was impaired. 

On the other hand, and perhaps more critically, the nominees who proposed these projects faced top-down evaluations that might not have taken into account Key Performance Indicators (KPIs) significant to their on-the-ground operations. This issue stemmed from a potential disconnect between the evaluators' perspectives and the realities of hands-on fieldwork. 

There are specific indicators and factors that are vitally important and unique to ground-level work, which might not be visible, known, or may even be dismissed as irrelevant from the standpoint of someone who hasn't been involved in such in-situ operations. Consequently, these evaluations might have overlooked some crucial aspects of the projects, thereby affecting the comprehensiveness and accuracy of the assessments.

### Inability to scale:

During the RetroPGF process, the limited amount of information supplied to badgeholders posed a significant challenge. It necessitated an increased commitment of time as badgeholders needed to liaise with their counterparts to determine an effective approach for assessing the impact of projects. They were compelled to sift through the provided information, identify any gaps in data, and deliberate over which metrics should be the determining factors in the allocation of votes.

This process was time-consuming and could potentially become unmanageable as the number of projects involved in RetroPGF grows. The design and expectation of RetroPGF is to see an increase in participating projects. However, with the current system, it may result in an overwhelming workload for badgeholders. They may find it increasingly challenging to thoroughly review each project and thoughtfully distribute their votes due to time constraints.

As it stands, without more comprehensive guidelines and support, the expanding scope of RetroPGF might exceed the badgeholders' capacity to perform careful, conscientious evaluations, compromising the effectiveness and fairness of the entire process. There is an urgent need to streamline and enhance the evaluation framework to ensure its scalability and efficacy as the initiative grows.

## 💡 Solution

This is a theoretical hack. The research I did was to look into what kind of metrics are out there to evaluate the impact a project is having and how badgeholders have previously coordinated to reach a consensus on what they reward through RetroPGF. 
1) With the new iteration in application forms we will see the projects being asked to provide metrics into the impact they have been having in the Optimism Collective. We will need these data to be easily consumable so the metrics can be displayed in a number of ways for badgeholders.
2) Previously badgeholders have shared their scoring criteria on the governance forum. This project enables the creation of evaluation templates by badgeholders to help guide others on how to  conduct their allocation process based on how other value/process aligned badgeholders of their choice have done it. 
3) Using sysmo, we will create a group to whitelist all badgeholders with an attestation. Through the identity provided by sismo badgeholders's interactions with the templates will be anonymous. 
4) Badgeholders will be able to select evaluation frameworks others have suggested per each of the 4 categories for RetroPGF3 and use them to conduct their own evaluations. 
5) All badgeholders will be issued Attestations with EAS proving they are a RetroPGF3 badgeholder. 
6) Every badgeholder that wishes to issue a template will have to first sign-on with WorldID to demonstrate they are a human being and are only submitting one template per category and second, be validated as having being attested as a badgeholder.
7) Select your template and vote! 
8) Analyze the results:
Once the voting has been completed the following metrics will be used to analyze and improve the system. 
1. Number of badgeholders that selected each framework for their analysis
2. Scoring by badgeholder on how useful the template was for their evaluation
3. Number of templates created per badgeholder
4. Voting alignment based template selection (was there an inherent bias or were badgeholders still able to get to a different result?)

Having these metrics will:
A) Help improve the interface of the app 
B) Identify which badgeholders have created more impact in supporting fellow badgeholders
C) Which metrics are most valuable in the allocation process (this can then be thought to projects applying for RetroPGF).
D) Compare if badgeholders have voted in alignment with the values of the optimism collective.


<table>
    <th>Stage</th>
    <th>Name</th>
    <th>Description</th>
    <tbody>
        <tr>
            <td>
                1
            </td>
            <td>
               Self-reported impact evaluation
            </td>
            <td>    
               Nominees will create a self-reported impact evaluation based on the impact their projects have had on the Ethereum Ecosystem and their ripple or direct impact on the Optimism Ecosystem. 
            </td>
        </tr>
        <tr>
            <td>
               2
                </a>
            </td>
            <td>
                Random, anonymous, peer evaluation
            </td>
            <td>    
                Each project that has submitted a self-reported evaluation and has registered on the IEF platform will, at random, be assigned to evaluate 5 peer projects self-reported evaluations. Peer evaluations will be anonymous, meaning the evaluated projects will be unable to tell who evaluated them, which helps reduce collusion and retaliation. They will also be preserved as binary attestations within the UniRep protocol: meaning an evaluating project may only approve or dissaprove the self report issued by a peer. 
            </td>
        </tr>
        <tr>
            <td>
                3
            </td>
            <td>
Badgeholders evaluation of a random set of self-reported evaluations along the peer attestations to those reports.              </td>
            <td>    
              Optimism Badgeholders will receive a capped random set of projects to evaluate. By capping the number of projects to be evaluated, badgeholders do not need to spread themselves thin. Additionally, through the use of the Impact Evaluation Framework and the results of the peer evaluation, badgeholders will have an increased amount of information to base their decisions on. 
            </td>
           <tbody>
</table>

## 🛠 Process



## 📜 Next Steps

1. Enable the use of POAPs as a data point to increase a projects reputation on the UniRep protocol. Having certain POAPs should contribute to giving more credibility to a projects evaluation of their peers. 
2. Create user lists within the UniRep code so that projects are 1) able to evaluate peers in multiple categories AND have different reputation scores for each category, based on their qualifications in each of these categories. 
3. Enable the carrying over of the reputation score from one epoch to the next. 
4. Enable an increase in reputation per category by having participated in multiple peer evaluation rounds. 

### Important


Having anonymous peer review may prevent collusion and retaliation, but can also prevent the development of a healthy and nurturing community feedback loop that enhances projects work and improvement on previous iterations. 

Therefore, I suggest running an A|B test in which a segment of evaluators are anonymous and another isn't to explore which group yields better results. 


