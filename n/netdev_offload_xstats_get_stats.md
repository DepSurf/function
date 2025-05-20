# Function: <code>netdev_offload_xstats_get_stats</code>

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
int netdev_offload_xstats_get_stats(struct net_device *dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 *p_stats, bool *p_used, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8046
Inline: False
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get
```
**Symbols:**

```
ffffffff81c0e3c0-ffffffff81c0e514: netdev_offload_xstats_get_stats (STB_LOCAL)
ffffffff81f01ea0-ffffffff81f01eb4: netdev_offload_xstats_get_stats.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_get_stats(struct net_device *dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 *p_stats, bool *p_used, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8032
Inline: False
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get
```
**Symbols:**

```
ffffffff81dbe460-ffffffff81dbe5b4: netdev_offload_xstats_get_stats (STB_LOCAL)
ffffffff820ab222-ffffffff820ab236: netdev_offload_xstats_get_stats.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_get_stats(struct net_device *dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 *p_stats, bool *p_used, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8037
Inline: False
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get
```
**Symbols:**

```
ffffffff81e39a80-ffffffff81e39bd4: netdev_offload_xstats_get_stats (STB_LOCAL)
ffffffff8212cd04-ffffffff8212cd18: netdev_offload_xstats_get_stats.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_get_stats(struct net_device *dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 *p_stats, bool *p_used, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8155
Inline: False
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get
```
**Symbols:**

```
ffffffff81ef7d70-ffffffff81ef7ec4: netdev_offload_xstats_get_stats (STB_LOCAL)
ffffffff8220ea43-ffffffff8220ea57: netdev_offload_xstats_get_stats.cold (STB_LOCAL)
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
