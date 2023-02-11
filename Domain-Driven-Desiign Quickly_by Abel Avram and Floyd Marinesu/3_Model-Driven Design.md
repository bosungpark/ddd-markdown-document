Model-Driven Design
-

It is important to choose a model which can be easily and accurately put into code. how to we approach the transition from model to code.

One of the recommended design techniques is the so called *analysis* model.
The analysis model is the result of business domain analysis, resulting in a model which has no consideration for software used for implementation.
Such a model is used to understand the domain.
Software is not taken into account at this stage because it is considered to be a confusing factor.
Analysis models are soon abandoned after coding starts.
One of the main issues with this approach is that analysis cannot foresee some of the defects in their model, and all the intricacies of the domain.

A better approach is to closely relate domain modeling an design.
Developers should be included in the modeling process. 
Getting the developers involved provides feedback.It make sure that the model can be implemented in software.
If analyst is separated from the implementation process, he will soon lose his concern about the limitations introduced by development. 
The result is a model which is not practical.

Object-oriented programming is suitable for model implementation because they are both based on the same paradigm.

The Building Blocks Of A Model-Driven Design
-

The purpose of this patterns is to present some of the key elements of object modeling and software design from viewpoint of domain-driven design.

User-Interface -> Application -> Domain -> Infrastructure

When we create a software application, a large part of the application is not directly related to domain, but it is part of the infrastructure or serves the software itself.
It is possible and ok for domain part of an application to be quite small compared to the rest.

When domain-related code is mixed with the other layers, it becomes extremely difficult to see and think about.

