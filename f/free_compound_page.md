# Function: <code>free_compound_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81194450)
Location: mm/page_alloc.c:460
Inline: False
```
**Symbols:**

```
ffffffff81194450-ffffffff8119446d: free_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a77e0)
Location: mm/page_alloc.c:567
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff811a77e0-ffffffff811a77fd: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b7bd0)
Location: mm/page_alloc.c:572
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff811b7bd0-ffffffff811b7bed: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bfa10)
Location: mm/page_alloc.c:588
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff811bfa10-ffffffff811bfa2d: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d4540)
Location: mm/page_alloc.c:603
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff811d4540-ffffffff811d455d: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f5f60)
Location: mm/page_alloc.c:564
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff811f5f60-ffffffff811f5f7e: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81207c00)
Location: mm/page_alloc.c:609
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff81207c00-ffffffff81207c20: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126df20)
Location: mm/page_alloc.c:671
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
  - fs/io_uring.c:io_mem_free
```
**Symbols:**

```
ffffffff8126df20-ffffffff8126df40: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127cd40)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
  - fs/io_uring.c:io_mem_free
```
**Symbols:**

```
ffffffff8127cd40-ffffffff8127cd72: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812af090)
Location: mm/page_alloc.c:652
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff812af090-ffffffff812af0c4: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bad00)
Location: mm/page_alloc.c:652
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff812bad00-ffffffff812bad36: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bfe50)
Location: mm/page_alloc.c:674
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff812bfe50-ffffffff812bfe86: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813056d0)
Location: mm/page_alloc.c:725
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff813056d0-ffffffff81305720: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136d9c0)
Location: mm/page_alloc.c:713
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff8136d9c0-ffffffff8136da95: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e9e40)
Location: mm/page_alloc.c:770
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff813e9e40-ffffffff813e9f15: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141ee70)
Location: mm/page_alloc.c:604
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
```
**Symbols:**

```
ffffffff8141ee70-ffffffff8141ef15: free_compound_page (STB_GLOBAL)
```
</details>
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
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103148d0)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
  - fs/io_uring.c:io_mem_free
```
**Symbols:**

```
ffff8000103148d0-ffff800010314918: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052ebb4)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - fs/io_uring.c:io_mem_free
```
**Symbols:**

```
c052ebb4-c052ebec: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e6040)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
  - fs/io_uring.c:io_mem_free
```
**Symbols:**

```
c0000000003e6040-c0000000003e60bc: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021b214)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - fs/io_uring.c:io_mem_free
```
**Symbols:**

```
ffffffe00021b214-ffffffe00021b258: free_compound_page (STB_GLOBAL)
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
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275390)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
  - fs/io_uring.c:io_mem_free
```
**Symbols:**

```
ffffffff81275390-ffffffff812753c2: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812672f0)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
  - fs/io_uring.c:io_mem_free
```
**Symbols:**

```
ffffffff812672f0-ffffffff81267322: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273130)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
  - fs/io_uring.c:io_mem_free
```
**Symbols:**

```
ffffffff81273130-ffffffff81273162: free_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_compound_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81282c10)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - mm/huge_memory.c:free_transhuge_page
  - fs/io_uring.c:io_mem_free
```
**Symbols:**

```
ffffffff81282c10-ffffffff81282c42: free_compound_page (STB_GLOBAL)
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
