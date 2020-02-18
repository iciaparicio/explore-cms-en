---
description: >-
  Also called horizontal carousel. This module can be used, for example, to 
  highlight content that is relevant to the user.
---

# Featured Content

An ideal module to highlight relevant content for the user, limiting the number of elements that can be viewed, with a maximum of 6.

The various content that has been configured is displayed as a horizontal carousel so that the user can see it comfortably.

![](../../.gitbook/assets/image-8.png)

Fill in the required fields and decide if you need to fill in any of the optional fields:

## Details

![](../../.gitbook/assets/image-70.png)

**Name**. Name that internally identifies the element. It is never shown in the app but you can use this name to identify the module in the module list view.

​​🔅 It has no maximum length and is a **required** field.‌

**For more information check the guidelines**. Check the design guidelines relating to the module you are creating or editing. Review them to ensure that content of the highest possible quality is being uploaded.

## Module building

![](../../.gitbook/assets/image-19.png)

**Section Title**. Title that is shown above the module as long as it is not positioned first. When a module is positioned first, there is no section title \(in that case the section title is always _Explore_\). In addition, this title is used to internally identify the module you are creating. Using this title, you can identify the module in the module list view.

🔅 It has a maximum length of **25 characters** and is a **required** field.

{% hint style="warning" %}
Within a layout, a _Featured Content_-type module must occupy the first position.
{% endhint %}

## Cards

The _cards_ are the sections that make up the carousel. For each _Featured Content_ module, configure a minimum of 2 _cards_ and a maximum of 6.

![](../../.gitbook/assets/image.png)

For each _card_, the available fields will vary depending on whether you select an image or a _bumper_:

* **Image**. It displays a static image.
* **Bumper**. It displays a short video or animation.

💡 \_\_ **Did you know?**

A _bumper_ is a short video or animation. It is a fairly standard format used in marketing, usually used for commercial purposes and with an average duration of around 6 seconds.

{% tabs %}
{% tab title="Image" %}
![](../../.gitbook/assets/image-11.png)

**Image Upload an image** 📤. URL of the _card_ image. This must be in the CMS's own URL format.

Click on the **Upload an image** link 📤 _\*\*_ and choose the image you want from your computer. Once the image upload has been processed, the URL will autocomplete in the text field.

When the image has been uploaded it is previewed just below.

