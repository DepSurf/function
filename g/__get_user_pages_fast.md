# Function: <code>__get_user_pages_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071a80)
Location: arch/x86/mm/gup.c:255
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
```
**Symbols:**

```
ffffffff81071a80-ffffffff81071baa: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071d50)
Location: arch/x86/mm/gup.c:302
Inline: False
```
**Symbols:**

```
ffffffff81071d50-ffffffff81071e71: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff810758c0)
Location: arch/x86/mm/gup.c:306
Inline: False
```
**Symbols:**

```
ffffffff810758c0-ffffffff810759e1: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd440)
Location: mm/util.c:281
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff811f0800-ffffffff811f1239: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f2ec0)
Location: mm/util.c:281
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81207dc0-ffffffff81207e68: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214100)
Location: mm/util.c:305
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81228b30-ffffffff81228bd3: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81226fd0)
Location: mm/util.c:298
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8123c3d0-ffffffff8123c473: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124b810)
Location: mm/gup.c:2325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8124b810-ffffffff8124b8bf: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81259d00)
Location: mm/gup.c:2341
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81259d00-ffffffff81259daf: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f17b8)
Location: mm/gup.c:2341
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:gfn_to_page_many_atomic
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffff8000102f17b8-ffff8000102f18d0: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0513f54)
Location: mm/gup.c:2341
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
c0513f54-c0513f70: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b7910)
Location: mm/gup.c:2341
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
c0000000003b7910-c0000000003b7a04: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000204234)
Location: mm/gup.c:2341
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffe000204234-ffffffe000204250: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81252350)
Location: mm/gup.c:2341
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81252350-ffffffff812523ff: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81245120)
Location: mm/gup.c:2341
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81245120-ffffffff812451b9: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812500f0)
Location: mm/gup.c:2341
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff812500f0-ffffffff8125019f: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125fa80)
Location: mm/gup.c:2341
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8125fa80-ffffffff8125fb2f: __get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
