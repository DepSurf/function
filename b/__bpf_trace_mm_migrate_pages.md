# Function: <code>__bpf_trace_mm_migrate_pages</code>

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
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126cce0)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff8126cce0-ffffffff8126ccf0: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81281460)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff81281460-ffffffff81281470: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129d760)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff8129d760-ffffffff8129d770: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812acf40)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff812acf40-ffffffff812acf50: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e1ff0)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff812e1ff0-ffffffff812e2000: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ecf50)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff812ecf50-ffffffff812ecf65: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f32a0)
Location: include/trace/events/migrate.h:47
Inline: False
```
**Symbols:**

```
ffffffff812f32a0-ffffffff812f32b5: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133d710)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff8133d710-ffffffff8133d725: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135af20)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff8135af20-ffffffff8135af49: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d5b30)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff813d5b30-ffffffff813d5b59: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140a9f0)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff8140a9f0-ffffffff8140aa19: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, long unsigned int large_folio_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81437250)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff81437250-ffffffff8143727e: __bpf_trace_mm_migrate_pages (STB_LOCAL)
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
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff80001034e800)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffff80001034e800-ffff80001034e81c: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0550dec)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
c0550dec-c0550e30: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0000000004311f0)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
c0000000004311f0-c000000000431220: __bpf_trace_mm_migrate_pages (STB_LOCAL)
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
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5520)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff812a5520-ffffffff812a5530: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81296ff0)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff81296ff0-ffffffff81297000: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a3330)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff812a3330-ffffffff812a3340: __bpf_trace_mm_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b35c0)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff812b35c0-ffffffff812b35d0: __bpf_trace_mm_migrate_pages (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int thp_succeeded</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int thp_failed</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int thp_split</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, succeeded, failed, mode, reason</code> ➡️ <code>__data, succeeded, failed, thp_succeeded, thp_failed, thp_split, mode, reason</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>long unsigned int large_folio_split</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, succeeded, failed, thp_succeeded, thp_failed, thp_split, mode, reason</code> ➡️ <code>__data, succeeded, failed, thp_succeeded, thp_failed, thp_split, large_folio_split, mode, reason</code>
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