![](https://lh4.googleusercontent.com/dULPpwb-XaQ083yWLTZF1G1l_7MO0cW70lM7eg5-ZpMvWyZAPBHjJJpMVNjiTUDtgMy1ng2b_JaSkVRGDZd84K0oSvZnzSS9wp_ddXuGkWXzR2Loo3Pbeio_0pm5ESpRuO28cUhx)

🔅 This is a **required** field.

**Image Accessibility Text**. Description of the image that is used for accessibility as an alternative if the image cannot be displayed \(for example, for people with vision problems\).

🔅 It has no maximum length and is an **optional** field.
{% endtab %}

{% tab title="Bumper" %}
![](../../.gitbook/assets/image-21.png)

**Bumper Upload a bumper** 📤. It is autofilled with the name of the _bumper_.

To upload a bumper you have two options:

1. Click on the **Upload a bumper** 📤 link and upload a _bumper_ from your computer.
2. Display the list of _bumpers_ and select one of those that have already been uploaded.

Activate the **Play in loop** option ifor the _bumper_ to be played in loop in Explore. If you leave it off, it will play every time the _bumper_ is on the screen, but once it has finished it will stop.

![Enable or disable the option to play on repeat](../../.gitbook/assets/image-26.png)

When the _bumper_ has been uploaded it is previewed just below:

![](https://lh3.googleusercontent.com/3IXi0mLJsZm9bEzL8Tv-0-lZoNL-TfIve9tuIW_3fQCsNTzYPF7HhKdPi_Vl5RV-TiRr7AF3LgeRpOP-IYXqNsxsMQqz2eZ-_T-zseUG3oWU7N7coCU5szug3M2kTo65W4LYDuT_)

**Bumper Accessibility Text**. Description of the _bumper_ that is used for accessibility as an alternative if the _bumper_ cannot be displayed \(for example, for people with vision problems\).

🔅 It has no maximum length and is an **optional** field.
{% endtab %}
{% endtabs %}

**Card 1 Pre-title**. Title that appears immediately below the image in the carousel.

🔅 It has a maximum length of **44 characters** \(less than 24 recommended\) and is a **required** field.

**Card 1 Title**. Title that appears below the **Pre-title** and identifies the _card_ internally.

It has a maximum length of **70 characters** \(less than 35 recommended so as not to take up more than one line\) and is a **required** field.

**Card 1 Tracking Name**. Name that is not seen by users but is seen in Google Analytics. It is used to more easily identify the product internally.

🔅 It is an **optional** field.

**Card 1 Description**. Short description of the _card_.

🔅 It has a maximum length of **132 characters** \(less than 125 recommended\) and is a **required** field.

**Card 1 Tag**. Short text that is located above the image of the _card_.

🔅 It has a maximum length of **18 characters** \(less than 10 recommended\) and is a **optional** field.

**Card 1 Action Url**. URL of the _card_, i.e., the URL that can be accessed by clicking on the _card_.

🔅 This is a **required** field and has to be a valid URL \(for example: [https://www.google.com\](https://www.google.com\)\)

**Card 1 Starting date and time**. Date and time you want the _card_ to start being displayed to users.

🔅 It is an optional field.

**Card 1 Ending date and time**. Date and time you want the _card_ to stop being displayed to users.

🔅 It is an optional field.

**Display the ending date on the card**. Activate this option to inform the user that the content will expire.

![](../../.gitbook/assets/image-25.png)

**How is the expiration date displayed?**

If you have enabled the option to show the expiration date, the way in which that date is displayed depends on the day on which the _card_ expires.

`ENDS TODAY hh:mm AM` or `ENDS TODAY hh:mm PM` or `ENDS TODAY hh:mm` \(format varies depending on the country\) to indicate that _card_ expires on the same day at the specified time, in the morning or in the afternoon, respectively. For example, `ENDS TODAY at 9:00 AM`.

![](../../.gitbook/assets/image-59.png)

`ENDS TOMORROW` to indicate that the expiration date is the following day.

![](../../.gitbook/assets/image-6.png)

`ENDS on dd mm` to indicate that the difference is more than two days. For example `ENDS on 30 JUN`.

![](../../.gitbook/assets/image-22.png)

🎯 Starting and Ending date and time is a way to program some campaigns and is specifically designed for seasonal campaigns.

**Card 1 Microsegments**. Tags that you can add, always separated by commas, to make a segmentation of the users who are going to see the content you are creating.

🔅 It is an **optional** field.

{% hint style="warning" %}
Remember that you have to configure a minimum of 2 _cards_ and a maximum of 6.

The fields for all the cards are the same.
{% endhint %}

**Card 1 categories \(mandatory\)**

Categories allow you to filter content in Explore. The categories are shown at the top in a horizontal scroll bar, which allows the user to browse by category and choose the one they want to see.

When the user selects a category, the content is shown in a vertical format \(as opposed to having to scroll horizontally\), so that the user doesn't miss any content.

![](../../.gitbook/assets/categories_divices-1.png)

In Explore CMS, select the category or categories that apply to the card that you are configuring:

![](../../.gitbook/assets/categories.png)

* **Accessories**: earphones, cases, watches.
* **Bundles**: packs, plans, product packs.
* **Devices**: smartphones, tablets.
* **Loyalty**: membership, loyalty/retention programmes content \(Vivo Valoriza, Priority, Club Movistar, etc.\)
* **Promos**: promotional content that may apply and which may coexist with other categories.
* **Plans**: rates, plan upgrades.
* **Services**: added value services, apps, new app features, other TEF services.
* **TV**: television plans, content packs, featured or new content.

{% hint style="info" %}
The category **All**, which is the first one that you see, isn't a category as such. Rather, it is the way in which the user can view all the content.

By default, when a user opens Explore he/she sees all content and all configured cards. As such, the selected category is always **All**.
{% endhint %}

🎯 **Good practices**: We don't recommend assigning more than one category to a content. Explore CMS does not set a limit for the number of categories that can be assigned.

**What should I consider when using the categories?**

Consult the [**Categories**](../../faq_en-us.md#categories) section of the [FAQ](../../faq_en-us.md) to resolve all of your doubts.

