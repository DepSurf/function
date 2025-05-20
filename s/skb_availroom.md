# Function: <code>skb_availroom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817697d3)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff817786ce)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff81796524)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff817ea6a8)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d61a8)
Location: include/linux/skbuff.h:1990
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff817e570e)
Location: include/linux/skbuff.h:1990
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff818042b9)
Location: include/linux/skbuff.h:1990
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81858f78)
Location: include/linux/skbuff.h:1990
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818061c9)
Location: include/linux/skbuff.h:2007
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff81815bcc)
Location: include/linux/skbuff.h:2007
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff8183525e)
Location: include/linux/skbuff.h:2007
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff8188ad7d)
Location: include/linux/skbuff.h:2007
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81826654)
Location: include/linux/skbuff.h:2046
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff81835f70)
Location: include/linux/skbuff.h:2046
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff8185683c)
Location: include/linux/skbuff.h:2046
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff818b1b48)
Location: include/linux/skbuff.h:2046
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a473f)
Location: include/linux/skbuff.h:2133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff818b5565)
Location: include/linux/skbuff.h:2133
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff818d666c)
Location: include/linux/skbuff.h:2133
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81933e35)
Location: include/linux/skbuff.h:2133
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818fa481)
Location: include/linux/skbuff.h:2144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff8190ac8b)
Location: include/linux/skbuff.h:2144
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff8192d027)
Location: include/linux/skbuff.h:2144
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff8198ca79)
Location: include/linux/skbuff.h:2144
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819283bb)
Location: include/linux/skbuff.h:2222
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81938f33)
Location: include/linux/skbuff.h:2222
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff8195c4c4)
Location: include/linux/skbuff.h:2222
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff819c32f6)
Location: include/linux/skbuff.h:2222
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8198b336)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff8199d178)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff819c11c0)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81a3212b)
Location: include/linux/skbuff.h:2310
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c1bab)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff819d3c38)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff819f7d60)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81a68c7b)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aad3e8)
Location: include/linux/skbuff.h:2347
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81ac01a1)
Location: include/linux/skbuff.h:2347
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
```
In net/ipv4/igmp.c (ffffffff81ae58b0)
Location: include/linux/skbuff.h:2347
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81b6124c)
Location: include/linux/skbuff.h:2347
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab47b8)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81acbbfb)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
```
In net/ipv4/igmp.c (ffffffff81af2770)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81b6f9cc)
Location: include/linux/skbuff.h:2368
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9f91b)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81ab6e6b)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
```
In net/ipv4/igmp.c (ffffffff81addf50)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81b5dd1e)
Location: include/linux/skbuff.h:2384
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5b6d4)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81b74058)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
```
In net/ipv4/igmp.c (ffffffff81b9d3f0)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81c251d1)
Location: include/linux/skbuff.h:2413
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d2f560)
Location: include/linux/skbuff.h:2781
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81dc2533)
Location: include/linux/skbuff.h:2781
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef7620)
Location: include/linux/skbuff.h:2673
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81f93233)
Location: include/linux/skbuff.h:2673
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f570a0)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81ff384d)
Location: include/linux/skbuff.h:2727
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201d54d)
Location: include/linux/skbuff.h:2734
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff820c18ca)
Location: include/linux/skbuff.h:2734
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c749c8)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffff800010c86660)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffff800010cade80)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffff800010d2f1f0)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d83070)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (c0d95b38)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (c0dbb268)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (c0e33038)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7bd34)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (c000000000d93078)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (c000000000dc5174)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (c000000000e61f94)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d7dd8)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffe0007e7c6c)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffe000808882)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffe00086f03e)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81961a1b)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81973aa8)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff81997b00)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81a0830b)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191b50b)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff8192d578)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff819515c0)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff819c50cb)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cc1eb)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff819de278)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff81a023a0)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81a72d8b)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d5d7b)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff819e7ef8)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/igmp.c (ffffffff81a0c8c0)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grec
```
```
In net/ipv6/mcast.c (ffffffff81a7f40b)
Location: include/linux/skbuff.h:2324
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grec
```
</details>
</li>
</ul>

## Differences
