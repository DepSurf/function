# Function: <code>if_nlmsg_stats_size</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81796682)
Location: net/core/rtnetlink.c:3649
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff817c4ca0)
Location: net/core/rtnetlink.c:3846
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff817e36cf)
Location: net/core/rtnetlink.c:3992
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff8185e5ff)
Location: net/core/rtnetlink.c:4237
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff818aa1b0)
Location: net/core/rtnetlink.c:4395
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff818ce8a0)
Location: net/core/rtnetlink.c:4840
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff8191b696)
Location: net/core/rtnetlink.c:4913
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff8194dcd3)
Location: net/core/rtnetlink.c:4944
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t if_nlmsg_stats_size(const struct net_device *dev, u32 filter_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a19150)
Location: net/core/rtnetlink.c:5151
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81a19150-ffffffff81a19283: if_nlmsg_stats_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t if_nlmsg_stats_size(const struct net_device *dev, u32 filter_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a19340)
Location: net/core/rtnetlink.c:5243
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81a19340-ffffffff81a19478: if_nlmsg_stats_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t if_nlmsg_stats_size(const struct net_device *dev, u32 filter_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a00250)
Location: net/core/rtnetlink.c:5245
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81a00250-ffffffff81a00388: if_nlmsg_stats_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t if_nlmsg_stats_size(const struct net_device *dev, u32 filter_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab23a0)
Location: net/core/rtnetlink.c:5266
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81ab23a0-ffffffff81ab24dc: if_nlmsg_stats_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t if_nlmsg_stats_size(const struct net_device *dev, const struct rtnl_stats_dump_filters *filters);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c33b3b)
Location: net/core/rtnetlink.c:5588
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81c2c4f0-ffffffff81c2c615: if_nlmsg_stats_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t if_nlmsg_stats_size(const struct net_device *dev, const struct rtnl_stats_dump_filters *filters);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de6f8b)
Location: net/core/rtnetlink.c:5639
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81ddf5e0-ffffffff81ddf705: if_nlmsg_stats_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t if_nlmsg_stats_size(const struct net_device *dev, const struct rtnl_stats_dump_filters *filters);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e57f7b)
Location: net/core/rtnetlink.c:5732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81e50900-ffffffff81e50a25: if_nlmsg_stats_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t if_nlmsg_stats_size(const struct net_device *dev, const struct rtnl_stats_dump_filters *filters);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f172cb)
Location: net/core/rtnetlink.c:5762
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81f0f9b0-ffffffff81f0fad5: if_nlmsg_stats_size (STB_LOCAL)
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
In net/core/rtnetlink.c (ffff800010befc4c)
Location: net/core/rtnetlink.c:4944
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (c0d08254)
Location: net/core/rtnetlink.c:4944
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (c000000000cd3f38)
Location: net/core/rtnetlink.c:4944
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffe000771f0a)
Location: net/core/rtnetlink.c:4944
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff818edca3)
Location: net/core/rtnetlink.c:4944
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff818a7ae3)
Location: net/core/rtnetlink.c:4944
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff8193ecd3)
Location: net/core/rtnetlink.c:4944
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
In net/core/rtnetlink.c (ffffffff81960573)
Location: net/core/rtnetlink.c:4944
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct rtnl_stats_dump_filters *filters</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 filter_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
