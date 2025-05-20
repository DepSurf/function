# Function: <code>__traceiter_mm_compaction_begin</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812890a0)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff812890a0-ffffffff8128910f: __traceiter_mm_compaction_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128e750)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff8128e750-ffffffff8128e7bd: __traceiter_mm_compaction_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812ce690)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff812ce690-ffffffff812ce6fd: __traceiter_mm_compaction_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mm_compaction_begin(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132c740)
Location: include/trace/events/compaction.h:90
Inline: False
```
**Symbols:**

```
ffffffff8132c740-ffffffff8132c7a9: __traceiter_mm_compaction_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mm_compaction_begin(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a2c10)
Location: include/trace/events/compaction.h:90
Inline: False
```
**Symbols:**

```
ffffffff813a2c10-ffffffff813a2c79: __traceiter_mm_compaction_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mm_compaction_begin(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d6120)
Location: include/trace/events/compaction.h:101
Inline: False
```
**Symbols:**

```
ffffffff813d6120-ffffffff813d6189: __traceiter_mm_compaction_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mm_compaction_begin(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813ffdf0)
Location: include/trace/events/compaction.h:101
Inline: False
```
**Symbols:**

```
ffffffff813ffdf0-ffffffff813ffe59: __traceiter_mm_compaction_begin (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct compact_control *cc</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int migrate_pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int free_pfn</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, zone_start, migrate_pfn, free_pfn, zone_end, sync</code> ➡️ <code>__data, cc, zone_start, zone_end, sync</code>
</li>
</ul>
</details>
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
