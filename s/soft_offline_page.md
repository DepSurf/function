# Function: <code>soft_offline_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81202f50)
Location: mm/memory-failure.c:1741
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_soft_offline_page
```
**Symbols:**

```
ffffffff81202f50-ffffffff81203489: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81227ab0)
Location: mm/memory-failure.c:1754
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_soft_offline_page
```
**Symbols:**

```
ffffffff81227ab0-ffffffff81228219: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8123a040)
Location: mm/memory-failure.c:1750
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_soft_offline_page
```
**Symbols:**

```
ffffffff8123a040-ffffffff8123a7d9: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81245c30)
Location: mm/memory-failure.c:1745
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_soft_offline_page
```
**Symbols:**

```
ffffffff81245c30-ffffffff812462a3: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81265c50)
Location: mm/memory-failure.c:1743
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_soft_offline_page
```
**Symbols:**

```
ffffffff81265c50-ffffffff812663ed: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1869
Inline: False
Direct callers:
  - mm/madvise.c:madvise_inject_error
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_soft_offline_page
```
**Symbols:**

```
ffffffff8128ac12-ffffffff8128ad3f: soft_offline_page.cold.44 (STB_LOCAL)
ffffffff81289ff0-ffffffff8128a728: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1896
Inline: False
Direct callers:
  - mm/madvise.c:madvise_inject_error
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff8129fb7c-ffffffff8129fc88: soft_offline_page.cold.45 (STB_LOCAL)
ffffffff8129ef60-ffffffff8129f68a: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1888
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff812baed3-ffffffff812baeff: soft_offline_page.cold (STB_LOCAL)
ffffffff812ba650-ffffffff812ba8b4: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1894
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff812ccdab-ffffffff812ccdd7: soft_offline_page.cold (STB_LOCAL)
ffffffff812cc530-ffffffff812cc794: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1930
Inline: False
Direct callers:
  - mm/madvise.c:madvise_inject_error
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff81303001-ffffffff8130302d: soft_offline_page.cold (STB_LOCAL)
ffffffff813027d0-ffffffff81302983: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1922
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff81bea2ca-ffffffff81bea31b: soft_offline_page.cold (STB_LOCAL)
ffffffff8130eac0-ffffffff8130ee25: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:2013
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff81bdc2e3-ffffffff81bdc352: soft_offline_page.cold (STB_LOCAL)
ffffffff81314fb0-ffffffff81315187: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:2168
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff81cc3391-ffffffff81cc33de: soft_offline_page.cold (STB_LOCAL)
ffffffff81361030-ffffffff8136121d: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:2324
Inline: False
Direct callers:
  - mm/madvise.c:madvise_inject_error
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff81e75961-ffffffff81e759b0: soft_offline_page.cold (STB_LOCAL)
ffffffff813dd160-ffffffff813dd63a: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int soft_offline_page(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81463f30)
Location: mm/memory-failure.c:2568
Inline: False
Direct callers:
  - mm/madvise.c:madvise_inject_error
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff81463f30-ffffffff814642a0: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int soft_offline_page(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814999f0)
Location: mm/memory-failure.c:2701
Inline: False
Direct callers:
  - mm/madvise.c:do_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff814999f0-ffffffff81499d80: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int soft_offline_page(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c9190)
Location: mm/memory-failure.c:2752
Inline: False
Direct callers:
  - mm/madvise.c:do_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff814c9190-ffffffff814c94f7: soft_offline_page (STB_GLOBAL)
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
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffff8000103700d8)
Location: mm/memory-failure.c:1894
Inline: False
Direct callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffff8000103700d8-ffff8000103708c0: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c000000000461c40)
Location: mm/memory-failure.c:1894
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
c000000000461c40-c000000000462040: soft_offline_page (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1894
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff812c538b-ffffffff812c53b7: soft_offline_page.cold (STB_LOCAL)
ffffffff812c4b10-ffffffff812c4d74: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1894
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff812b63cb-ffffffff812b63f7: soft_offline_page.cold (STB_LOCAL)
ffffffff812b5b50-ffffffff812b5db4: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1894
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff812c319b-ffffffff812c31c7: soft_offline_page.cold (STB_LOCAL)
ffffffff812c2920-ffffffff812c2b84: soft_offline_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int soft_offline_page(struct page *page, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1894
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:soft_offline_page_store
```
**Symbols:**

```
ffffffff812d3c3b-ffffffff812d3c67: soft_offline_page.cold (STB_LOCAL)
ffffffff812d33c0-ffffffff812d3624: soft_offline_page (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
