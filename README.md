# FRT-Project-Image-Analyzer-
**Image Analyzer using Azure Cognitive  Services,Computer Vision and Azure
Machine Learning**

**![](media/54b3cc9cb0a3ca9c942eb95ba63c3455.jpg)**

Image Analysis is when a computer or electrical device automatically studies an
image to obtain useful information from it. Image Analysis is the extraction of
meaningful information from images, mainly from digital images by means of
digital image processing techniques. Image analysis tasks can be as simple as
reading bar coded tags.

**Azure Services Used :-**

-   Azure Cognitive Services:-

-   Azure Cognitive Services makes AI accessible to all developers, without the
    need for machine-learning skills.

-   To embed the capacity to see, hear, speak, understand, and expedite decision
    making into your apps, all you need is an API call.

-   Enable developers of all levels of knowledge to easily add to apps.

-   **Create a Cognitive Services Resource :-**

Let’s start by creating a Cognitive Services resource in our Azure subscription:

1.  In another browser tab, open the Azure portal at <https://portal.azure.com>,
    signing in with our Microsoft account.

2.  Click the **+create a resource** button, search for cognitive services, and
    create a **cognitive services** resource with the following settings:

-   **Name:** resource2001

-   **Subscription:** Free Trail

-   **Location:** East US

-   **Pricing tier:** Standard

-   Computer Vision:-

-   The computer vision provides an obvious starting point for our exploration
    of computer vision in Azure.

-   It uses the pre-trained machine learning models to analyse images and
    extract information about them.

-   By using the Computer Vision Service, images taken by cameras throughout the
    store can be analysed to provide meaningful description of what they depict.

-   **Create a Computer Vision resource:-**

Let’s start by creating a Computer Vision Services in our Azure subscription:

1.  In another browser tab, open the Azure portal at <https://portal.azure.com>,
    signing in with our Microsoft account.

2.  Click the **+create a resource** button, search for AI+ Machine Learning and
    then click on **Computer Vision**. and create a **computer vision** resource
    with the following settings:

-   **Subscription:** Free Trail

-   **Resource group:** resource2001

-   **Name:** resouce2001

-   **Resource region:** East US

-   **Pricing tier:** Standard

1.  Select **Review + create.**

2.  Select **Create** and click on **Go to resource.**

3.  Select **Keys** and **Endpoints** on the left side under **Resource
    Management.**

-   Azure Machine Learning:-

-   The Azure Machine Learning allows you to work centrally with all the
    artefacts you create by using Azure Machine.

-   The Workspace maintains the history of all training courses, including logs,
    measurement output and an overview of your scripts.

-   **Create a Azure Machine Learning workspace:-**

Let’s start by creating an Azure Machine Learning workspace in our Azure
subscription:

1.  In another browser tab, open the Azure portal at <https://portal.azure.com>,
    signing in with our Microsoft account.

    2.Click the **+create a resource** button, search for Machine Learning and
    then click on **Machine Learning**. and create a **Machine Learning**
    resource with the following settings:

-   **Workspace Name:** workspace2001

-   **Subscription:** Free Trail

-   **Resource group:** resource2001

-   **Location:** East US

    3.Wait for the creation of your working space. Then go to the portal, and to
    the overview of your workspace page, start the Azure Machine Learning
    studio.

    4.Tap the toggle **icon** at the top right to view the several pages in the
    interface at the Azure Machine Learning studio. These pages can be used to
    manage your workplace resources.

-   FRT Image Analyzer project code SS:

![](media/a8809bbccdc1e829673f0d9fddc1ca1c.png)

-   FRT Image Analyzer project output SS:

![](media/76eb31f5cbac61eb4538392f399b54b6.png)

-   **Algorithm:-**

    **Step 1** :- Start

    **Step 2** :- Initialize library matplotlib

    **Step 3** :- Read subscription key and endpoint to call

API

**Step 4** :- Access to Cognitive Azure Services

**Step 5** :- Read Image Url provided in runtime process

**Step 6** :- After accessing give result in parameters like

Visual features : category, text, description, etc

**Step 7** :- If some error occurs show the message

regarding the error

**Step 8** :- With parametric output, show the input image

**Step 9** :- End
