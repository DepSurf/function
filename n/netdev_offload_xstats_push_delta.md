# Function: <code>netdev_offload_xstats_push_delta</code>

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
void netdev_offload_xstats_push_delta(struct net_device *dev, enum netdev_offload_xstats_type type, const struct rtnl_hw_stats64 *p_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8113
Inline: False
```
**Symbols:**

```
ffffffff81f02804-ffffffff81f02819: netdev_offload_xstats_push_delta.cold (STB_LOCAL)
ffffffff81c138f0-ffffffff81c139de: netdev_offload_xstats_push_delta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void netdev_offload_xstats_push_delta(struct net_device *dev, enum netdev_offload_xstats_type type, const struct rtnl_hw_stats64 *p_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8099
Inline: False
```
**Symbols:**

```
ffffffff820ab3dc-ffffffff820ab3f1: netdev_offload_xstats_push_delta.cold (STB_LOCAL)
ffffffff81dc2f60-ffffffff81dc304e: netdev_offload_xstats_push_delta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void netdev_offload_xstats_push_delta(struct net_device *dev, enum netdev_offload_xstats_type type, const struct rtnl_hw_stats64 *p_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8104
Inline: False
```
**Symbols:**

```
ffffffff8212ca11-ffffffff8212ca26: netdev_offload_xstats_push_delta.cold (STB_LOCAL)
ffffffff81e32400-ffffffff81e324ee: netdev_offload_xstats_push_delta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void netdev_offload_xstats_push_delta(struct net_device *dev, enum netdev_offload_xstats_type type, const struct rtnl_hw_stats64 *p_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8222
Inline: False
```
**Symbols:**

```
ffffffff8220e750-ffffffff8220e765: netdev_offload_xstats_push_delta.cold (STB_LOCAL)
ffffffff81ef08c0-ffffffff81ef09ae: netdev_offload_xstats_push_delta (STB_GLOBAL)
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
