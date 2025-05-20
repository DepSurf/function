# Function: <code>__bpf_trace_mm_page</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121d2b0)
Location: include/trace/events/kmem.h:221
Inline: True
```
**Symbols:**

```
ffffffff8121d2b0-ffffffff8121d2bf: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812302a0)
Location: include/trace/events/kmem.h:221
Inline: True
```
**Symbols:**

```
ffffffff812302a0-ffffffff812302af: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812402e0)
Location: include/trace/events/kmem.h:221
Inline: False
```
**Symbols:**

```
ffffffff812402e0-ffffffff812402ef: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124e6f0)
Location: include/trace/events/kmem.h:222
Inline: False
```
**Symbols:**

```
ffffffff8124e6f0-ffffffff8124e6ff: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127cb10)
Location: include/trace/events/kmem.h:222
Inline: True
```
**Symbols:**

```
ffffffff8127cb10-ffffffff8127cb1f: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81287870)
Location: include/trace/events/kmem.h:222
Inline: True
```
**Symbols:**

```
ffffffff81287870-ffffffff8128787f: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128ca20)
Location: include/trace/events/kmem.h:230
Inline: True
```
**Symbols:**

```
ffffffff8128ca20-ffffffff8128ca2f: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cc7e0)
Location: include/trace/events/kmem.h:230
Inline: True
```
**Symbols:**

```
ffffffff812cc7e0-ffffffff812cc7ef: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype, int percpu_refill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132af80)
Location: include/trace/events/kmem.h:230
Inline: False
```
**Symbols:**

```
ffffffff8132af80-ffffffff8132afa1: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype, int percpu_refill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a03b0)
Location: include/trace/events/kmem.h:206
Inline: False
```
**Symbols:**

```
ffffffff813a03b0-ffffffff813a03d1: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype, int percpu_refill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d3670)
Location: include/trace/events/kmem.h:206
Inline: False
```
**Symbols:**

```
ffffffff813d3670-ffffffff813d3691: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype, int percpu_refill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fe070)
Location: include/trace/events/kmem.h:206
Inline: False
```
**Symbols:**

```
ffffffff813fe070-ffffffff813fe091: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e4a28)
Location: include/trace/events/kmem.h:222
Inline: True
```
**Symbols:**

```
ffff8000102e4a28-ffff8000102e4a44: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c05096a0)
Location: include/trace/events/kmem.h:222
Inline: False
```
**Symbols:**

```
c05096a0-c05096d8: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a6280)
Location: include/trace/events/kmem.h:222
Inline: False
```
**Symbols:**

```
c0000000003a6280-c0000000003a62b0: __bpf_trace_mm_page (STB_LOCAL)
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
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81246d40)
Location: include/trace/events/kmem.h:222
Inline: False
```
**Symbols:**

```
ffffffff81246d40-ffffffff81246d4f: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81239cf0)
Location: include/trace/events/kmem.h:222
Inline: False
```
**Symbols:**

```
ffffffff81239cf0-ffffffff81239cff: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81244ae0)
Location: include/trace/events/kmem.h:222
Inline: False
```
**Symbols:**

```
ffffffff81244ae0-ffffffff81244aef: __bpf_trace_mm_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_mm_page(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812542a0)
Location: include/trace/events/kmem.h:222
Inline: False
```
**Symbols:**

```
ffffffff812542a0-ffffffff812542af: __bpf_trace_mm_page (STB_LOCAL)
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
<code>int percpu_refill</code>
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
