# Function: <code>netdev_offload_xstats_enable</code>

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
int netdev_offload_xstats_enable(struct net_device *dev, enum netdev_offload_xstats_type type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7924
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff81f02718-ffffffff81f02742: netdev_offload_xstats_enable.cold (STB_LOCAL)
ffffffff81c10df0-ffffffff81c10fcc: netdev_offload_xstats_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_enable(struct net_device *dev, enum netdev_offload_xstats_type type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7910
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff820ab34a-ffffffff820ab374: netdev_offload_xstats_enable.cold (STB_LOCAL)
ffffffff81dc0870-ffffffff81dc0a4c: netdev_offload_xstats_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_enable(struct net_device *dev, enum netdev_offload_xstats_type type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7915
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff8212c94c-ffffffff8212c976: netdev_offload_xstats_enable.cold (STB_LOCAL)
ffffffff81e303f0-ffffffff81e305cc: netdev_offload_xstats_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_enable(struct net_device *dev, enum netdev_offload_xstats_type type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8033
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff8220e6e8-ffffffff8220e712: netdev_offload_xstats_enable.cold (STB_LOCAL)
ffffffff81eef330-ffffffff81eef53b: netdev_offload_xstats_enable (STB_GLOBAL)
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
