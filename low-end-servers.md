Low-End Servers

Cam, of [Gullo's Hosting][gullo], periodically runs deals where he offers OVZ containers for $2.00 per year -- $2.00 per year. That's significantly less than most VPSs cost per month, less than most dedicated servers cost per day. Standard pricing for an entry level VPS is about $5.00 per month among the industry-dominating providers, like Digital Ocean and Vultr. The cheapest regular pricing you will likely find is from the big German provider, Hetzner, whose VPSs start at €2.49 per month.

I was curious to see just what one could do with a $2.00 server. This blog is now running on that $2.00 per year server. Keep in mind that at $2.00 per year you are not going to get a dedicated IPv4 address. What you get are 20 ports on an IPv4 NAT and an /80 block of IPv6 addresses. If you are using Cloudflare for your DNS hosting, you can proxy one of your IPv6 addresses to allow HTTP(S) access by clients that are limited to IPv4 -- which is how I have made this site available to the wider internet.

UPDATE (2020-05-02): I have discovered an IPv4 front-end service that you can use to provide IPv4 access to servers (like Cam's $2 per year OVZ containers) that come only with an IPv6 address. [Netiter][netiter]'s IPv4 front-end offers a useful alternative for sites that are not behind Cloudflare's proxy.

[gullo]: https://hosting.gullo.me/
[netiter]: http://v4-frontend.netiter.com

Tags: VPS

