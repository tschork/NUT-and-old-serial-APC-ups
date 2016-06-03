# NUT-and-old-serial-APC-ups
My issue(s) setting up a APC ups with nut

I'm letting this here in hope it will help someone (might even be me in the future) on why you cannot get apcupsd nor nut to communicate with your old Serial UPS.
I bought this second hand, and it's working great.

In my case, the UPS is an old APC smart-ups 1000, model SU1000INET.
It features only a serial port and an extension port.
In my case, the expansion port came with a "dry contact cards".

For 3 days, I tried to have NUT communicate with my UPS, with no success.
I hadd ordered a genuine APC cable, but to no avail, I kept getting "Driver failed to start (exit status=1)"

It took me 3 days, but in the end I tried to remove the extension card.
I would have know, I'd had started with that, as this made the difference.

So, if you are trying to communicate with an old smart-ups on a serial port and nothing goes, remove the card you have in the expansion port if you cannot get it to work.
It might just save you some hours of sleep.
