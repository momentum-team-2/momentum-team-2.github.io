---
layout: post
title: BE -- REST and nested models
tags: phase-3 phase-3-be django
---

Today, we walked through how to make serializers for nested models.

## An API for Question Box

Between now and Thursday, you should add an API to QuestionBox. You should make a new Django app and use viewsets for questions and answers.

- You don't to worry about favoriting or marking answers as correct.
- When you make a question, associate the current user as the author of the question.
- When you make an answer, associate the current user as the author of the answer.
- When you make an answer, the user must send the question PK.

## Resources

- [How to Save Extra Data to a DRF Serializer](https://simpleisbetterthancomplex.com/tutorial/2019/04/07/how-to-save-extra-data-to-a-django-rest-framework-serializer.html)
- [Classy DRF](http://www.cdrf.co/)
