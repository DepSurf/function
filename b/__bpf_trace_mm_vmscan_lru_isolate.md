# Function: <code>__bpf_trace_mm_vmscan_lru_isolate</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81205ee0)
Location: include/trace/events/vmscan.h:278
Inline: False
```
**Symbols:**

```
ffffffff81205ee0-ffffffff81205efe: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812188b0)
Location: include/trace/events/vmscan.h:278
Inline: False
```
**Symbols:**

```
ffffffff812188b0-ffffffff812188ce: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81228390)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff81228390-ffffffff812283ae: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81236230)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff81236230-ffffffff8123624e: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int highest_zoneidx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812638c0)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff812638c0-ffffffff812638de: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int highest_zoneidx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126e250)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff8126e250-ffffffff8126e26e: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int highest_zoneidx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81272f50)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff81272f50-ffffffff81272f6e: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int highest_zoneidx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b0240)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff812b0240-ffffffff812b025e: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int highest_zoneidx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130b9d0)
Location: include/trace/events/vmscan.h:281
Inline: False
```
**Symbols:**

```
ffffffff8130b9d0-ffffffff8130ba02: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int highest_zoneidx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81375e70)
Location: include/trace/events/vmscan.h:281
Inline: False
```
**Symbols:**

```
ffffffff81375e70-ffffffff81375ea2: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int highest_zoneidx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813a8aa0)
Location: include/trace/events/vmscan.h:281
Inline: False
```
**Symbols:**

```
ffffffff813a8aa0-ffffffff813a8ad2: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int highest_zoneidx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d2530)
Location: include/trace/events/vmscan.h:281
Inline: False
```
**Symbols:**

```
ffffffff813d2530-ffffffff813d255c: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c6038)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffff8000102c6038-ffff8000102c6068: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f122c)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
c04f122c-c04f12a0: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000382150)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
c000000000382150-c00000000038218c: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e880)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff8122e880-ffffffff8122e89e: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81221940)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff81221940-ffffffff8122195e: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122c620)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff8122c620-ffffffff8122c63e: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_lru_isolate(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_skipped, long unsigned int nr_taken, isolate_mode_t isolate_mode, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123ba10)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff8123ba10-ffffffff8123ba2e: __bpf_trace_mm_vmscan_lru_isolate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
