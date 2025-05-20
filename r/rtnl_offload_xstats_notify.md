# Function: <code>rtnl_offload_xstats_notify</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rtnl_offload_xstats_notify(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:5881
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff81f037e6-ffffffff81f037fb: rtnl_offload_xstats_notify.cold (STB_LOCAL)
ffffffff81c33ac0-ffffffff81c33c50: rtnl_offload_xstats_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rtnl_offload_xstats_notify(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:5932
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff820abf34-ffffffff820abf49: rtnl_offload_xstats_notify.cold (STB_LOCAL)
ffffffff81de6f10-ffffffff81de70a0: rtnl_offload_xstats_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rtnl_offload_xstats_notify(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:6025
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff8212d699-ffffffff8212d6ae: rtnl_offload_xstats_notify.cold (STB_LOCAL)
ffffffff81e57f00-ffffffff81e58090: rtnl_offload_xstats_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rtnl_offload_xstats_notify(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:6055
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff8220f3e6-ffffffff8220f3fb: rtnl_offload_xstats_notify.cold (STB_LOCAL)
ffffffff81f17250-ffffffff81f173e0: rtnl_offload_xstats_notify (STB_GLOBAL)
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
