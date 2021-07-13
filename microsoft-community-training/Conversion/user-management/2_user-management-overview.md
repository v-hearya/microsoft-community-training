---
title: User Management - Overview
original-url: https://docs.microsoftcommunitytraining.com/docs/user-management-overview
---
Microsoft Community Training Management portal allows administrators an easy way to delegate/automate administrative tasks like user onboarding, course enrollment, etc. and empower the ground level facilitators/trainers to drive engagement and adoption of the learning program across your training audience. 

All the user management functionalities are stacked together in a single panel **under the Users Tab** – a one-stop-shop for administrators to manage users and course enrollments on the management portal. From the users tab, administrators can [add users](/v1/docs/add-users-to-the-portal-1) and assign administrative roles,[ create groups](/v1/docs/create-a-new-group), assign courses, track progress and much more.

![image.png](../../media/image%28421%29.png)

In this article, you will learn how to use the management portal capabilities to create and manage your users and facilitate effective training administration. 

## Types of Users 
In Microsoft Community Training platform, there are two types of users - a Learner and an Administrator. 

**Learner** 
Learner is the default role assigned to any user added to the platform. Learners will be able to view and consume courses uploaded by the administrators on the training portal. While accessing the training content, learners can use discussion forum to [add/share comments](https://docs.microsoftcommunitytraining.com/docs/mobile#step-5-discuss-and-share-information-with-peers) with others and stay informed on the important updates sent by the trainers. 

**Administrator** 
Administrators are the users who can access the [**management portal**](https://docs.microsoftcommunitytraining.com/docs/step-by-step-configuration-guide#step-2--switch-to-administrator-view-of-the-portal) on the platform and are responsible responsible for managing and delivering the training program. 

There are six types of administrator on the platform (i.e. Global Administrator, Organization Administrator, Learning Path Administrator, Category Administrator, Course Administrator and Group Administrator) each responsible for performing specific activities on the management portal. Administrators can create organizations, groups and courses, add users and assign content, track progress and drive content completion via announcements to users and make other users as administrators on the platform. 

For more details, please visit the [**user personas and management portal overview article**](https://docs.microsoftcommunitytraining.com/docs/user-role-and-management-portal-overview).  

## Create Organizations and Groups
Organizations and Groups are a way to help you organize your learners depending on the needs and structure of the training program. 

**Organization** is a set of learners and administrators on the training platform who have a particular purpose or belong to a specific criteria viz. location, job function, interest etc. 
:::(Info) (Note)
**Organizations** help create virtual boundaries on the training platform, by ensuring that content and users of an organization is accessible ONLY within that organization. 
:::

**Group** is a set of learners on the training platform who have a specific training requirement. Groups make user management within an organization and overall company easy via bulk user onboarding and automatic enrollment. 

:::(Info) (Note)
Training platforms can utilize the capabilities of **both** Organization & Group or **only ONE** one of them without enabling the other to manage their training use case.
:::

### Sample Scenario 1
Let's say there is a company in South Africa which has employees located across the country who are required to be trained and upskilled regularly. 
* To effectively manage and train their geographically disributed workforce, the company can decide to create **Groups** based on their office locations such as Cape Town, Johannesburg, Port Elizbeth, etc. 
* Another way to manage and organize workforce would be based on the roles and departments such as Sales, Marketing, Human Resources, Operations, etc. 

### Sample Scenario 2
Let's say there is a company in United States of America which has employees located in various countries across the world and managed by their own country leadership. 

* In this case, the company may decide to create **Organizations** on the training platform basis country viz. India, Singapore, South Africa etc. 
* Each of the Organizations can be assigned their own set of Organization Administrator(s) and each learner can belong to one Organization. 
:::(Info) (Note)
The Organization Administrator of an organization will be able to create and manage content and users for ONLY the particular organization creating virtual boundaries on the training platform. 
:::
* Now, to effectively manage and train their distributed workforce, each organization can create its own Groups basis job roles such as Sales, Marketing, Human Resources, Operations, etc. 
* Another way to manage and organize workforce would be based on training requirements such as areas of interest, performance review assessments etc.  

## Add users to Organization
**Organizations** can be used on the training platform to create virtual boundaries where content and users of an organization is accessible only within the organization. 
Global administrators can define Organization and [assign Organization Administrator role](/v1/docs/organization-management) from the management portal. 
Learners are by default part of the Default Organization and API calls can be made to the training platform to change their Organization.

:::(Warning) (Important)
Typically, Organizations should be set up on the training portal ONLY IF there is a requirement that users and content relevant to one organization should not be accesible by another organization. 
:::

## Add users to groups
Groups can be used on training platform to manage different types of learners and automate enollment to content based on the skills required, user location, functional domains, role etc. 
For example, you can [**create groups**](https://docs.microsoftcommunitytraining.com/docs/create-a-new-group) and [**set rules to automatically add users**](https://docs.microsoftcommunitytraining.com/docs/setup-automatic-user-enrollment-for-a-group-1) to the group whenever they sign up on the platform. 

Alternatively, organization can also [**manually add users**](https://docs.microsoftcommunitytraining.com/docs/add-multiple-users-to-the-group) to the group at once. 

## Manage content enrollment for user groups
Group administrator can leverage the group functionality on the platform to automate content enrollment for learners in the group. For any group on the management portal, admininstrator can pre-assign courses and learning paths from the content library and [**automate content enrollment**](https://docs.microsoftcommunitytraining.com/docs/assign-content-to-group-users) for existing and new participants in the group.

**For example**, let's say the administrators on the training portal have [**created a group**](https://docs.microsoftcommunitytraining.com/docs/create-a-new-group) for the Sales team and [**added all the sales employees**](https://docs.microsoftcommunitytraining.com/docs/add-multiple-users-to-the-group) to the group.  Now, a group administrator (aka Sales Manager) can pre-assign the mandatory sales trainings for the group so that any new sales employee signing up on the portal will be automatically enrolled to those courses.   

## Tracking learner progress and drive course completion 

Groups can be used on the training platform to not only delegate and automate administrative tasks like user onboarding and course enrollment but also tracking learners progress and send reminders to drive engagement and course completion. 

Group administrator on the portal can leverage [**group analytics**](https://docs.microsoftcommunitytraining.com/docs/group-view-report) to monitor progress of the group participants and [**send announcements**](https://docs.microsoftcommunitytraining.com/docs/send-announcement-to-the-users) and reminders to drive course completion. In the following sections, you will learn more about these features: 

### Send announcement
Whenever new courses are assigned to the users, automatic notifications are sent by the system to the learners. Apart from this, group administrators can [**send announcements**](https://docs.microsoftcommunitytraining.com/docs/send-announcement-to-the-users) to the whole group or specific set of learners in the group and inform them about important updates, event or action they need to perform. 

For example, let's say there are set of learners in a group who have not finished the complaince training which needs to be completed in a week's time. In such scenarios, group administrators can send a reminder to the learners to complete the training and get certification. 

### Tracking learning progress
Management portal provides real-time analytics and reports to track learners progress and course completion of the assigned courses for the group participants. Groups administrators can view and download learners report card to monitor progress and measure performance for the assigned courses. For more details, [**see this article**](https://docs.microsoftcommunitytraining.com/docs/group-view-report).

## Steps to add users and assign content on the portal 

Microsoft Community Training platform provides specific set of features to help administrator with activities such as adding learners, creating groups and assigning content. Given below are the simple steps to get started with user management on the management portal:

1.	Create groups on the management portal 
Here are the detailed steps on [**how to create a new group in the portal**](https://docs.microsoftcommunitytraining.com/docs/create-a-new-group).

2.	Add learners to the newly created group 
Here are the detailed steps to [**how to add users to the group**](https://docs.microsoftcommunitytraining.com/docs/add-multiple-users-to-the-group).

4.	Assign content to the group participants
Here are the detailed steps to **[assign content to the group users](https://docs.microsoftcommunitytraining.com/docs/assign-course-to-group-users)**. 

5.	Send announcement and reminders to the group participants
Here are the detailed steps to **[send announcements to the group users](https://microsoftindia.document360.io/docs/send-announcement-to-the-users)**.

## Best Practices to manage users on the portal

1. [**Create groups on the platform**](https://docs.microsoftcommunitytraining.com/docs/create-a-new-group) based on learner's location, designation, department, role, etc. and [**add group administrators**](https://docs.microsoftcommunitytraining.com/docs/add-an-administrtor-to-the-portal#add-a-group-administrator-to-the-portal) to delegate user onboarding and automate course enrollment

2. Use [**bulk upload users**](https://docs.microsoftcommunitytraining.com/docs/add-multiple-users-to-the-group) functionality to quickly import your existing users list and organize them into different groups 

3. [**Set rules to automate user enollment**](https://docs.microsoftcommunitytraining.com/docs/setup-automatic-user-enrollment-for-a-group-1) to the group and reduce the burden of administrator tasks on your trainers 

4. Have very limited number of  Global Administrators on the portal. This is because Global Administrators can read and modify everything on the platform.