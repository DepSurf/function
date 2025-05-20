# Function: <code>stats_put_rmon_hist</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/stats.c (ffffffff81a82b86)
Location: net/ethtool/stats.c:289
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
```
**Symbols:**

```
ffffffff81a82a00-ffffffff81a82b6f: stats_put_rmon_hist.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/stats.c (ffffffff81b3c706)
Location: net/ethtool/stats.c:289
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
```
**Symbols:**

```
ffffffff81b3c580-ffffffff81b3c6ef: stats_put_rmon_hist.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int stats_put_rmon_hist(struct sk_buff *skb, u32 attr, const u64 *hist, const struct ethtool_rmon_hist_range *ranges);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81cc8590)
Location: net/ethtool/stats.c:288
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
```
**Symbols:**

```
ffffffff81cc8590-ffffffff81cc870b: stats_put_rmon_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int stats_put_rmon_hist(struct sk_buff *skb, u32 attr, const u64 *hist, const struct ethtool_rmon_hist_range *ranges);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81e87d10)
Location: net/ethtool/stats.c:288
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
```
**Symbols:**

```
ffffffff81e87d10-ffffffff81e87e8b: stats_put_rmon_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int stats_put_rmon_hist(struct sk_buff *skb, u32 attr, const u64 *hist, const struct ethtool_rmon_hist_range *ranges);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81ee49b0)
Location: net/ethtool/stats.c:315
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
```
**Symbols:**

```
ffffffff81ee49b0-ffffffff81ee4b2b: stats_put_rmon_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int stats_put_rmon_hist(struct sk_buff *skb, u32 attr, const u64 *hist, const struct ethtool_rmon_hist_range *ranges);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81fa8790)
Location: net/ethtool/stats.c:314
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
```
**Symbols:**

```
ffffffff81fa8790-ffffffff81fa890b: stats_put_rmon_hist (STB_LOCAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
