---
description: >-
  You can receive emails inside your Rocket.Chat from your contacts on an email
  address your administration has configured within Rocket.Chat.
---

# Email Inboxes Agent Guide

{% hint style="info" %}
Please get in touch with your workspace admin or follow [email-inboxes.md](../rocket.chat-workspace-administration/email-inboxes.md "mention")  administrator guide to set up this feature on your workspace.&#x20;
{% endhint %}

{% hint style="warning" %}
**You must also have the** [**Omnichannel** ](https://docs.rocket.chat/guides/administration/settings/omnichannel-admins-guide#enable-omnichannel)**enabled, as well as have** [**agents**](https://docs.rocket.chat/guides/omnichannel/agents) **and** [**managers**](https://docs.rocket.chat/guides/omnichannel/managers) **assigned in order to use this feature.**
{% endhint %}

Once an email is part of a channel, your contacts can send emails to it to start a conversation. It will appear inside Rocket.Chat just like any other Omnichannel Live Chat conversation. When you reply to an email message that has been sent to you, it will appear just like any other email in your contact’s inbox.

As soon as your contact sends an email to the registered email address, it will appear in the queue just like any other Omnichannel conversation, as shown below:

![](<../../.gitbook/assets/image (217).png>)

Click **Take it!** to take it off of the **Queued Chats** and be able to reply to it

As soon as you take it, it will appear in **Chats in Progress,** and you can click **Reply via Email** to reply to it.

{% hint style="info" %}
If you type without clicking **Reply via Email**, your contact will **NOT** receive your reply at all.
{% endhint %}

Type your message and hit **Send**

It appears on your Rocket.Chat interface as shown below:

![](<../../.gitbook/assets/image (221).png>)

Your contact receives the message in email instantly.

## Invite a fellow agent to an email inbox

Suppose you get an email and you need the assistance of your fellow agent on it; you can invite them to this inbox using `/invite @username`.

![](<../../.gitbook/assets/image (235).png>)

They are invited to the channel, as shown below:

![](<../../.gitbook/assets/image (237).png>)

{% hint style="info" %}
As soon as fellow Omnichannel agent is invited to an email inbox, they are all able to see all the old conversation that has happened before their arrival in that email inbox.
{% endhint %}

And you can conversate with them internally on the same channel.

![](<../../.gitbook/assets/image (239).png>)

![](<../../.gitbook/assets/image (241).png>)

{% hint style="info" %}
As stated above, to talk to your contact, you need to click **Reply via Email**. Every message sent without clicking the button remains internal.
{% endhint %}

## Sending an Attachment

To send an attachment:

1. The agent first needs to upload the file in the channel, as shown below:

![](<../../.gitbook/assets/image (242).png>)

1. Click **Send via Email as attachment**

![](<../../.gitbook/assets/image (243).png>)

**It appears in the email of your Omnichannel contact, as shown below:**

![](<../../.gitbook/assets/image (244).png>)