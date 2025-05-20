# Function: <code>netdev_offload_xstats_get</code>

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
int netdev_offload_xstats_get(struct net_device *dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 *p_stats, bool *p_used, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8081
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
**Symbols:**

```
ffffffff81f01eb4-ffffffff81f01eed: netdev_offload_xstats_get.cold (STB_LOCAL)
ffffffff81c0e520-ffffffff81c0e66b: netdev_offload_xstats_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_get(struct net_device *dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 *p_stats, bool *p_used, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8067
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
**Symbols:**

```
ffffffff820ab236-ffffffff820ab26f: netdev_offload_xstats_get.cold (STB_LOCAL)
ffffffff81dbe5d0-ffffffff81dbe71b: netdev_offload_xstats_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_get(struct net_device *dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 *p_stats, bool *p_used, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8072
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
**Symbols:**

```
ffffffff8212cd18-ffffffff8212cd51: netdev_offload_xstats_get.cold (STB_LOCAL)
ffffffff81e39bf0-ffffffff81e39d3b: netdev_offload_xstats_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_get(struct net_device *dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 *p_stats, bool *p_used, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8190
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
```
**Symbols:**

```
ffffffff8220ea57-ffffffff8220ea90: netdev_offload_xstats_get.cold (STB_LOCAL)
ffffffff81ef7ee0-ffffffff81ef802b: netdev_offload_xstats_get (STB_GLOBAL)
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
