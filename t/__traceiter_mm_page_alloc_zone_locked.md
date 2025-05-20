# Function: <code>__traceiter_mm_page_alloc_zone_locked</code>

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
int __traceiter_mm_page_alloc_zone_locked(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81286730)
Location: include/trace/events/kmem.h:248
Inline: False
```
**Symbols:**

```
ffffffff81286730-ffffffff81286781: __traceiter_mm_page_alloc_zone_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mm_page_alloc_zone_locked(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128b9f0)
Location: include/trace/events/kmem.h:256
Inline: False
```
**Symbols:**

```
ffffffff8128b9f0-ffffffff8128ba3f: __traceiter_mm_page_alloc_zone_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mm_page_alloc_zone_locked(void *__data, struct page *page, unsigned int order, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cb7b0)
Location: include/trace/events/kmem.h:256
Inline: False
```
**Symbols:**

```
ffffffff812cb7b0-ffffffff812cb7ff: __traceiter_mm_page_alloc_zone_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mm_page_alloc_zone_locked(void *__data, struct page *page, unsigned int order, int migratetype, int percpu_refill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81329270)
Location: include/trace/events/kmem.h:259
Inline: False
```
**Symbols:**

```
ffffffff81329270-ffffffff813292d8: __traceiter_mm_page_alloc_zone_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mm_page_alloc_zone_locked(void *__data, struct page *page, unsigned int order, int migratetype, int percpu_refill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8139e3f0)
Location: include/trace/events/kmem.h:235
Inline: False
```
**Symbols:**

```
ffffffff8139e3f0-ffffffff8139e458: __traceiter_mm_page_alloc_zone_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mm_page_alloc_zone_locked(void *__data, struct page *page, unsigned int order, int migratetype, int percpu_refill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d1630)
Location: include/trace/events/kmem.h:235
Inline: False
```
**Symbols:**

```
ffffffff813d1630-ffffffff813d1698: __traceiter_mm_page_alloc_zone_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mm_page_alloc_zone_locked(void *__data, struct page *page, unsigned int order, int migratetype, int percpu_refill);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fc060)
Location: include/trace/events/kmem.h:235
Inline: False
```
**Symbols:**

```
ffffffff813fc060-ffffffff813fc0c8: __traceiter_mm_page_alloc_zone_locked (STB_GLOBAL)
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
