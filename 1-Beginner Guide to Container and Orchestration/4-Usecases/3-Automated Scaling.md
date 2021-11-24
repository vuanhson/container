# Automated Scaling

Automated scaling refer to automatically provisioning resources in response to realtime data metrics

Without automated scaling, you must provision enough resource to cover your peak resource needs at all times

If I need 10 servers to handle my peak usage times, then I need 10 servers all the time

With automated scaling, you can automatically detect (or even predict) increase in usage. The automated system creates new servers to handle the peak usage time then remove those servers when usage returns to normal levels

Automated scaling depends on the ability to spin up new instance quickly and efficiently

Since containers are small and can start up quickly, they are ideal for this purpose. This mean that if the system detects an increase in usage, it can spin up new containers in a few seconds.

This increase stability and reduces cost! Your users see less downtime due to high loads, and you don't use (and pay for resources unnecessarity)