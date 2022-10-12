# Tor Exit Notice Refresh

https://exit.relay.love/

https://glenn-sorrentino.github.io/tor-exit-notice-refresh/

The Tor Project exit relay notice page updated with a more accessibile reading experience and a refreshed visual design.

![Frame 256](https://user-images.githubusercontent.com/28545431/195223293-d0ffcc29-3be7-4f58-90d6-9c4e806533db.png)

<p style="text-align:center">

<p>
You are most likely accessing this website because you've had some issue with
the traffic coming from this IP. This router is part of the <a
href="https://www.torproject.org/">Tor Anonymity Network</a>, which is
dedicated to <a href="https://2019.www.torproject.org/about/overview">providing
privacy</a> to people who need it most: average computer users. This
router IP should be generating no other traffic, unless it has been
compromised.</p>

<p>
Tor works by running user traffic through a random chain of encrypted
servers, and then letting the traffic exit the Tor network through an
exit node like this one. This design makes it very hard for a service to
know which user is connecting to it, since it can only see the IP-address
of the Tor exit node:</p>

<p>
<a href="https://2019.www.torproject.org/about/overview">Read more about how Tor works.</a></p>

<p>
Tor sees use by <a href="https://2019.www.torproject.org/about/torusers">many
important segments of the population</a>, including whistle blowers,
journalists, Chinese dissidents skirting the Great Firewall and oppressive
censorship, abuse victims, stalker targets, the US military, and law
enforcement, just to name a few.  While Tor is not designed for malicious
computer users, it is true that they can use the network for malicious ends.
In reality however, the actual amount of <a
href="https://support.torproject.org/abuse/">abuse</a> is quite low. This
is largely because criminals and hackers have significantly better access to
privacy and anonymity than do the regular users whom they prey upon. Criminals
can and do <a
href="https://web.archive.org/web/20200131013910/http://voices.washingtonpost.com/securityfix/2008/08/web_fraud_20_tools.html">build,
sell, and trade</a> far larger and <a
href="https://web.archive.org/web/20200131013908/http://voices.washingtonpost.com/securityfix/2008/08/web_fraud_20_distributing_your.html">more
powerful networks</a> than Tor on a daily basis. Thus, in the mind of this
operator, the social need for easily accessible censorship-resistant private,
anonymous communication trumps the risk of unskilled bad actors, who are
almost always more easily uncovered by traditional police work than by
extensive monitoring and surveillance anyway.</p>

<p>
In terms of applicable law, the best way to understand Tor is to consider it a
network of routers operating as common carriers, much like the Internet
backbone. However, unlike the Internet backbone routers, Tor routers
explicitly do not contain identifiable routing information about the source of
a packet, and no single Tor node can determine both the origin and destination
of a given transmission.</p>

<p>
As such, there is little the operator of this router can do to help you track
the connection further. This router maintains no logs of any of the Tor
traffic, so there is little that can be done to trace either legitimate or
illegitimate traffic (or to filter one from the other).  Attempts to
seize this router will accomplish nothing.</p>

<!-- FIXME: US-Only section. Remove if you are a non-US operator -->

<p>
Furthermore, this machine also serves as a carrier of email, which means that
its contents are further protected under the ECPA. <a
href="https://www.law.cornell.edu/uscode/text/18/2707">18
USC 2707</a> explicitly allows for civil remedies ($1000/account
<i>plus</i>  legal fees)
in the event of a seizure executed without good faith or probable cause (it
should be clear at this point that traffic with an originating IP address of
FIXME_DNS_NAME should not constitute probable cause to seize the
machine). Similar considerations exist for 1st amendment content on this
machine.</p>

<!-- FIXME: May or may not be US-only. Some non-US tor nodes have in
     fact reported DMCA harassment... -->

<p>
If you are a representative of a company who feels that this router is being
used to violate the DMCA, please be aware that this machine does not host or
contain any illegal content. Also be aware that network infrastructure
maintainers are not liable for the type of content that passes over their
equipment, in accordance with <a
href="https://www.law.cornell.edu/uscode/text/17/512">DMCA
"safe harbor" provisions</a>. In other words, you will have just as much luck
sending a takedown notice to the Internet backbone providers. Please consult
<a href="https://community.torproject.org/relay/community-resources/eff-tor-legal-faq/tor-dmca-response/">EFF's prepared
response</a> for more information on this matter.</p>

<p>For more information, please consult the following documentation:</p>

<div class="links">
<ul>
<li><a href="https://2019.www.torproject.org/about/overview">Tor Overview</a></li>
<li><a href="https://support.torproject.org/abuse/">Tor Abuse FAQ</a></li>
<li><a href="https://community.torproject.org/relay/community-resources/eff-tor-legal-faq/">Tor Legal FAQ</a></li>
</ul>
</div>

<p>
That being said, if you still have a complaint about the router,  you may
email the <a href="mailto:FIXME_YOUR_EMAIL_ADDRESS">maintainer</a>. If
complaints are related to a particular service that is being abused, I will
consider removing that service from my exit policy, which would prevent my
router from allowing that traffic to exit through it. I can only do this on an
IP+destination port basis, however. Common P2P ports are
already blocked.</p>

<p>
You also have the option of blocking this IP address and others on
the Tor network if you so desire. The Tor project provides a <a
href="https://check.torproject.org/torbulkexitlist">web service</a>
to fetch a list of all IP addresses of Tor exit nodes that allow exiting to a
specified IP:port combination, and an official <a
href="https://dist.torproject.org/tordnsel/">DNSRBL</a> is also available to
determine if a given IP address is actually a Tor exit server. Please
be considerate
when using these options. It would be unfortunate to deny all Tor users access
to your site indefinitely simply because of a few bad apples.</p>
