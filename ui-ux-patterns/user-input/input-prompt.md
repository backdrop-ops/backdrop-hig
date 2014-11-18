---
layout: default
title: Input Prompt
menu_title: UI/UX Patterns
id: 34
parent_id : 32
navigation: false
group: user-input
---

# Input Prompt

### Pattern Description
The Input Prompt pattern is most successfully used with dropdown lists and text fields.
As the dropdown list has a fixed set of choices the user can choose from, it is often words like Select or Choose the prompt text begins with.
For text fields, the prompting string often begins with a call to action: Enter, Type, Search.
End the string with the noun the input is describing, for instance Enter city or Enter an address.

For text fields, the Input Prompt pattern is often combined with scripting that removes the prompting text once the user’s focus is on that box. Once the user enters the input field to type in content, the prompting text is removed and replaced with nothing so that the input field is free for the user to fill out


### Problem Statement

Backdrop system needs user correct inputs from user but needs to minimize the effort/time for user.


### Use When
When system expect a input which is correct and wants to minimize the effort/time of providing input by proper and valid clue.

### Solution
Provide correct system default value/s with proper explanations in the form of message.

### Rationale
User uses a system to mimimize overall effort and get the maximum value, so help user by providing proper defaults with message.

### Examples

![Input Prompt Pattern Example](../images/input-prompt.png)
