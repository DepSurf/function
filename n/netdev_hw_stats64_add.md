# Function: <code>netdev_hw_stats64_add</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void netdev_hw_stats64_add(struct rtnl_hw_stats64 *dest, const struct rtnl_hw_stats64 *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c13928)
Location: net/core/dev.c:8011
Inline: True
Inline callers:
  - net/core/dev.c:netdev_offload_xstats_push_delta
  - net/core/dev.c:netdev_offload_xstats_report_delta
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get_stats
```
**Symbols:**

```
ffffffff81c0b650-ffffffff81c0b6ab: netdev_hw_stats64_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void netdev_hw_stats64_add(struct rtnl_hw_stats64 *dest, const struct rtnl_hw_stats64 *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc2f98)
Location: net/core/dev.c:7997
Inline: True
Inline callers:
  - net/core/dev.c:netdev_offload_xstats_push_delta
  - net/core/dev.c:netdev_offload_xstats_report_delta
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get_stats
```
**Symbols:**

```
ffffffff81dbb680-ffffffff81dbb6db: netdev_hw_stats64_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void netdev_hw_stats64_add(struct rtnl_hw_stats64 *dest, const struct rtnl_hw_stats64 *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e32438)
Location: net/core/dev.c:8002
Inline: True
Inline callers:
  - net/core/dev.c:netdev_offload_xstats_push_delta
  - net/core/dev.c:netdev_offload_xstats_report_delta
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get_stats
```
**Symbols:**

```
ffffffff81e2be10-ffffffff81e2be6b: netdev_hw_stats64_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void netdev_hw_stats64_add(struct rtnl_hw_stats64 *dest, const struct rtnl_hw_stats64 *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef08f8)
Location: net/core/dev.c:8120
Inline: True
Inline callers:
  - net/core/dev.c:netdev_offload_xstats_push_delta
  - net/core/dev.c:netdev_offload_xstats_report_delta
Direct callers:
  - net/core/dev.c:netdev_offload_xstats_get_stats
```
**Symbols:**

```
ffffffff81ee9e70-ffffffff81ee9ecb: netdev_hw_stats64_add (STB_LOCAL)
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
