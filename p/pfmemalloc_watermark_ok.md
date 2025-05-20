# Function: <code>pfmemalloc_watermark_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pfmemalloc_watermark_ok(pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a03b0)
Location: mm/vmscan.c:2699
Inline: False
Direct callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811a03b0-ffffffff811a04ad: pfmemalloc_watermark_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pfmemalloc_watermark_ok(pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b82e0)
Location: mm/vmscan.c:2814
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
**Symbols:**

```
ffffffff811b82e0-ffffffff811b83ce: pfmemalloc_watermark_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pfmemalloc_watermark_ok(pg_data_t *pgdat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c8920)
Location: mm/vmscan.c:2823
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
**Symbols:**

```
ffffffff811c8920-ffffffff811c8a0e: pfmemalloc_watermark_ok (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
