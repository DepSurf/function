# Function: <code>perf_trace_mm_shrink_slab_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int pgs_scanned, long unsigned int lru_pgs, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8119f8e0)
Location: include/trace/events/vmscan.h:182
Inline: False
```
**Symbols:**

```
ffffffff8119f8e0-ffffffff8119fa39: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int pgs_scanned, long unsigned int lru_pgs, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b5bd0)
Location: include/trace/events/vmscan.h:187
Inline: False
```
**Symbols:**

```
ffffffff811b5bd0-ffffffff811b5d12: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int pgs_scanned, long unsigned int lru_pgs, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c61f0)
Location: include/trace/events/vmscan.h:187
Inline: False
```
**Symbols:**

```
ffffffff811c61f0-ffffffff811c6330: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int pgs_scanned, long unsigned int lru_pgs, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811ce4b0)
Location: include/trace/events/vmscan.h:188
Inline: False
```
**Symbols:**

```
ffffffff811ce4b0-ffffffff811ce5ee: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int pgs_scanned, long unsigned int lru_pgs, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e38f0)
Location: include/trace/events/vmscan.h:193
Inline: False
```
**Symbols:**

```
ffffffff811e38f0-ffffffff811e3a23: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81204f40)
Location: include/trace/events/vmscan.h:196
Inline: False
```
**Symbols:**

```
ffffffff81204f40-ffffffff8120506b: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81217910)
Location: include/trace/events/vmscan.h:196
Inline: False
```
**Symbols:**

```
ffffffff81217910-ffffffff81217a3b: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81227270)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff81227270-ffffffff8122738b: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81235110)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff81235110-ffffffff8123522b: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81262770)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff81262770-ffffffff81262891: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126d100)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff8126d100-ffffffff8126d221: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81271e40)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff81271e40-ffffffff81271f61: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812af340)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff812af340-ffffffff812af461: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81309b90)
Location: include/trace/events/vmscan.h:199
Inline: False
```
**Symbols:**

```
ffffffff81309b90-ffffffff81309cd7: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81373cd0)
Location: include/trace/events/vmscan.h:199
Inline: False
```
**Symbols:**

```
ffffffff81373cd0-ffffffff81373e14: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813a6970)
Location: include/trace/events/vmscan.h:199
Inline: False
```
**Symbols:**

```
ffffffff813a6970-ffffffff813a6ab4: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d04e0)
Location: include/trace/events/vmscan.h:199
Inline: False
```
**Symbols:**

```
ffffffff813d04e0-ffffffff813d0624: perf_trace_mm_shrink_slab_start (STB_LOCAL)
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
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c7868)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffff8000102c7868-ffff8000102c7980: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04efeb0)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
c04efeb0-c04effd4: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000380340)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
c000000000380340-c0000000003804f0: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e5aaa)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffe0001e5aaa-ffffffe0001e5b6c: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122d760)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff8122d760-ffffffff8122d87b: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81220820)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff81220820-ffffffff8122093b: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122b500)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff8122b500-ffffffff8122b61b: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123a8f0)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff8123a8f0-ffffffff8123aa0b: perf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int priority</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int pgs_scanned</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int lru_pgs</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, shr, sc, nr_objects_to_shrink, pgs_scanned, lru_pgs, cache_items, delta, total_scan</code> ➡️ <code>__data, shr, sc, nr_objects_to_shrink, cache_items, delta, total_scan, priority</code>
</li>
</ul>
</details>
</li>
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
