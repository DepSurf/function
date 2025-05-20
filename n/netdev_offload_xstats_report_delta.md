# Function: <code>netdev_offload_xstats_report_delta</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void netdev_offload_xstats_report_delta(struct netdev_notifier_offload_xstats_rd *report_delta, const struct rtnl_hw_stats64 *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c11b50)
Location: net/core/dev.c:8098
Inline: False
```
**Symbols:**

```
ffffffff81c11b50-ffffffff81c11baf: netdev_offload_xstats_report_delta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netdev_offload_xstats_report_delta(struct netdev_notifier_offload_xstats_rd *report_delta, const struct rtnl_hw_stats64 *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc1d10)
Location: net/core/dev.c:8084
Inline: False
```
**Symbols:**

```
ffffffff81dc1d10-ffffffff81dc1d6f: netdev_offload_xstats_report_delta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netdev_offload_xstats_report_delta(struct netdev_notifier_offload_xstats_rd *report_delta, const struct rtnl_hw_stats64 *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e31aa0)
Location: net/core/dev.c:8089
Inline: False
```
**Symbols:**

```
ffffffff81e31aa0-ffffffff81e31aff: netdev_offload_xstats_report_delta (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netdev_offload_xstats_report_delta(struct netdev_notifier_offload_xstats_rd *report_delta, const struct rtnl_hw_stats64 *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eefa60)
Location: net/core/dev.c:8207
Inline: False
```
**Symbols:**

```
ffffffff81eefa60-ffffffff81eefabf: netdev_offload_xstats_report_delta (STB_GLOBAL)
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
