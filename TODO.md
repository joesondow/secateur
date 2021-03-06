Why use kanban when you can just move bullet points around a text file?

DONE
====
- Replace the user proxy model with an actual user model based on AbstractUser
- A FormView for triggering a blocking run.
- A sloppy initial deployment
- Homepage
- Gunicorn
- A daily scheduled job for triggering unblocking.
- Add a mechanism to make sure secateur doesn't do anything if the user account no longer works.
- Set up a dockerfile to build an image for the app
- Set up a docker-compose to build a dev environment
- A 'disconnect from secateur' page that removes secateur's ability to act as you.
- A management command that upgrades someone to superuser
- A warning on the frontpage for when the twitter API hasn't been enabled for you.
- An admin action that will call 'get_user' on accounts.
- Add an account detail view.
- Add a search page to look up a user.
- Write copy for the frontpage explaining what the tool actually does.


NOW
===


NEXT
====
- Add a search bar.
- put a 'block/mute' form on an account profile page (where a search result sends you.)


BACKLOG
=======

- Login page
- Add a random margin to the blocking duration.
- move all the celery tasks into celery.py
- Add a rest API
- Replace the current blocking mechanism with a 'Job' model than can be used
  to arbitrarily schedule block, unblock, mute, and unmute operations. This
  would make the whole thing a whole lot more RESTful.
