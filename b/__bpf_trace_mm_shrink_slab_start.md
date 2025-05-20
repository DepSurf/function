# Function: <code>__bpf_trace_mm_shrink_slab_start</code>

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
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81205e60)
Location: include/trace/events/vmscan.h:196
Inline: False
```
**Symbols:**

```
ffffffff81205e60-ffffffff81205e74: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81218830)
Location: include/trace/events/vmscan.h:196
Inline: False
```
**Symbols:**

```
ffffffff81218830-ffffffff81218844: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81228310)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff81228310-ffffffff81228324: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812361b0)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff812361b0-ffffffff812361c4: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81263840)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff81263840-ffffffff81263854: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126e1d0)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff8126e1d0-ffffffff8126e1e4: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81272ed0)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff81272ed0-ffffffff81272ee4: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b01c0)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff812b01c0-ffffffff812b01d4: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130b910)
Location: include/trace/events/vmscan.h:199
Inline: False
```
**Symbols:**

```
ffffffff8130b910-ffffffff8130b938: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81375d70)
Location: include/trace/events/vmscan.h:199
Inline: False
```
**Symbols:**

```
ffffffff81375d70-ffffffff81375d98: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813a89a0)
Location: include/trace/events/vmscan.h:199
Inline: False
```
**Symbols:**

```
ffffffff813a89a0-ffffffff813a89c8: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d24f0)
Location: include/trace/events/vmscan.h:199
Inline: False
```
**Symbols:**

```
ffffffff813d24f0-ffffffff813d2518: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
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
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c5fc0)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffff8000102c5fc0-ffff8000102c5fd8: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f10a8)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
c04f10a8-c04f110c: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000382060)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
c000000000382060-c000000000382090: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
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
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e800)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff8122e800-ffffffff8122e814: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812218c0)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff812218c0-ffffffff812218d4: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122c5a0)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff8122c5a0-ffffffff8122c5b4: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123b990)
Location: include/trace/events/vmscan.h:185
Inline: False
```
**Symbols:**

```
ffffffff8123b990-ffffffff8123b9a4: __bpf_trace_mm_shrink_slab_start (STB_LOCAL)
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
