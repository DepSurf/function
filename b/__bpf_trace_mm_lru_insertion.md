# Function: <code>__bpf_trace_mm_lru_insertion</code>

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
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81200ae0)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffffffff81200ae0-ffffffff81200aed: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81213450)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffffffff81213450-ffffffff8121345d: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81222d80)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffffffff81222d80-ffffffff81222d8d: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81230930)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffffffff81230930-ffffffff8123093d: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125daf0)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffffffff8125daf0-ffffffff8125dafd: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81267f30)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffffffff81267f30-ffffffff81267f3d: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126c970)
Location: include/trace/events/pagemap.h:28
Inline: True
```
**Symbols:**

```
ffffffff8126c970-ffffffff8126c97b: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812a9690)
Location: include/trace/events/pagemap.h:28
Inline: True
```
**Symbols:**

```
ffffffff812a9690-ffffffff812a969b: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81302cf0)
Location: include/trace/events/pagemap.h:28
Inline: True
```
**Symbols:**

```
ffffffff81302cf0-ffffffff81302d03: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136d1f0)
Location: include/trace/events/pagemap.h:28
Inline: True
```
**Symbols:**

```
ffffffff8136d1f0-ffffffff8136d203: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8139f470)
Location: include/trace/events/pagemap.h:28
Inline: True
```
**Symbols:**

```
ffffffff8139f470-ffffffff8139f483: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813c90d0)
Location: include/trace/events/pagemap.h:28
Inline: True
```
**Symbols:**

```
ffffffff813c90d0-ffffffff813c90e3: __bpf_trace_mm_lru_insertion (STB_LOCAL)
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
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c0058)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffff8000102c0058-ffff8000102c0070: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ebbbc)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
c04ebbbc-c04ebbe4: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c0000000003795c0)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
c0000000003795c0-c0000000003795f0: __bpf_trace_mm_lru_insertion (STB_LOCAL)
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
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228f80)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffffffff81228f80-ffffffff81228f8d: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121c0c0)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffffffff8121c0c0-ffffffff8121c0cd: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81226d20)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffffffff81226d20-ffffffff81226d2d: __bpf_trace_mm_lru_insertion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_mm_lru_insertion(void *__data, struct page *page, int lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81236050)
Location: include/trace/events/pagemap.h:28
Inline: False
```
**Symbols:**

```
ffffffff81236050-ffffffff8123605d: __bpf_trace_mm_lru_insertion (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int lru</code>
</li>
</ul>
</details>
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
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
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
