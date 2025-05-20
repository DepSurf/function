# Function: <code>ipcm_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191c4e4)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff819479e1)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81949d9c)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81953203)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81969db0)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff8197e817)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff819ac751)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819ae429)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff819b7d5b)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff819d0a71)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff819b51b7)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff819e3301)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e5139)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff819eea5b)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81a075c1)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81a9f416)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff81ad0bd2)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ad4f81)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81adc7d2)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81af6e22)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81aa9356)
Location: include/net/ip.h:82
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff81adcb12)
Location: include/net/ip.h:82
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ae14c3)
Location: include/net/ip.h:82
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81ae94ed)
Location: include/net/ip.h:82
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81b03cb1)
Location: include/net/ip.h:82
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81a9451c)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff81ac7b7d)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81acb0a7)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81ad4bcd)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ping.c (ffffffff81aef910)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81b4f99c)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff81b863dd)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81b89937)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81b938b7)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ping.c (ffffffff81baf920)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81cdd414)
Location: include/net/ip.h:85
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff81d16da9)
Location: include/net/ip.h:85
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81d1d2b9)
Location: include/net/ip.h:85
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81d246f0)
Location: include/net/ip.h:85
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ping.c (ffffffff81d42ed8)
Location: include/net/ip.h:85
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81e9ded3)
Location: include/net/ip.h:85
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff81edd579)
Location: include/net/ip.h:85
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ee43e4)
Location: include/net/ip.h:85
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81eebed0)
Location: include/net/ip.h:85
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ping.c (ffffffff81f0bec8)
Location: include/net/ip.h:85
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81efc69d)
Location: include/net/ip.h:86
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff81f3c7da)
Location: include/net/ip.h:86
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81f43d1b)
Location: include/net/ip.h:86
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81f4bcc6)
Location: include/net/ip.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ping.c (ffffffff81f6bb43)
Location: include/net/ip.h:86
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81fc05dd)
Location: include/net/ip.h:87
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff820028f8)
Location: include/net/ip.h:87
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff82009c94)
Location: include/net/ip.h:87
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff82011dd6)
Location: include/net/ip.h:87
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ping.c (ffffffff82032103)
Location: include/net/ip.h:87
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffff800010c65980)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffff800010c97f98)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c9de00)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffff800010ca4c64)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffff800010cc05d0)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (c0d755c0)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (c0da5dec)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c0da8b04)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (c0db0d50)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (c0dcc848)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (c000000000d6a0d4)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (c000000000da9208)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000dafd24)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (c000000000db8058)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (c000000000ddb8ac)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffe0007cd0d2)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffe0007f6332)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f7d24)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffe0007ffe82)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffe000816d62)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81955027)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff81983171)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81984fa9)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff8198e7fb)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff819a7361)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff8190eb17)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff8193cc31)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8193ea69)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff819482bb)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81960e21)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff819bf7f7)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff819ed941)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819ef779)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff819f909b)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81a11c01)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
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
In net/ipv4/ip_output.c (ffffffff819c9177)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/raw.c (ffffffff819f7831)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819f9f69)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81a02f93)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ping.c (ffffffff81a1c577)
Location: include/net/ip.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
</details>
</li>
</ul>

## Differences
