# Wayback Machine URL Checker

This is a [ThreatConnect](https://app.threatconnect.com/) playbook that gets run every time a new URL is created. It checks to see if that URL has already been archived in the [Wayback Machine](https://archive.org/web/web.php) and sends a slack message whether or not the given URL has ever been archived before.

![Wayback Machine URL Playbook](/img/wayback_machine_url_checker.png)

This playbook now has a user action trigger so that it can be run from the page for any url or host indicator:

![Wayback Machine User Action Trigger](/img/wayback_user_action_trigger.png)
