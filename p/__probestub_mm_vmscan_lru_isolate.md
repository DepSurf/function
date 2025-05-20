# Function: <code>__probestub_mm_vmscan_lru_isolate</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __probestub_mm_vmscan_lru_isolate(void *__data, int highest_zoneidx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813a54c0)
Location: include/trace/events/vmscan.h:281
Inline: False
```
**Symbols:**

```
ffffffff813a54c0-ffffffff813a54cf: __probestub_mm_vmscan_lru_isolate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __probestub_mm_vmscan_lru_isolate(void *__data, int highest_zoneidx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, int lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813cf040)
Location: include/trace/events/vmscan.h:281
Inline: False
```
**Symbols:**

```
ffffffff813cf040-ffffffff813cf04f: __probestub_mm_vmscan_lru_isolate (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>isolate_mode_t isolate_mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, highest_zoneidx, order, nr_requested, nr_scanned, nr_skipped, nr_taken, isolate_mode, lru</code> ➡️ <code>__data, highest_zoneidx, order, nr_requested, nr_scanned, nr_skipped, nr_taken, lru</code>
</li>
</ul>
</details>
</li>
</ul>
