---
title: Enabling forms portal components
seo-title: Enabling forms portal components
description: Out of the box, Forms Portal components are disabled. Enable Document Services and Document Services Predicates groups to enable Forms Portal components.
seo-description: Out of the box, Forms Portal components are disabled. Enable Document Services and Document Services Predicates groups to enable Forms Portal components.
uuid: 92d25da6-f1df-4ac0-bf84-2edf9e2722b3
content-type: reference
products: SG_EXPERIENCEMANAGER/6.4/FORMS
topic-tags: publish
discoiquuid: 4d318908-c724-4582-a82b-6e9b1c55705b
feature: Forms Portal
exl-id: 01c5eb6b-b097-4354-84b2-8bee7b7626f2
---
# Enabling forms portal components {#enabling-forms-portal-components}

Out of the box, forms portal components are not available for use. To make the components appear in the list of available components in AEM sidekick, perform the following steps:

1. Log in to the author instance of your website and open an AEM Sites page.

1. For the pages using a static template, perform the following steps:

    1. In the page header, tap ![canvas-drop-down](assets/canvas-drop-down.png) &gt; **Design** to open the page in Design mode.
    1. Tap any component (with a blue border) and then tap ![field-level](assets/field-level.png) to select the paragraph system containing the current component.
    1. In the paragraph system, tap ![settings_icon](assets/settings_icon.png) to open the Edit dialog for the paragraph system.
    1. From the list of **[!UICONTROL Allowed Components]**, enable checkboxes for **[!UICONTROL Document Services]** and **[!UICONTROL Document Services Predicates]** components. Tap **[!UICONTROL OK]**.

1. For the pages using a dynamic template, perform the following steps:

    1. In the page header, tap ![properties](assets/properties.png) > **Edit Template** to open the template of the page.
    1. Tap **Layout Container** and tap ![FeedManagement](assets/FeedManagement.png). In the **Allowed Components** tab, enable the **Document Services and Document Services Predicates** options, and tap ![aem_6_3_forms_save](assets/aem_6_3_forms_save.png).

>[!NOTE]
>
>You can also enable specific components from these categories by selecting the components. For more information about the components and their usage, see [Creating a form portal page](/help/forms/using/creating-form-portal-page.md) and [Embedding link component in a page](/help/forms/using/embedding-link-component-page.md).

Now, the Document Services and Document Services Predicates component categories are available in the components browser. The components are enabled for all the pages that use the same template.

## Related Articles

* [Enable forms portal components](/help/forms/using/enabling-forms-portal-components.md)
* [Create forms portal page](/help/forms/using/creating-form-portal-page.md)
* [List forms on a web page using APIs](/help/forms/using/listing-forms-webpage-using-apis.md)
* [Use Drafts and submissions component](/help/forms/using/draft-submission-component.md)
* [Customize storage of drafts and submitted forms](/help/forms/using/draft-submission-component.md)
* [Sample for integrating drafts & submissions component with database](/help/forms/using/integrate-draft-submission-database.md)
* [Customizing templates for forms portal components](/help/forms/using/customizing-templates-forms-portal-components.md)
* [Introduction to publishing forms on a portal](/help/forms/using/introduction-publishing-forms.md)
