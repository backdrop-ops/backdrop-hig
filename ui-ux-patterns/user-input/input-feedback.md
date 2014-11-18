---
layout: default
title: Input Feedback
menu_title: UI/UX Patterns
id: 35
parent_id : 32
navigation: false
group: user-input
---

# Input Feedback

### Pattern Description
When users submit content to your site via forms, errors in the data the user has provided is bound to happen from time to time. The goal of this pattern is to improve the user experience by minimizing input errors.

A paradigm suited for determining whether errors happened during form submission is whether the data validates. A common way to tell if data validates is to set up rules for each input field in the form that the entered data must pass to validate.

### Problem Statement
When user enter data to the system and which is wrong and system needs to inform the user about it in a proper manner so that it helps user to understand the problem and also gets the clue how to correct the mistake.

### Use When
System needs to validate or check the sanity of data as per the requirement of the system to function properly. Also needs to help user how to provide correct data as input.

### Solution
Indicate where user has faltered with a visible clue and a message stating what has entered wrong so that user can map. System also needs to provide appropriate message by which user can able to understand how to correct it or what is the correct way of providing input.

### Rationale
System needs to take care of the users mistake which is very common. It is obvious to the user that system will help them to use it in a proper manner with guidance.


### Examples

![Input Prompt Pattern Example](../images/input-feedback.png)
