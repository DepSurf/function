# Function: <code>__traceiter_mm_page_pcpu_drain</code>

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
int __traceiter_mm_page_pcpu_drain(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81286790)
Location: include/trace/events/kmem.h:255
Inline: False
```
**Symbols:**

```
ffffffff81286790-ffffffff812867e1: __traceiter_mm_page_pcpu_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mm_page_pcpu_drain(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128ba40)
Location: include/trace/events/kmem.h:263
Inline: False
```
**Symbols:**

```
ffffffff8128ba40-ffffffff8128ba8f: __traceiter_mm_page_pcpu_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mm_page_pcpu_drain(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cb800)
Location: include/trace/events/kmem.h:263
Inline: False
```
**Symbols:**

```
ffffffff812cb800-ffffffff812cb84f: __traceiter_mm_page_pcpu_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mm_page_pcpu_drain(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813292e0)
Location: include/trace/events/kmem.h:267
Inline: False
```
**Symbols:**

```
ffffffff813292e0-ffffffff8132933b: __traceiter_mm_page_pcpu_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mm_page_pcpu_drain(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8139e470)
Location: include/trace/events/kmem.h:243
Inline: False
```
**Symbols:**

```
ffffffff8139e470-ffffffff8139e4cb: __traceiter_mm_page_pcpu_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mm_page_pcpu_drain(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d16d0)
Location: include/trace/events/kmem.h:243
Inline: False
```
**Symbols:**

```
ffffffff813d16d0-ffffffff813d172b: __traceiter_mm_page_pcpu_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mm_page_pcpu_drain(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fc100)
Location: include/trace/events/kmem.h:243
Inline: False
```
**Symbols:**

```
ffffffff813fc100-ffffffff813fc15b: __traceiter_mm_page_pcpu_drain (STB_GLOBAL)
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
