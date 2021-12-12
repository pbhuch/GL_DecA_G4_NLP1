# GL_DecA_G4_NLP1
Great Learnings Capstone Project for Dec A Batch Group4.

AIML Online Capstone - AUTOMATIC TICKET ASSIGNMENT

The Real Problem :
One of the key activities of any IT function is to “Keep the lights on” to ensure there is no impact to the
Business operations. IT leverages Incident Management process to achieve the
above Objective. An incident is something that is unplanned interruption to an IT service or
reduction in the quality of an IT service that affects the Users and the Business. The main goal
of Incident Management process is to provide a quick fix / workarounds or solutions that resolves the
interruption and restores the service to its full capacity to ensure no business impact. In most of the
organizations, incidents are created by various Business and IT Users, End Users/ Vendors if they have
access to ticketing systems, and from the integrated monitoring systems and tools. Assigning the
incidents to the appropriate person or unit in the support team has critical importance to provide
improved user satisfaction while ensuring better allocation of support resources. The assignment of
incidents to appropriate IT groups is still a manual process in many of the IT organizations. Manual
assignment of incidents is time consuming and requires human efforts. There may be mistakes due to
human errors and resource consumption is carried out ineffectively because of
the misaddressing. On the other hand, manual assignment increases the response and resolution times
which result in user satisfaction deterioration / poor customer service.

Business Domain Value :
In the support process, incoming incidents are analyzed and assessed by organization’s support teams to
fulfill the request. In many organizations, better allocation and effective usage of the valuable support
resources will directly result in substantial cost savings.
Currently the incidents are created by various stakeholders (Business Users, IT Users and Monitoring
Tools) within IT Service Management Tool and are assigned to Service Desk teams (L1 / L2 teams). This
team will review the incidents for right ticket categorization, priorities and then carry out initial
diagnosis to see if they can resolve. Around ~54% of the incidents are resolved by L1 / L2 teams. Incase
L1 / L2 is unable to resolve, they will then escalate / assign the tickets to Functional teams from
Applications and Infrastructure (L3 teams). Some portions of incidents are directly assigned to L3 teams
by either Monitoring tools or Callers / Requestors. L3 teams will carry out detailed diagnosis and resolve
the incidents. Around ~56% of incidents are resolved by Functional / L3 teams. Incase if vendor support
is needed, they will reach out for their support towards incident closure.
L1 / L2 needs to spend time reviewing Standard Operating Procedures (SOPs) before assigning to
Functional teams (Minimum ~25-30% of incidents needs to be reviewed for SOPs before ticket
assignment). 15 min is being spent for SOP review for each incident. Minimum of ~1 FTE effort needed
only for incident assignment to L3 teams.

During the process of incident assignments by L1 / L2 teams to functional groups, there were multiple
instances of incidents getting assigned to wrong functional groups. Around ~25% of Incidents are
wrongly assigned to functional teams. Additional effort needed for Functional teams to re-assign to right
functional groups. During this process, some of the incidents are in queue and not addressed timely
resulting in poor customer service.
Guided by powerful AI techniques that can classify incidents to right functional groups can help
organizations to reduce the resolving time of the issue and can focus on more productive tasks.
Project Description
In this capstone project, the goal is to build a classifier that can classify the tickets by analyzing text.
Details about the data and dataset files are given in below link,
https://drive.google.com/open?id=1OZNJm81JXucV3HmZroMq6qCT2m7ez7IJ

Pre-Processing, Data Visualization and EDA
  ● Exploring the given Data files
  ● Understanding the structure of data
  ● Missing points in data
  ● Finding inconsistencies in the data
  ● Visualizing different patterns
  ● Visualizing different text features
  ● Dealing with missing values
  ● Text preprocessing
  ● Creating word vocabulary from the corpus of report text data
  ● Creating tokens as required

Model Building

 Building a model architecture which can classify.
 Trying different model architectures by researching state of the art for similar tasks.
 Train the model
 To deal with large training time, save the weights so that you can use them when training the
model for the second time without starting from scratch.

Test the Model, Fine-tuning and Repeat
  ● Test the model and report as per evaluation metrics
  ● Try different models
  ● Try different evaluation metrics
  ● Set different hyper parameters, by trying different optimizers, loss functions, epochs, learning
rate, batch size, checkpointing, early stopping etc..for these models to fine-tune them
  ● Report evaluation metrics for these models along with your observation on how changing
different hyper parameters leads to change in the final evaluation metric.
Proprietary content. ©Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited
Project Objectives

The objective of the project is,
 Learn how to use different classification models.
 Use transfer learning to use pre-built models.
 Learn to set the optimizers, loss functions, epochs, learning rate, batch size, checkpointing, early
stopping etc.
 Read different research papers of given domain to obtain the knowledge of advanced models for
the given problem.
Project submissions and Evaluation Criteria
While we encourage peer collaboration and contribution, plagiarism, copying the code from other
sources or peers will defeat the purpose of coming to this program. We expect the highest order of
ethical behavior.
Submit the project as given below.
 Report with Problem Statement, Related Work, Your Approach and comparison of results with
other models written in Latex.
 Github link of where the model is hosted
