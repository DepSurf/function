# Function: <code>__traceiter_mm_compaction_migratepages</code>

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
int __traceiter_mm_compaction_migratepages(void *__data, long unsigned int nr_all, int migrate_rc, struct list_head *migratepages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81289040)
Location: include/trace/events/compaction.h:68
Inline: False
```
**Symbols:**

```
ffffffff81289040-ffffffff81289091: __traceiter_mm_compaction_migratepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mm_compaction_migratepages(void *__data, long unsigned int nr_all, int migrate_rc, struct list_head *migratepages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128e700)
Location: include/trace/events/compaction.h:68
Inline: False
```
**Symbols:**

```
ffffffff8128e700-ffffffff8128e74f: __traceiter_mm_compaction_migratepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mm_compaction_migratepages(void *__data, long unsigned int nr_all, int migrate_rc, struct list_head *migratepages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812ce640)
Location: include/trace/events/compaction.h:68
Inline: False
```
**Symbols:**

```
ffffffff812ce640-ffffffff812ce68f: __traceiter_mm_compaction_migratepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mm_compaction_migratepages(void *__data, struct compact_control *cc, unsigned int nr_succeeded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132c6f0)
Location: include/trace/events/compaction.h:68
Inline: False
```
**Symbols:**

```
ffffffff8132c6f0-ffffffff8132c73f: __traceiter_mm_compaction_migratepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mm_compaction_migratepages(void *__data, struct compact_control *cc, unsigned int nr_succeeded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a2bb0)
Location: include/trace/events/compaction.h:68
Inline: False
```
**Symbols:**

```
ffffffff813a2bb0-ffffffff813a2bff: __traceiter_mm_compaction_migratepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mm_compaction_migratepages(void *__data, struct compact_control *cc, unsigned int nr_succeeded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d60a0)
Location: include/trace/events/compaction.h:79
Inline: False
```
**Symbols:**

```
ffffffff813d60a0-ffffffff813d60ef: __traceiter_mm_compaction_migratepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mm_compaction_migratepages(void *__data, struct compact_control *cc, unsigned int nr_succeeded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813ffd70)
Location: include/trace/events/compaction.h:79
Inline: False
```
**Symbols:**

```
ffffffff813ffd70-ffffffff813ffdbf: __traceiter_mm_compaction_migratepages (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int nr_succeeded</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_all</code>
</li>
<li>
<b>Param removed. </b>
<code>int migrate_rc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct list_head *migratepages</code>
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
