# Function: <code>__traceiter_mm_compaction_finished</code>

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
int __traceiter_mm_compaction_finished(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812891f0)
Location: include/trace/events/compaction.h:226
Inline: False
```
**Symbols:**

```
ffffffff812891f0-ffffffff81289241: __traceiter_mm_compaction_finished (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mm_compaction_finished(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128e880)
Location: include/trace/events/compaction.h:226
Inline: False
```
**Symbols:**

```
ffffffff8128e880-ffffffff8128e8cf: __traceiter_mm_compaction_finished (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mm_compaction_finished(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812ce7c0)
Location: include/trace/events/compaction.h:226
Inline: False
```
**Symbols:**

```
ffffffff812ce7c0-ffffffff812ce80f: __traceiter_mm_compaction_finished (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mm_compaction_finished(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132c8a0)
Location: include/trace/events/compaction.h:210
Inline: False
```
**Symbols:**

```
ffffffff8132c8a0-ffffffff8132c8fb: __traceiter_mm_compaction_finished (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mm_compaction_finished(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a2da0)
Location: include/trace/events/compaction.h:210
Inline: False
```
**Symbols:**

```
ffffffff813a2da0-ffffffff813a2dfb: __traceiter_mm_compaction_finished (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mm_compaction_finished(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d6310)
Location: include/trace/events/compaction.h:221
Inline: False
```
**Symbols:**

```
ffffffff813d6310-ffffffff813d636b: __traceiter_mm_compaction_finished (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mm_compaction_finished(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813fffe0)
Location: include/trace/events/compaction.h:221
Inline: False
```
**Symbols:**

```
ffffffff813fffe0-ffffffff8140003b: __traceiter_mm_compaction_finished (STB_GLOBAL)
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
