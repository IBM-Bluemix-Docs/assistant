---

copyright:
  years: 2015, 2020
lastupdated: "2020-09-08"

subcollection: assistant

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:external: target="_blank" .external}
{:deprecated: .deprecated}
{:important: .important}
{:note: .note}
{:tip: .tip}
{:pre: .pre}
{:preview: .preview}
{:codeblock: .codeblock}
{:screen: .screen}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:swift: .ph data-hd-programlang='swift'}
{:table: .aria-labeledby="caption"}

# Adding an actions skill ![Beta](images/beta.png)
{: #skill-actions-add}

Add an actions skill to design a content-rich dialogue for your assistant.
{: shortdesc}

The actions skill feature is being offered as a beta feature. The feature might be unstable, might change frequently, and might be discontinued with short notice. This beta feature also might not provide the same level of performance or compatibility that generally available features provide and are not intended for use in a production environment.
{: important}

## Add the actions skill
{: #skill-actions-add-task}

To add actions, complete the following steps:

1.  Click **Create Skill**.

1.  Select the **Actions skill**, and then click **Next**.

1.  Take one of the following actions:

    - To add an existing skill to this service instance, you can import it as a JSON file. Click **Import skill**. Drag a file or click **Drag and drop file here or click to select a file** and select the JSON file you want to import.

      The imported JSON file must use UTF-8 encoding, without byte order mark (BOM) encoding. The JSON cannot contain tabs, newlines, or carriage returns.
      {: important}

      Click **Import**.

    - To create a new skill, stay on the *Create skill* tab.

1.  Specify the details for the skill:

    - **Name**: A name no more than 100 characters in length. A name is required.
    - **Description**: An optional description no more than 200 characters in length.
    - **Language**: The language of the user input the skill will be trained to understand. The default value is English.

      For more information about supported languages, see [Supported languages](/docs/assistant?topic=assistant-language-support).

1.  Click **Create actions skill**.

Add actions to your skill. For more information, see [Adding actions](/docs/assistant?topic=assistant-actions).