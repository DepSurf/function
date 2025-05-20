# Function: <code>page_address_in_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811ca770)
Location: mm/rmap.c:694
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/mempolicy.c:new_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff811ca770-ffffffff811ca81d: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e7120)
Location: mm/rmap.c:662
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/mempolicy.c:new_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff811e7120-ffffffff811e7221: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f84b0)
Location: mm/rmap.c:661
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/mempolicy.c:new_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff811f84b0-ffffffff811f85b1: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81203970)
Location: mm/rmap.c:685
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/mempolicy.c:new_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff81203970-ffffffff81203a5e: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121c670)
Location: mm/rmap.c:686
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/mempolicy.c:new_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff8121c670-ffffffff8121c75e: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123e460)
Location: mm/rmap.c:687
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_vma
  - mm/mempolicy.c:new_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff8123e460-ffffffff8123e547: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812529f0)
Location: mm/rmap.c:687
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_vma
  - mm/mempolicy.c:new_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812529f0-ffffffff81252ada: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81264d70)
Location: mm/rmap.c:687
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff81264d70-ffffffff81264e5a: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81273600)
Location: mm/rmap.c:688
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff81273600-ffffffff812736ea: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a4780)
Location: mm/rmap.c:701
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812a4780-ffffffff812a486a: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812aff10)
Location: mm/rmap.c:701
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812aff10-ffffffff812afffa: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b54f0)
Location: mm/rmap.c:708
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812b54f0-ffffffff812b561c: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f7180)
Location: mm/rmap.c:709
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812f7180-ffffffff812f729b: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135c680)
Location: mm/rmap.c:752
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff8135c680-ffffffff8135c8a2: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d6d60)
Location: mm/rmap.c:747
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff813d6d60-ffffffff813d6f75: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140bdb0)
Location: mm/rmap.c:750
Inline: False
Direct callers:
  - mm/mempolicy.c:new_folio
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/memory-failure.c:__add_to_kill
```
**Symbols:**

```
ffffffff8140bdb0-ffffffff8140be73: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81438660)
Location: mm/rmap.c:775
Inline: False
Direct callers:
  - mm/mempolicy.c:do_mbind
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/memory-failure.c:__add_to_kill
```
**Symbols:**

```
ffffffff81438660-ffffffff81438720: page_address_in_vma (STB_GLOBAL)
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
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff800010309178)
Location: mm/rmap.c:688
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffff800010309178-ffff800010309290: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0525ee8)
Location: mm/rmap.c:688
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
**Symbols:**

```
c0525ee8-c0525fa0: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d8500)
Location: mm/rmap.c:688
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
c0000000003d8500-c0000000003d869c: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000213686)
Location: mm/rmap.c:688
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffe000213686-ffffffe00021372e: page_address_in_vma (STB_GLOBAL)
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
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126bc50)
Location: mm/rmap.c:688
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff8126bc50-ffffffff8126bd3a: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125dcf0)
Location: mm/rmap.c:688
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff8125dcf0-ffffffff8125ddda: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812699f0)
Location: mm/rmap.c:688
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812699f0-ffffffff81269ada: page_address_in_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int page_address_in_vma(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81279360)
Location: mm/rmap.c:688
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
  - mm/ksm.c:replace_page
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff81279360-ffffffff8127944a: page_address_in_vma (STB_GLOBAL)
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
