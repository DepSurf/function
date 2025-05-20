# Function: <code>page_anon_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811ac0a0)
Location: mm/util.c:320
Inline: False
Direct callers:
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:rmap_walk
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff811ac0a0-ffffffff811ac0d7: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4d10)
Location: mm/util.c:373
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff811c4d10-ffffffff811c4d44: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4e20)
Location: mm/util.c:376
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff811d4e20-ffffffff811d4e54: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811ddc70)
Location: mm/util.c:460
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff811ddc70-ffffffff811ddca4: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f36f0)
Location: mm/util.c:460
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff811f36f0-ffffffff811f3724: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812149b0)
Location: mm/util.c:486
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/swapfile.c:unuse_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff812149b0-ffffffff812149e4: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227890)
Location: mm/util.c:489
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/swapfile.c:unuse_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff81227890-ffffffff812278c4: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81237630)
Location: mm/util.c:532
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff81237630-ffffffff81237664: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81245880)
Location: mm/util.c:637
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff81245880-ffffffff812458b4: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812735b0)
Location: mm/util.c:665
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff812735b0-ffffffff812735e4: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127dd70)
Location: mm/util.c:678
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff8127dd70-ffffffff8127dda4: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282f30)
Location: mm/util.c:678
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff81282f30-ffffffff81282f64: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c1020)
Location: mm/util.c:699
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff812c1020-ffffffff812c1054: page_anon_vma (STB_GLOBAL)
```
</details>
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
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d8e28)
Location: mm/util.c:637
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffff8000102d8e28-ffff8000102d8e70: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c0500028)
Location: mm/util.c:637
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
c0500028-c0500060: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000398940)
Location: mm/util.c:637
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
c000000000398940-c00000000039898c: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f32b8)
Location: mm/util.c:637
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffe0001f32b8-ffffffe0001f32f8: page_anon_vma (STB_GLOBAL)
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
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123ded0)
Location: mm/util.c:637
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff8123ded0-ffffffff8123df04: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230ed0)
Location: mm/util.c:637
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff81230ed0-ffffffff81230f04: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123bc70)
Location: mm/util.c:637
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff8123bc70-ffffffff8123bca4: page_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct anon_vma *page_anon_vma(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124b380)
Location: mm/util.c:637
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:ksm_might_need_to_copy
```
**Symbols:**

```
ffffffff8124b380-ffffffff8124b3b4: page_anon_vma (STB_GLOBAL)
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
