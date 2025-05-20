# Function: <code>netdev_offload_xstats_enabled</code>

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
bool netdev_offload_xstats_enabled(const struct net_device *dev, enum netdev_offload_xstats_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7993
Inline: False
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/rtnetlink.c:rtnl_offload_xstats_get_size
  - net/core/rtnetlink.c:rtnl_offload_xstats_get_size
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
**Symbols:**

```
ffffffff81f01e37-ffffffff81f01e4c: netdev_offload_xstats_enabled.cold (STB_LOCAL)
ffffffff81c0de00-ffffffff81c0de8e: netdev_offload_xstats_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool netdev_offload_xstats_enabled(const struct net_device *dev, enum netdev_offload_xstats_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7979
Inline: False
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/rtnetlink.c:rtnl_offload_xstats_get_size
  - net/core/rtnetlink.c:rtnl_offload_xstats_get_size
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
**Symbols:**

```
ffffffff820ab1b9-ffffffff820ab1ce: netdev_offload_xstats_enabled.cold (STB_LOCAL)
ffffffff81dbdca0-ffffffff81dbdd2e: netdev_offload_xstats_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool netdev_offload_xstats_enabled(const struct net_device *dev, enum netdev_offload_xstats_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7984
Inline: False
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/rtnetlink.c:rtnl_offload_xstats_get_size
  - net/core/rtnetlink.c:rtnl_offload_xstats_get_size
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
**Symbols:**

```
ffffffff8212c862-ffffffff8212c877: netdev_offload_xstats_enabled.cold (STB_LOCAL)
ffffffff81e2e4f0-ffffffff81e2e57e: netdev_offload_xstats_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool netdev_offload_xstats_enabled(const struct net_device *dev, enum netdev_offload_xstats_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8102
Inline: False
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_disable
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/rtnetlink.c:rtnl_offload_xstats_get_size
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
**Symbols:**

```
ffffffff8220e5a1-ffffffff8220e5b6: netdev_offload_xstats_enabled.cold (STB_LOCAL)
ffffffff81eeca10-ffffffff81eeca9e: netdev_offload_xstats_enabled (STB_GLOBAL)
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
