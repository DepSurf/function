# Function: <code>__bpf_trace_mm_compaction_begin</code>

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
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81220280)
Location: include/trace/events/compaction.h:105
Inline: False
```
**Symbols:**

```
ffffffff81220280-ffffffff8122028f: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812332c0)
Location: include/trace/events/compaction.h:105
Inline: False
```
**Symbols:**

```
ffffffff812332c0-ffffffff812332cf: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81243890)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff81243890-ffffffff8124389f: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81251d50)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff81251d50-ffffffff81251d5f: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81280480)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff81280480-ffffffff8128048f: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128a520)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff8128a520-ffffffff8128a52f: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128fb70)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff8128fb70-ffffffff8128fb7f: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812cf910)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff812cf910-ffffffff812cf91f: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132e230)
Location: include/trace/events/compaction.h:90
Inline: False
```
**Symbols:**

```
ffffffff8132e230-ffffffff8132e24e: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a49b0)
Location: include/trace/events/compaction.h:90
Inline: False
```
**Symbols:**

```
ffffffff813a49b0-ffffffff813a49ce: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d81a0)
Location: include/trace/events/compaction.h:101
Inline: False
```
**Symbols:**

```
ffffffff813d81a0-ffffffff813d81be: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81401e80)
Location: include/trace/events/compaction.h:101
Inline: False
```
**Symbols:**

```
ffffffff81401e80-ffffffff81401e9e: __bpf_trace_mm_compaction_begin (STB_LOCAL)
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
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102e8760)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffff8000102e8760-ffff8000102e8778: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050d10c)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
c050d10c-c050d15c: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003ab8e0)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
c0000000003ab8e0-c0000000003ab90c: __bpf_trace_mm_compaction_begin (STB_LOCAL)
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
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124a3a0)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff8124a3a0-ffffffff8124a3af: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123d350)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff8123d350-ffffffff8123d35f: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81248140)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff81248140-ffffffff8124814f: __bpf_trace_mm_compaction_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_begin(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81257970)
Location: include/trace/events/compaction.h:106
Inline: False
```
**Symbols:**

```
ffffffff81257970-ffffffff8125797f: __bpf_trace_mm_compaction_begin (STB_LOCAL)
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
