# Function: <code>netdev_offload_xstats_disable</code>

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
int netdev_offload_xstats_disable(struct net_device *dev, enum netdev_offload_xstats_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7956
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff81f01e8b-ffffffff81f01ea0: netdev_offload_xstats_disable.cold (STB_LOCAL)
ffffffff81c0e2a0-ffffffff81c0e3bf: netdev_offload_xstats_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_disable(struct net_device *dev, enum netdev_offload_xstats_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7942
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff820ab20d-ffffffff820ab222: netdev_offload_xstats_disable.cold (STB_LOCAL)
ffffffff81dbe330-ffffffff81dbe44f: netdev_offload_xstats_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_disable(struct net_device *dev, enum netdev_offload_xstats_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7947
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff8212ccef-ffffffff8212cd04: netdev_offload_xstats_disable.cold (STB_LOCAL)
ffffffff81e39950-ffffffff81e39a6f: netdev_offload_xstats_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int netdev_offload_xstats_disable(struct net_device *dev, enum netdev_offload_xstats_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8065
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/rtnetlink.c:rtnl_stats_set
```
**Symbols:**

```
ffffffff8220ea2e-ffffffff8220ea43: netdev_offload_xstats_disable.cold (STB_LOCAL)
ffffffff81ef7c40-ffffffff81ef7d5f: netdev_offload_xstats_disable (STB_GLOBAL)
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
