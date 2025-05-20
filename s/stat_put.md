# Function: <code>stat_put</code>

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
In net/ethtool/stats.c (ffffffff81a82bd2)
Location: net/ethtool/stats.c:182
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_phy_stats
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_phy_stats
```
**Symbols:**

```
ffffffff81a825a0-ffffffff81a82676: stat_put.part.0 (STB_LOCAL)
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
In net/ethtool/stats.c (ffffffff81b3c752)
Location: net/ethtool/stats.c:182
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_phy_stats
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_phy_stats
```
**Symbols:**

```
ffffffff81b3c120-ffffffff81b3c1f6: stat_put.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int stat_put(struct sk_buff *skb, u16 attrtype, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81cc8170)
Location: net/ethtool/stats.c:181
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_phy_stats
```
**Symbols:**

```
ffffffff81cc8170-ffffffff81cc8264: stat_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int stat_put(struct sk_buff *skb, u16 attrtype, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81e878b0)
Location: net/ethtool/stats.c:181
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_phy_stats
```
**Symbols:**

```
ffffffff81e878b0-ffffffff81e879a4: stat_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int stat_put(struct sk_buff *skb, u16 attrtype, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81ee4540)
Location: net/ethtool/stats.c:208
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_phy_stats
```
**Symbols:**

```
ffffffff81ee4540-ffffffff81ee4634: stat_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int stat_put(struct sk_buff *skb, u16 attrtype, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81fa8320)
Location: net/ethtool/stats.c:207
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_rmon_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_ctrl_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_mac_stats
  - net/ethtool/stats.c:stats_put_phy_stats
```
**Symbols:**

```
ffffffff81fa8320-ffffffff81fa8414: stat_put (STB_LOCAL)
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
