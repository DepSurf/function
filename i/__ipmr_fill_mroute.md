# Function: <code>__ipmr_fill_mroute</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817a84e0)
Location: net/ipv4/ipmr.c:2146
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ipmr_get_route
```
**Symbols:**

```
ffffffff817a84e0-ffffffff817a86cb: __ipmr_fill_mroute.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81815bc0)
Location: net/ipv4/ipmr.c:2073
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81815bc0-ffffffff81815dff: __ipmr_fill_mroute.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81847370)
Location: net/ipv4/ipmr.c:2084
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81847370-ffffffff818475af: __ipmr_fill_mroute.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mfc_cache *c, struct rtmsg *rtm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81869f90)
Location: net/ipv4/ipmr.c:2140
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
```
**Symbols:**

```
ffffffff81869f90-ffffffff8186a1a3: __ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mfc_cache *c, struct rtmsg *rtm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818ea6f0)
Location: net/ipv4/ipmr.c:2302
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff818ea6f0-ffffffff818ea928: __ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
