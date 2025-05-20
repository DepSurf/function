# Function: <code>free_page_and_swap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811d2980)
Location: mm/swap_state.c:248
Inline: False
Direct callers:
  - mm/huge_memory.c:khugepaged
```
**Symbols:**

```
ffffffff811d2980-ffffffff811d29c6: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811f06a0)
Location: mm/swap_state.c:252
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff811f06a0-ffffffff811f073e: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81201070)
Location: mm/swap_state.c:254
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81201070-ffffffff81201115: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8120beb0)
Location: mm/swap_state.c:272
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8120beb0-ffffffff8120bf4d: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812254b0)
Location: mm/swap_state.c:303
Inline: False
Direct callers:
  - mm/memory.c:tlb_remove_table
  - mm/memory.c:tlb_remove_table_rcu
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812254b0-ffffffff8122557d: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81247a50)
Location: mm/swap_state.c:300
Inline: False
Direct callers:
  - mm/memory.c:tlb_remove_table
  - mm/memory.c:tlb_remove_table_rcu
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81247a50-ffffffff81247b21: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8125c020)
Location: mm/swap_state.c:276
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8125c020-ffffffff8125c0f1: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812771e0)
Location: mm/swap_state.c:277
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
```
**Symbols:**

```
ffffffff812771e0-ffffffff812772be: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81286cc0)
Location: mm/swap_state.c:277
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
```
**Symbols:**

```
ffffffff81286cc0-ffffffff81286d9e: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b9240)
Location: mm/swap_state.c:276
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/khugepaged.c:__collapse_huge_page_copy
```
**Symbols:**

```
ffffffff812b9240-ffffffff812b9317: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c4bd0)
Location: mm/swap_state.c:336
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
```
**Symbols:**

```
ffffffff812c4bd0-ffffffff812c4ca4: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cb860)
Location: mm/swap_state.c:306
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
```
**Symbols:**

```
ffffffff812cb860-ffffffff812cb934: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81310a00)
Location: mm/swap_state.c:301
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
```
**Symbols:**

```
ffffffff81310a00-ffffffff81310a7a: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8137b790)
Location: mm/swap_state.c:306
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
```
**Symbols:**

```
ffffffff8137b790-ffffffff8137b826: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff813f9100)
Location: mm/swap_state.c:295
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff813f9100-ffffffff813f9196: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8142bed0)
Location: mm/swap_state.c:300
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8142bed0-ffffffff8142bf66: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81465630)
Location: mm/swap_state.c:300
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81465630-ffffffff814656c3: free_page_and_swap_cache (STB_GLOBAL)
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
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffff800010321600)
Location: mm/swap_state.c:277
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffff800010321600-ffff800010321728: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0539e08)
Location: mm/swap_state.c:277
Inline: False
```
**Symbols:**

```
c0539e08-c0539f28: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0000000003f6c80)
Location: mm/swap_state.c:277
Inline: False
```
**Symbols:**

```
c0000000003f6c80-c0000000003f6e4c: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffe00022291a)
Location: mm/swap_state.c:277
Inline: False
```
**Symbols:**

```
ffffffe00022291a-ffffffe0002229cc: free_page_and_swap_cache (STB_GLOBAL)
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
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127f310)
Location: mm/swap_state.c:277
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
```
**Symbols:**

```
ffffffff8127f310-ffffffff8127f3ee: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81271130)
Location: mm/swap_state.c:277
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81271130-ffffffff8127120e: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127d0b0)
Location: mm/swap_state.c:277
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
```
**Symbols:**

```
ffffffff8127d0b0-ffffffff8127d18e: free_page_and_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_page_and_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128cc70)
Location: mm/swap_state.c:277
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table_rcu
```
**Symbols:**

```
ffffffff8128cc70-ffffffff8128cd4e: free_page_and_swap_cache (STB_GLOBAL)
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
