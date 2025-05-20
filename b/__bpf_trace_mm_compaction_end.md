# Function: <code>__bpf_trace_mm_compaction_end</code>

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
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81220290)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff81220290-ffffffff812202a4: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812332d0)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff812332d0-ffffffff812332e4: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812438a0)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff812438a0-ffffffff812438b4: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81251d60)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff81251d60-ffffffff81251d74: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81280490)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff81280490-ffffffff812804a4: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128a530)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff8128a530-ffffffff8128a544: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128fb80)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff8128fb80-ffffffff8128fb94: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812cf920)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff812cf920-ffffffff812cf934: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132e290)
Location: include/trace/events/compaction.h:120
Inline: False
```
**Symbols:**

```
ffffffff8132e290-ffffffff8132e2b4: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a4a40)
Location: include/trace/events/compaction.h:120
Inline: False
```
**Symbols:**

```
ffffffff813a4a40-ffffffff813a4a64: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d8230)
Location: include/trace/events/compaction.h:131
Inline: False
```
**Symbols:**

```
ffffffff813d8230-ffffffff813d8254: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, struct compact_control *cc, long unsigned int zone_start, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81401f10)
Location: include/trace/events/compaction.h:131
Inline: False
```
**Symbols:**

```
ffffffff81401f10-ffffffff81401f34: __bpf_trace_mm_compaction_end (STB_LOCAL)
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
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102e8778)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffff8000102e8778-ffff8000102e8794: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050d15c)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
c050d15c-c050d1b8: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003ab910)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
c0000000003ab910-c0000000003ab940: __bpf_trace_mm_compaction_end (STB_LOCAL)
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
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124a3b0)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff8124a3b0-ffffffff8124a3c4: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123d360)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff8123d360-ffffffff8123d374: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81248150)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff81248150-ffffffff81248164: __bpf_trace_mm_compaction_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_mm_compaction_end(void *__data, long unsigned int zone_start, long unsigned int migrate_pfn, long unsigned int free_pfn, long unsigned int zone_end, bool sync, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81257980)
Location: include/trace/events/compaction.h:136
Inline: False
```
**Symbols:**

```
ffffffff81257980-ffffffff81257994: __bpf_trace_mm_compaction_end (STB_LOCAL)
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
