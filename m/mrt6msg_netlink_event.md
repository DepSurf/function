# Function: <code>mrt6msg_netlink_event</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff818c159b)
Location: net/ipv6/ip6mr.c:2479
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819448eb)
Location: net/ipv6/ip6mr.c:2484
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8199d625)
Location: net/ipv6/ip6mr.c:2385
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d4185)
Location: net/ipv6/ip6mr.c:2417
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a43023)
Location: net/ipv6/ip6mr.c:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a79b83)
Location: net/ipv6/ip6mr.c:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mrt6msg_netlink_event(struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b74470)
Location: net/ipv6/ip6mr.c:2440
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff81b74470-ffffffff81b74691: mrt6msg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mrt6msg_netlink_event(struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b831e0)
Location: net/ipv6/ip6mr.c:2441
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff81b831e0-ffffffff81b83401: mrt6msg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mrt6msg_netlink_event(struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b71e60)
Location: net/ipv6/ip6mr.c:2441
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff81b71e60-ffffffff81b7207a: mrt6msg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mrt6msg_netlink_event(struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81c3c310)
Location: net/ipv6/ip6mr.c:2442
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff81c3c310-ffffffff81c3c52a: mrt6msg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mrt6msg_netlink_event(struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81dda6d0)
Location: net/ipv6/ip6mr.c:2463
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff81dda6d0-ffffffff81dda8fd: mrt6msg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mrt6msg_netlink_event(const struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81fac3f0)
Location: net/ipv6/ip6mr.c:2468
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff81fac3f0-ffffffff81fac61d: mrt6msg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mrt6msg_netlink_event(const struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8200cb90)
Location: net/ipv6/ip6mr.c:2460
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff8200cb90-ffffffff8200cdbd: mrt6msg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mrt6msg_netlink_event(const struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff820dbb60)
Location: net/ipv6/ip6mr.c:2458
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
**Symbols:**

```
ffffffff820dbb60-ffffffff820dbd8d: mrt6msg_netlink_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffff800010d43e7c)
Location: net/ipv6/ip6mr.c:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c0e45c38)
Location: net/ipv6/ip6mr.c:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c000000000e789d8)
Location: net/ipv6/ip6mr.c:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffe00087e9fa)
Location: net/ipv6/ip6mr.c:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a19213)
Location: net/ipv6/ip6mr.c:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d5fd3)
Location: net/ipv6/ip6mr.c:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a83c93)
Location: net/ipv6/ip6mr.c:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a905b8)
Location: net/ipv6/ip6mr.c:2435
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mr_table *mrt</code> ➡️ <code>const struct mr_table *mrt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
