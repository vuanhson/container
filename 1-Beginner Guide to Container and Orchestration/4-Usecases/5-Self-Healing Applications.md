# Self Healing Applications

Self-Healing applications are applications that are able to automatically detect when something is broken and automatically take steps to correct the problem without the need for human involvement.

System administrators will tell you that in the past, it was often very common to have to wake up in the middle of the night to reboot a server because something went wrong.

What if an automated system could detect a problem and reboot the server automatically? That an example of self-healing.

Since containers startup quickly, it's easy enough to automatically restart them.

However, containers take the concept of rebooting the server a step further

Since it is so quick and easy to startup new container instances, when something goes wrong with a containers it can often be easily destroyed and replace within a few seconds.

That means that if something goes wrong, you can have a brand new, clean, working instance quickly replace the broken one.