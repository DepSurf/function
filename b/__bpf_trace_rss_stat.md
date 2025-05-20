# Function: <code>__bpf_trace_rss_stat</code>

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
void __bpf_trace_rss_stat(void *__data, struct mm_struct *mm, int member, long int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127cb20)
Location: include/trace/events/kmem.h:338
Inline: False
```
**Symbols:**

```
ffffffff8127cb20-ffffffff8127cb2d: __bpf_trace_rss_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_rss_stat(void *__data, struct mm_struct *mm, int member, long int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81287880)
Location: include/trace/events/kmem.h:338
Inline: False
```
**Symbols:**

```
ffffffff81287880-ffffffff8128788d: __bpf_trace_rss_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_rss_stat(void *__data, struct mm_struct *mm, int member, long int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128ca30)
Location: include/trace/events/kmem.h:366
Inline: False
```
**Symbols:**

```
ffffffff8128ca30-ffffffff8128ca3d: __bpf_trace_rss_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_rss_stat(void *__data, struct mm_struct *mm, int member, long int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cc7f0)
Location: include/trace/events/kmem.h:366
Inline: False
```
**Symbols:**

```
ffffffff812cc7f0-ffffffff812cc7fd: __bpf_trace_rss_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_rss_stat(void *__data, struct mm_struct *mm, int member, long int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132af10)
Location: include/trace/events/kmem.h:370
Inline: False
```
**Symbols:**

```
ffffffff8132af10-ffffffff8132af29: __bpf_trace_rss_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_rss_stat(void *__data, struct mm_struct *mm, int member);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a02b0)
Location: include/trace/events/kmem.h:346
Inline: False
```
**Symbols:**

```
ffffffff813a02b0-ffffffff813a02c7: __bpf_trace_rss_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_rss_stat(void *__data, struct mm_struct *mm, int member);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d3570)
Location: include/trace/events/kmem.h:346
Inline: False
```
**Symbols:**

```
ffffffff813d3570-ffffffff813d3587: __bpf_trace_rss_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_rss_stat(void *__data, struct mm_struct *mm, int member);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fdf70)
Location: include/trace/events/kmem.h:346
Inline: False
```
**Symbols:**

```
ffffffff813fdf70-ffffffff813fdf87: __bpf_trace_rss_stat (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long int count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
