# Function: <code>ptr_to_hashval</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptr_to_hashval(const void *ptr, long unsigned int *hashval_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f98c0)
Location: lib/vsprintf.c:786
Inline: False
Direct callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
**Symbols:**

```
ffffffff815f98c0-ffffffff815f98ec: ptr_to_hashval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptr_to_hashval(const void *ptr, long unsigned int *hashval_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161df80)
Location: lib/vsprintf.c:789
Inline: False
Direct callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
**Symbols:**

```
ffffffff8161df80-ffffffff8161dfac: ptr_to_hashval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptr_to_hashval(const void *ptr, long unsigned int *hashval_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff816018d0)
Location: lib/vsprintf.c:815
Inline: False
Direct callers:
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
**Symbols:**

```
ffffffff816018d0-ffffffff816018fc: ptr_to_hashval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptr_to_hashval(const void *ptr, long unsigned int *hashval_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166f860)
Location: lib/vsprintf.c:816
Inline: False
Direct callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
**Symbols:**

```
ffffffff8166f860-ffffffff8166f889: ptr_to_hashval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptr_to_hashval(const void *ptr, long unsigned int *hashval_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81789c00)
Location: lib/vsprintf.c:799
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
**Symbols:**

```
ffffffff81789c00-ffffffff81789c13: ptr_to_hashval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ptr_to_hashval(const void *ptr, long unsigned int *hashval_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:800
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
**Symbols:**

```
ffffffff820b7c08-ffffffff820b7c1d: ptr_to_hashval.cold (STB_LOCAL)
ffffffff82046fb0-ffffffff82047003: ptr_to_hashval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ptr_to_hashval(const void *ptr, long unsigned int *hashval_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:800
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
**Symbols:**

```
ffffffff82139079-ffffffff8213908e: ptr_to_hashval.cold (STB_LOCAL)
ffffffff820c5640-ffffffff820c5693: ptr_to_hashval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ptr_to_hashval(const void *ptr, long unsigned int *hashval_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:802
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - mm/slab_common.c:perf_trace_rss_stat
  - mm/slab_common.c:trace_event_raw_event_rss_stat
```
**Symbols:**

```
ffffffff8221ae1e-ffffffff8221ae33: ptr_to_hashval.cold (STB_LOCAL)
ffffffff8219ffc0-ffffffff821a0013: ptr_to_hashval (STB_GLOBAL)
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
