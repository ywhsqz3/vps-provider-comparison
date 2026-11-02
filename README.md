# compare vps providers: Real Specs, Renewal Costs, and the Fine Print That Decides Your Bill

When you compare VPS providers, three numbers matter more than anything on the marketing page: the entry price, the renewal price, and the billing cycle. Most comparison sites stop at the first one. That's how people end up paying four to five times more in year two than they expected.

This guide puts real, checked numbers side by side — RackNerd, Vultr, Contabo, InterServer, Hostwinds, Hostinger — and covers the details that rarely make it into the top-ranking reviews: how RackNerd's cheap yearly specials actually renew, what its refund policy really says, and which hidden perks and traps exist in the fine print.

> **Quick pick:** If you want the lowest total cost and you're comfortable managing your own root server, RackNerd's 1 GB yearly special at **$21.99/year** (about $1.83/month) is the standout deal — and it renews at the same rate. [👉 Check current RackNerd yearly specials](https://my.racknerd.com/cart.php?a=add&pid=952&aff=11397)

## What actually matters when you compare VPS providers

The headline price tells you almost nothing on its own. Two providers can both advertise "from $5/month" and cost wildly different amounts over 24 months.

Four things decide the real outcome:

1. **Entry price vs. renewal price.** Hostinger's KVM VPS starts at $6.49/mo but renews at $11.99/mo — an 85% jump. Hostwinds renews at roughly +30%. InterServer locks its price permanently. These differences compound fast.
2. **Managed vs. unmanaged.** ScalaHosting's managed VPS starts at $29.95/mo (renewing at $54.95/mo) because someone else handles patches and security. Unmanaged KVM plans like RackNerd's cost a fraction of that because you do the work: choose the OS image, harden SSH, apply updates, set up backups.
3. **Support response and uptime.** A $3/month server that goes down for six hours costs more in frustration than a $6/month one that answers tickets in two. Third-party 12-month tracking puts InterServer and Hostwinds at 99.9% uptime with 1–4 hour and 30-minute-to-2-hour ticket responses respectively, while Contabo's support typically responds in 6–24 hours.
4. **Billing cycle.** Yearly prepaid locks in the deal; hourly billing (Vultr's model) costs more per month but lets you spin servers up and destroy them when you're done.

Keep those four in mind. Now the plans themselves.

## RackNerd's full VPS lineup: catalog plans vs. yearly specials

RackNerd sells its KVM VPS through two separate product lines, and confusing them is the single most expensive mistake buyers make. Here's the complete catalog lineup from the official KVM VPS page (Los Angeles, Asia-optimized network; all plans include 1 free IPv4, RAID-10 SSD storage, 1 Gbps port, instant setup):

| Plan | vCPU | RAM | SSD (RAID-10) | Traffic @ 1Gbps | Price | Order |
| --- | --- | --- | --- | --- | --- | --- |
| 512 MB | 1 | 512 MB | 30 GB | 500 GB | $26.99/year | [ Get the 512 MB plan](https://my.racknerd.com/cart.php?a=add&pid=1&aff=11397) |
| 1 GB | 2 | 1 GB | 50 GB | 1 TB | $17.99/mo | [ Order 1 GB monthly](https://my.racknerd.com/cart.php?a=add&pid=20&aff=11397) |
| 2 GB | 3 | 2 GB | 75 GB | 2 TB | $20.59/mo | [ Order 2 GB monthly](https://my.racknerd.com/cart.php?a=add&pid=21&aff=11397) |
| 4 GB | 4 | 4 GB | 130 GB | 3 TB | $24.59/mo | [ Order 4 GB monthly](https://my.racknerd.com/cart.php?a=add&pid=22&aff=11397) |
| 6 GB | 5 | 6 GB | 170 GB | 4 TB | $27.59/mo | [ Order 6 GB monthly](https://my.racknerd.com/cart.php?a=add&pid=23&aff=11397) |
| 8 GB | 6 | 8 GB | 220 GB | 5 TB | $36.59/mo | [ Order 8 GB monthly](https://my.racknerd.com/cart.php?a=add&pid=24&aff=11397) |
| 12 GB | 7 | 12 GB | 300 GB | 6 TB | $55.99/mo | [ Order 12 GB monthly](https://my.racknerd.com/cart.php?a=add&pid=25&aff=11397) |

Catalog plans are mostly monthly and available across more locations, including Amsterdam, France, and Dublin alongside the US cities and Toronto.

The yearly specials are a different animal — lower specs per dollar tier, but radically cheaper because you prepay a full year:

| Special | vCPU | RAM | SSD | Traffic | Price/year | Order |
| --- | --- | --- | --- | --- | --- | --- |
| 1 GB | 1 | 1 GB | 20 GB | 3 TB | $21.99 | [ Buy the 1 GB special](https://my.racknerd.com/cart.php?a=add&pid=952&aff=11397) |
| 2 GB | 2 | 2 GB | 35 GB | 5 TB | $35.99 | [ Buy the 2 GB special](https://my.racknerd.com/cart.php?a=add&pid=953&aff=11397) |
| 4 GB | 3 | 4 GB | 60 GB | 7 TB | $59.99 | [ Buy the 4 GB special](https://my.racknerd.com/cart.php?a=add&pid=954&aff=11397) |
| 6 GB | 6 | 6 GB | 100 GB | 12 TB | $89.99 | [ Buy the 6 GB special](https://my.racknerd.com/cart.php?a=add&pid=955&aff=11397) |
| 8 GB | 7 | 8 GB | 150 GB | 20 TB | $119.99 | [ Buy the 8 GB special](https://my.racknerd.com/cart.php?a=add&pid=956&aff=11397) |

Specials rotate through US datacenters (New York, Los Angeles, Atlanta, Chicago, Dallas, Seattle, San Jose, Ashburn) plus Toronto, and they're sold while stock lasts.

RackNerd also sells cPanel shared hosting and dedicated servers on the same site — shared plans and bare-metal boxes aren't part of this VPS comparison, but if you land there for a dedicated machine, the **15OFFDEDI** code takes 15% off, and it applies to dedicated servers only, not VPS specials.

## The renewal math nobody spells out

Here's the detail most comparison articles gloss over: RackNerd's two product lines have completely different renewal behavior.

The yearly specials page states that these plans **"renew indefinitely at the same rate."** That's rare in this market. Most budget hosts treat year one as a loss leader and then reset you to a higher renewal price — Hostinger's renewal is $11.99 after a $6.49 intro, and Hostwinds jumps about 30%.

There's a catch on the other side: specials are stock-limited, and after your first year the exact plan you bought often disappears from the store. You'd then re-buy whatever special is currently live or move onto a catalog plan. The special you hold keeps renewing at its original rate as long as you don't let it lapse — which makes canceling one of these things a decision worth pausing over.

The catalog-vs-special gap is enormous. The 4 GB catalog plan costs $24.59/month, which works out to roughly $295/year. The 4 GB special is $59.99/year — about a fifth of the cost, with slightly fewer vCPUs (3 vs. 4) and less SSD (60 GB vs. 130 GB) but more traffic (7 TB vs. 3 TB). Over 36 months, the catalog 4 GB plan adds up to around $885. If your workload fits 60 GB of storage, the special is the obvious choice. If it doesn't, don't force it.

The 1 GB numbers tell the same story: $17.99/month on catalog ($215.88/year) versus $21.99/year on the special. Same RAM, similar traffic, an order of magnitude apart in cost.

## The refund reality: read this before you click buy

RackNerd does not offer a money-back guarantee. Their terms state it plainly: refunds are handled case-by-case, because "by default no refunds are provided once payment is received." Prepaid account credit is explicitly non-refundable, and initiating a credit card chargeback triggers a $125–$250 administrative fee on top of possible account suspension.

Refunds do happen — mainly for fresh orders with a genuine technical fault (VPS won't boot, IP unreachable) or a dedicated server that misses its 72-hour delivery promise — but "I changed my mind" after a few days of use is very likely to be declined, though support may offer alternatives like account credit, a location change, or a plan swap.

This makes the buying sequence matter more at RackNerd than at most providers:

1. **Test the network before paying.** Every datacenter has a public Looking Glass with test IPs — Los Angeles DC02 at 198.52.116.4, San Jose at 192.210.207.88, New York at 192.3.253.2 — plus downloadable test files. Ping them from your own connection first.
2. **Use monthly as your trial.** The 1 GB catalog plan at $17.99/month costs under $0.60 per day. That's your insurance policy against a year-long commitment to a route you end up disliking. RackNerd's own knowledge base recommends exactly this.
3. **Use your first 72 hours.** IP changes are free within 72 hours of delivery and cost $3 each after that. That window is when you have the most leverage, so test latency, throughput, and the IP's reputation immediately.
4. **Never click "Immediate Cancellation" casually.** It terminates the service within 24 hours and deletes all data irrecoverably. If you misclick, open a ticket right away — support can restore the service.

Payment options include credit cards, PayPal, Bitcoin, and Alipay. PayPal and cards give you an external dispute mechanism in theory; in practice, the chargeback fee makes it a bad tool here. Bitcoin and Alipay leave you with in-platform tickets only.

## How RackNerd stacks up against the other budget providers

Here's the entry-level comparison using independently tracked data. All figures below are for the competitors' entry plans as published in 2026:

| Provider | Entry price | Entry specs | Renewal | Uptime (12 mo) | Ticket response |
| --- | --- | --- | --- | --- | --- |
| Contabo | $5.99/mo | 2 vCPU, 4 GB RAM, 50 GB NVMe, 32 TB | $6.99/mo (+17%) | 99.6% | 6–24 hours |
| InterServer | $6.00/mo | 1 vCPU, 2 GB RAM, 30 GB SSD, 1 TB | $6.00/mo (locked) | 99.9% | 1–4 hours |
| Hostwinds | $4.99/mo | 1 vCPU, 1 GB RAM, 30 GB SSD, 1 TB | ~$6.49/mo (+30%) | 99.9% | 30 min–2 hours |
| Vultr | $2.50/mo | 1 vCPU, 512 MB RAM, 10 GB NVMe, 500 GB | Hourly, no contracts | 99.99% | Ticket + KB |
| Hostinger | $6.49/mo | KVM, NVMe, up to 8 vCPU/32 GB on higher tiers | $11.99/mo | n/a | Ticket + chat |

RackNerd doesn't fit neatly in that table because its cheapest meaningful plan bills yearly: 1 GB, 20 GB SSD, 3 TB traffic for $21.99/year — about $1.83/month. Contabo's 4 GB at $5.99/month beats it on raw specs per dollar if you need RAM and bandwidth in bulk (32 TB of traffic is enormous), and its entry plan is genuinely competitive. Where RackNerd wins is the 24-month total: one third-party cost analysis put RackNerd's two-year spend at $83.28 versus $155.76 for Contabo's monthly billing, $144 for InterServer, and $137.76 for Hostwinds — all serving roughly comparable entry workloads.

Vultr occupies its own niche. Its 512 MB plan at $2.50/month is memory-starved for most uses, but hourly billing across roughly 32 datacenters is genuinely useful for bursty workloads — run an inference job for an hour, destroy the server, pay for the hour. RackNerd can't do that; you're buying months or years.

Performance-wise, expect RackNerd to sit below Vultr: third-party load testing puts its per-core CPU score around 2,800 versus Vultr's 4,100, with disk IOPS at roughly 20K versus 50K, and network speeds around 750 Mbps versus 950 Mbps. Contabo lands in between on CPU but matches neither on IOPS. None of this matters much for a low-traffic website, a VPN endpoint, a small game server, or a hobby project. It matters if you're doing database-heavy or latency-sensitive work.

## What existing customers say

RackNerd holds a **4.3 on Trustpilot** across 384 reviews as of early November. The positive reviews consistently mention value for money, long-term uptime, and quick support replies. The negative cluster around a handful of recurring complaints: packet loss on certain routes, blocked IPs, refused refunds during connectivity incidents, and services terminated after copyright complaints. That last category is worth taking seriously if you plan to run anything with questionable licensing — RackNerd appears to act on those reports.

## FAQ

**Does RackNerd have promo codes for VPS?**
No general VPS coupon codes — the yearly specials are already the promo price, and buying them directly gets you the deal. The only public code is 15OFFDEDI for dedicated servers.

**Can I get more bandwidth on a special plan?**
There's a documented trick: post a comment on RackNerd's designated LowEndTalk thread with your order number, using the format "Hello, I would like to double the bandwidth. Order Number: [your order number] Thanks!" Customers who do this have had their monthly traffic doubled for free. It's an odd system, but it works, and it makes the traffic numbers on the specials table effectively conservative.

**Which plan should I avoid?**
The 512 MB catalog plan is the odd one out. It's yearly-only at $26.99/year with 500 GB of traffic — yet the 1 GB special costs $5 less per year with double the RAM, double-plus traffic, and better long-term flexibility. Unless you specifically need the tiny footprint, skip it.

**Do plans include IPv6?**
Los Angeles and France locations can be assigned up to 100 free IPv6 addresses; you request them via a support ticket after ordering.

## Bottom line: which provider fits which situation

- **Tightest budget, US-only locations, willing to prepay and self-manage** → RackNerd's 1 GB or 2 GB yearly special. Renewal stays flat, which is the whole game in this price bracket.
- **Need lots of RAM and bandwidth cheap, EU locations** → Contabo's entry plan. Accept the slower support.
- **Want zero renewal surprises above all else** → InterServer's price-locked $6/month plan.
- **Bursty, short-lived workloads or global datacenter coverage** → Vultr's hourly model.
- **Someone else to handle the server** → a managed option like ScalaHosting, starting at $29.95/month. That's 16 times the RackNerd 1 GB special's effective monthly cost, and you're paying for labor, not hardware.

One last thing before you order anything from RackNerd: run the Looking Glass tests from your own connection, and if you're going yearly, pick the datacenter whose latency you've actually measured — because once that first year is paid, the practical refund path is narrow. If the numbers hold up on your route, the [👉 2 GB yearly special at $35.99](https://my.racknerd.com/cart.php?a=add&pid=953&aff=11397) is the sweet spot for most self-hosting projects — enough RAM for a small stack of services, 5 TB of traffic, and a renewal price that never moves.
