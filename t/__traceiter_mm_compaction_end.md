# Function: <code>__traceiter_mm_compaction_end</code>

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
int __traceiter_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81289110)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff81289110-ffffffff81289181: __traceiter_mm_compaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128e7c0)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff8128e7c0-ffffffff8128e82f: __traceiter_mm_compaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812ce700)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff812ce700-ffffffff812ce76f: __traceiter_mm_compaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mm_compaction_end(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132c7b0)
Location: include/trace/events/compaction.h:120
Inline: False
```
**Symbols:**

```
ffffffff8132c7b0-ffffffff8132c832: __traceiter_mm_compaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mm_compaction_end(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a2c90)
Location: include/trace/events/compaction.h:120
Inline: False
```
**Symbols:**

```
ffffffff813a2c90-ffffffff813a2d12: __traceiter_mm_compaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mm_compaction_end(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d61c0)
Location: include/trace/events/compaction.h:131
Inline: False
```
**Symbols:**

```
ffffffff813d61c0-ffffffff813d6242: __traceiter_mm_compaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mm_compaction_end(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813ffe90)
Location: include/trace/events/compaction.h:131
Inline: False
```
**Symbols:**

```
ffffffff813ffe90-ffffffff813fff12: __traceiter_mm_compaction_end (STB_GLOBAL)
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
<code>__data, zone_start, migrate_pfn, free_pfn, zone_end, sync, status</code> ➡️ <code>__data, cc, zone_start, zone_end, sync, status</code>
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
