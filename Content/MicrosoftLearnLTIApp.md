# Microsoft Learn LTI Application 

![Learn LTI Application](https://github.com/microsoft/Learn-LTI/blob/main/images/Learn-lti.png)
### About ###
[Microsoft Learn](https://docs.microsoft.com/learn/?WT.mc_id=edna) is a free, online training platform that provides interactive learning resources for Microsoft products and cutting edge technologies. Our goal is to empower students and educators to learn about technology through fun, guided, hands-on content aimed at specific learning goals. 

To bring Microsoft Learn's content into the classroom, we've made a Learning Tools Interoperability (LTI) application that enables you to seamlessly blend self-paced learning content from the Microsoft Learn catalog with your curriculum and Learning Management System (LMS).

Educators and Institutions can leverage the LTI application to integrate Microsoft Learn Modules and Learning Paths into their curricula while providing hands-on experiences with Azure and other Microsoft technologies. Learners will be routed from their LMS to Microsoft Learn, where they can accrue experience points and achievements as well as track progress on learning activities.

The Microsoft Learn LTI Application adheres to [v1.1](https://www.imsglobal.org/specs/ltiv1p1) and [v1.3](http://www.imsglobal.org/spec/lti/v1p3/) standards. For more specifics on the application itself, check out the [Architecture Overview](http://github.com/microsoft/learn-lti/tree/main/docs/ARCHITECTURE_OVERVIEW.md).

### Key Features: ###
- **Single Sign-On** (SSO) - users only have to sign into their institution once to access the Learn LTI application
- **LMS Pairing** - instructors can create, edit, and publish Learn-based assignments for their courses and populate their insitution's LMS with them easily
- **LTI v1.1 and v1.3 Compliant** - student data is not gathered and their data cannot be accessed; all user data is protected.

### What do I need to get started? ###
Typically, there will be four roles involved in deploying, configuring, and using the Microsoft Learn LTI application with Institution’s LMS.

1. **Central IT / IT Admin** – The user deploying the Microsoft Learn LTI application to Azure. They need to be an owner of an Azure subscription and have the privileges to create Azure resources. This person will also be the one configuring the Microsoft Learn LTI application to work with the LMS.
2. **LMS Admin** – The user configuring the LMS to work with the deployed Microsoft Learn LTI application. Once configured, the Microsoft Learn LTI application will appear as an LTI tool (external tool) to be used by all Educators on the LMS.
3. **Educators** – The user(s) of the LMS who is set up as a “Teacher” in a course and will facilitate the learning. This person will create activities or resources based on the configured LTI tool on the LMS.
4. **Students** – The users of the LMS who will consume the learning provisioned to them by the Educators.

The following visual illustrates the workflow in full:
![Readme.1.png](https://github.com/microsoft/learn-lti/blob/main/images/Readme.1.png)

To deploy the Microsoft Learn LTI application, the Central IT / IT Admin will need:

- LMS System that supports LTI v1.1 or v1.3
- You need to be the **owner** of an Azure subscription
- IT administrator privileges to create an Azure resource
- [Getting Started Overview](https://techcommunity.microsoft.com/t5/educator-developer-blog/getting-started-with-the-microsoft-learn-lti-application/ba-p/2247034)
- Microsoft Learn LTI application [Setup presentation](http://github.com/microsoft/learn-lti/tree/main/docs/Microsoft%20Learn%20LTI%20Application.pdf) 

# Table of Contents

1. [Deployment Guide](http://github.com/microsoft/learn-lti/tree/main/docs/DEPLOYMENT_GUIDE.md)
2. [Configuration Guide](http://github.com/microsoft/learn-lti/tree/main/docs/CONFIGURATION_GUIDE.md)
3. [Educator Guide](http://github.com/microsoft/learn-lti/tree/main/docs/USER_GUIDE.md)
4. [Student Guide](http://github.com/microsoft/learn-lti/tree/main/docs/STUDENT_GUIDE.md)
5. [Architecture Overview](http://github.com/microsoft/learn-lti/tree/main//docs/ARCHITECTURE_OVERVIEW.md)
6. [Pricing Structure](http://github.com/microsoft/learn-lti/tree/main/docs/PRICING_STRUCTURE.md)
7. [Take it Further](http://github.com/microsoft/learn-lti/tree/main/docs/TAKE_IT_FURTHER.md)
8. [Frequently Asked Questions](http://github.com/microsoft/learn-lti/tree/main/docs/FAQ.md)
9. [Troubleshooting](http://github.com/microsoft/learn-lti/tree/main/docs/TROUBLESHOOTING.md)
10. [Security](http://github.com/microsoft/learn-lti/tree/main/docs/SECURITY.md)
11. [Privacy](http://github.com/microsoft/learn-lti/tree/main/docs/PRIVACY.md)
