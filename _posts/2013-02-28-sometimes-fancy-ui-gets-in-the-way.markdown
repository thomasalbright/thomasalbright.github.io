---
layout: post
title:  "Sometimes, fancy UI gets in the way"
date:   2013-02-28 23:46:00
categories: design
---

GUI interfaces are great, when they are appropriate. But sometimes, they just get in the way.

For example, it takes 2 steps in apache to restrict access to a particular directory, but it takes 10 to do the same exact thing in IIS.

In Apache:

> 1. Type "deny from all" into .htaccess.
> 2. Type "allow from .domain.com"

In IIS:

> 1. Click *Start*, point to *Settings*, and then click *Control Panel*. Double-click *Administrative Tools*, and then double click *Internet Services Manager*.
> 2. If you want to limit access for the whole site, select the Web site from the list of different served sites in the left pane. If you want to limit access only for a specific folder, click the folder you want to control.
> 3. Right-click the Web site or folder, and then click *Properties*.
> 4. Click the *Directory Security* panel.
> 5. If you want to limit access to a specific set of sites but deny access to all other sites, click *Denied Access*.
> 6. If you want to grant access to all clients by default but exclude a specific list of clients, click *Granted Access*.
> 7. To update the list of hosts or domains in the *Except* list, click *Add*.
> 8. To add computers by their identified domain name, click *Domain name*, and then type the domain name in the appropriate box.
> 9. Click *Properties*, type the domain name, and then click *OK*.
> 10. Click *OK*, and then click *OK*.

Believe it or not, both sets of instructions are from [Microsoft's support site](http://support.microsoft.com/kb/324066).
