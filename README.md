# create-react-app-django

Helps Django-first projects bring a Create React App (CRA) into a templated view with less fuss.

# Benefits

## Django-Developer Focused

*   No magic. Clear explanation of how Django and CRA work together in Django terms.
*   See it Working. Get React safely into your Django project faster using the CRA-Django Example project.
*   Learn React as you go. Ease yourself into this modern web stuff.

## All the Benefits of Create React App + CRACO

*   Exceed expectations of React developers. Industry-standard React developer experience _inside_ your django project.
*   Flexible customization of CRA. Sensibly tweak CRA to your requirements _without_ ejecting with [CRACO](https://github.com/gsoft-inc/craco).
*   Onboard yourself with the best tools. Pick up React by starting with the official React starter project in a workflow you already understand.

# Django / React Philosophy

*   Django and React can co-exist and work together.
*   Existing Django projects have a lot to offer a React app.
*   It is still a Django Project.

# CRA-Django Example Project

\[A recognizable organization and example DRF API Endpoints serving the react application\]

# FAQ

## For Django Developers

### How many new API endpoints are needed to start?

In many cases, zero. React developers can use Django's normal session authentication to hit DRF from the get go.

### Will React eat my Django project?

No, especially if you have an established Django project. But you may re-evaluate your allegiance to Django on your next one. 👀

## For React Developers

### Can I safely start developing a CRA before Django folks have done this integration?

Yes. You can get started and imagine your app running inside the Django project's existing template.

### Why are you making us work with Django?

For starters, this isn't a technology feud it is an alignment that lets your team focus on building a great product. But since you asked:

*   Django is stable and has a lot to offer.
*   Django's backend can offer you everything you normally get in React including [the possibility of GraphQL](https://github.com/graphql-python/graphene-django) on Django.
*   If the team is great with Django, and you have a deadline, this lets everyone release faster.

### How do Django apps build out APIs?

*   The most popular way is using [Django Rest Framework](https://www.django-rest-framework.org/). But to you it will just look like `/api/...`

---

**Draft Notes:**

*   Hot-reload of _only_ your Create React App _inside_ a django template
*   CRACO benefits
    *   Easy upgrades of CRA
    *   Front-end testing with Jest
    *   Comprehensive and well-maintained configuration layer for future tweaks
