# Function: <code>get_user_pages_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071bb0)
Location: arch/x86/mm/gup.c:323
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/trace/trace.c:tracing_mark_write
  - mm/madvise.c:SyS_madvise
  - fs/splice.c:vmsplice_to_pipe
  - block/bio.c:bio_map_user_iov
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
**Symbols:**

```
ffffffff81071bb0-ffffffff81071d38: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071e80)
Location: arch/x86/mm/gup.c:370
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/trace/trace.c:tracing_mark_write
  - mm/madvise.c:SyS_madvise
  - fs/splice.c:vmsplice_to_pipe
  - block/bio.c:bio_map_user_iov
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff81071e80-ffffffff81071ffb: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff810759f0)
Location: arch/x86/mm/gup.c:374
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:SyS_madvise
  - block/bio.c:bio_map_user_iov
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff810759f0-ffffffff81075b6c: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd780)
Location: mm/util.c:312
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:SyS_madvise
  - block/bio.c:bio_map_user_iov
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff811f1240-ffffffff811f12fd: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3200)
Location: mm/util.c:312
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:SyS_madvise
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff81207e70-ffffffff81207f6d: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214440)
Location: mm/util.c:336
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:madvise_inject_error
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff81228be0-ffffffff81228ce6: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, int write, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227310)
Location: mm/util.c:329
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:madvise_inject_error
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff8123c480-ffffffff8123c586: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124db00)
Location: mm/gup.c:2403
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:__do_sys_madvise
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff8124db00-ffffffff8124dc8e: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125c030)
Location: mm/gup.c:2419
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:__do_sys_madvise
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff8125c030-ffffffff8125c1be: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128b560)
Location: mm/gup.c:2884
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:madvise_inject_error
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff8128b560-ffffffff8128b583: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812953c0)
Location: mm/gup.c:2677
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff812953c0-ffffffff812953f6: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129ad30)
Location: mm/gup.c:2743
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff8129ad30-ffffffff8129ad66: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812db700)
Location: mm/gup.c:2838
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff812db700-ffffffff812db736: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133b400)
Location: mm/gup.c:2988
Inline: False
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - mm/madvise.c:madvise_inject_error
  - mm/mempolicy.c:do_get_mempolicy
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff8133b400-ffffffff8133b45a: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b2f60)
Location: mm/gup.c:3014
Inline: False
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - mm/madvise.c:madvise_inject_error
  - mm/mempolicy.c:do_get_mempolicy
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
```
**Symbols:**

```
ffffffff813b2f60-ffffffff813b2fba: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e7c80)
Location: mm/gup.c:3264
Inline: False
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - mm/madvise.c:do_madvise
  - mm/mempolicy.c:do_get_mempolicy
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
```
**Symbols:**

```
ffffffff813e7c80-ffffffff813e7cff: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff814128f0)
Location: mm/gup.c:3282
Inline: False
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - mm/madvise.c:do_madvise
  - mm/mempolicy.c:do_get_mempolicy
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
```
**Symbols:**

```
ffffffff814128f0-ffffffff8141296d: get_user_pages_fast (STB_GLOBAL)
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f3428)
Location: mm/gup.c:2419
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:__arm64_sys_madvise
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffff8000102f3428-ffff8000102f35e4: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0515778)
Location: mm/gup.c:2419
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
c0515778-c05158d8: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b9f70)
Location: mm/gup.c:2419
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:__se_sys_madvise
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
c0000000003b9f70-c0000000003ba17c: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe0002056aa)
Location: mm/gup.c:2419
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffe0002056aa-ffffffe000205776: get_user_pages_fast (STB_GLOBAL)
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
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81254680)
Location: mm/gup.c:2419
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:__do_sys_madvise
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff81254680-ffffffff8125480e: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812472d0)
Location: mm/gup.c:2419
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:__do_sys_madvise
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff812472d0-ffffffff81247452: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81252420)
Location: mm/gup.c:2419
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:__do_sys_madvise
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff81252420-ffffffff812525ae: get_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81261dd0)
Location: mm/gup.c:2419
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - mm/madvise.c:__do_sys_madvise
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff81261dd0-ffffffff81261f5e: get_user_pages_fast (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
</ul>
</details>
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
