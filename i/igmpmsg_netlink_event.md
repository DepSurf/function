# Function: <code>igmpmsg_netlink_event</code>

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
In net/ipv4/ipmr.c (ffffffff8186962b)
Location: net/ipv4/ipmr.c:2361
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (ffffffff818e9c78)
Location: net/ipv4/ipmr.c:2526
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (ffffffff8194034d)
Location: net/ipv4/ipmr.c:2409
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (ffffffff819701ca)
Location: net/ipv4/ipmr.c:2422
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (ffffffff819d9a7d)
Location: net/ipv4/ipmr.c:2434
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (ffffffff81a108d5)
Location: net/ipv4/ipmr.c:2435
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void igmpmsg_netlink_event(struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b01f50)
Location: net/ipv4/ipmr.c:2403
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
**Symbols:**

```
ffffffff81b01f50-ffffffff81b0217f: igmpmsg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void igmpmsg_netlink_event(struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b102c0)
Location: net/ipv4/ipmr.c:2411
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
**Symbols:**

```
ffffffff81b102c0-ffffffff81b1051c: igmpmsg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void igmpmsg_netlink_event(struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afded0)
Location: net/ipv4/ipmr.c:2411
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
**Symbols:**

```
ffffffff81afded0-ffffffff81afe12b: igmpmsg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void igmpmsg_netlink_event(struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bbf160)
Location: net/ipv4/ipmr.c:2413
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
**Symbols:**

```
ffffffff81bbf160-ffffffff81bbf3bb: igmpmsg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void igmpmsg_netlink_event(struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d53ed0)
Location: net/ipv4/ipmr.c:2407
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
**Symbols:**

```
ffffffff81d53ed0-ffffffff81d5414e: igmpmsg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void igmpmsg_netlink_event(const struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1e0a0)
Location: net/ipv4/ipmr.c:2414
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
**Symbols:**

```
ffffffff81f1e0a0-ffffffff81f1e31e: igmpmsg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void igmpmsg_netlink_event(const struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7db90)
Location: net/ipv4/ipmr.c:2429
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
**Symbols:**

```
ffffffff81f7db90-ffffffff81f7de0e: igmpmsg_netlink_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void igmpmsg_netlink_event(const struct mr_table *mrt, struct sk_buff *pkt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff820443d0)
Location: net/ipv4/ipmr.c:2427
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
**Symbols:**

```
ffffffff820443d0-ffffffff8204464e: igmpmsg_netlink_event (STB_LOCAL)
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
In net/ipv4/ipmr.c (ffff800010ccb518)
Location: net/ipv4/ipmr.c:2435
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (c0dd5a10)
Location: net/ipv4/ipmr.c:2435
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (c000000000de81a8)
Location: net/ipv4/ipmr.c:2435
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (ffffffe00081e82e)
Location: net/ipv4/ipmr.c:2435
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (ffffffff819b02e5)
Location: net/ipv4/ipmr.c:2435
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (ffffffff8196c915)
Location: net/ipv4/ipmr.c:2435
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (ffffffff81a1ab85)
Location: net/ipv4/ipmr.c:2435
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
In net/ipv4/ipmr.c (ffffffff81a259ea)
Location: net/ipv4/ipmr.c:2435
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
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
