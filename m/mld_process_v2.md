# Function: <code>mld_process_v2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff817ecee0)
Location: net/ipv6/mcast.c:1283
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff8185b711)
Location: net/ipv6/mcast.c:1283
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff8188d611)
Location: net/ipv6/mcast.c:1297
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff818b3ce8)
Location: net/ipv6/mcast.c:1297
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (ffffffff81936a58)
Location: net/ipv6/mcast.c:1297
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (ffffffff8198f800)
Location: net/ipv6/mcast.c:1322
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (ffffffff819c60b4)
Location: net/ipv6/mcast.c:1322
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (ffffffff81a34f20)
Location: net/ipv6/mcast.c:1321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (ffffffff81a6ba70)
Location: net/ipv6/mcast.c:1321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mld_process_v2(struct inet6_dev *idev, struct mld2_query *mld, long unsigned int *max_delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:1318
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
**Symbols:**

```
ffffffff81b60a50-ffffffff81b60b6b: mld_process_v2 (STB_LOCAL)
ffffffff81b655f0-ffffffff81b65608: mld_process_v2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mld_process_v2(struct inet6_dev *idev, struct mld2_query *mld, long unsigned int *max_delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:1318
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
**Symbols:**

```
ffffffff81b6f1c0-ffffffff81b6f2db: mld_process_v2 (STB_LOCAL)
ffffffff81c32f4c-ffffffff81c32f64: mld_process_v2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mld_process_v2(struct inet6_dev *idev, struct mld2_query *mld, long unsigned int *max_delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:1354
Inline: False
Direct callers:
  - net/ipv6/mcast.c:__mld_query_work
```
**Symbols:**

```
ffffffff81b5d1d0-ffffffff81b5d2ef: mld_process_v2 (STB_LOCAL)
ffffffff81c2524d-ffffffff81c25267: mld_process_v2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81c27f2a)
Location: net/ipv6/mcast.c:1359
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81dc52c8)
Location: net/ipv6/mcast.c:1359
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81f95e58)
Location: net/ipv6/mcast.c:1359
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81ff6828)
Location: net/ipv6/mcast.c:1359
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff820c4468)
Location: net/ipv6/mcast.c:1359
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
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
In net/ipv6/mcast.c (ffff800010d3338c)
Location: net/ipv6/mcast.c:1321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (c0e360ac)
Location: net/ipv6/mcast.c:1321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (c000000000e65a04)
Location: net/ipv6/mcast.c:1321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (ffffffe000871728)
Location: net/ipv6/mcast.c:1321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (ffffffff81a0b100)
Location: net/ipv6/mcast.c:1321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (ffffffff819c7ec0)
Location: net/ipv6/mcast.c:1321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (ffffffff81a75b80)
Location: net/ipv6/mcast.c:1321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
In net/ipv6/mcast.c (ffffffff81a822b0)
Location: net/ipv6/mcast.c:1321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
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
</ul>
