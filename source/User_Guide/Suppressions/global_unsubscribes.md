---
layout: page
weight: 0
title: Global Unsubscribes
seo:
  title: Global Unsubscribes
  description: Recipients can unsubscribe from everything you send, rather than just a single group.
  keywords: Global suppressions, global unsubscribes, global email unsubscribe, global email suppression
navigation:
  show: true
---

{% info %}
This page refers to our beta UI functionality. To find these features, please click the “Beta” button at the top of the SendGrid Customer Portal.
{% endinfo %}

Global unsubscribes happen when a recipient indicates that they would like to opt out from any email that you send.  The list provided here can be filtered by email address or date. 

{% anchor h2 %}
Searching Global Unsubscribes by Date
{% endanchor %}

In the top right corner, you will see a calendar icon. Click this and choose the unsubscribe dates you would like to search between. Your recipient list will refresh, showing the recipients who unsubscribed between these dates.

{% anchor h2 %}
Removing Recipients From The List
{% endanchor %}

When you select the checkboxes next to the recipient names or select all, using the checkbox next to the search box, you will see a new button at the top of the page. From this list, you can choose to remove the selected recipients from the list.

{% anchor h2 %}
Download Global Unsubscribes as CSV
{% endanchor %}

You can download your Global Unsubscribe list as a CSV by clicking the gear icon at the top of the page and selecting “Download CSV”. The file will download in your browser right away.

{% anchor h2 %}
Using the API
{% endanchor %}

You can manage your Global Unsubscribes via the [Advanced Suppression Manager Global Suppressions API]({{root_url}}/API_Reference/Web_API_v3/Advanced_Suppression_Manager/global_suppressions.html).

{% anchor h2 %}
Related
{% endanchor %}

[Global unsubscribes vs. Group Unsubscribes]({{root_url}}/User_Guide/Email_Deliverability/Subscription_Tracking/suppressions_vs_unsubscribes.html).