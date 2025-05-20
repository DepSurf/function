# Function: <code>reuse_ksm_page</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81292b60)
Location: mm/ksm.c:2677
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81292b60-ffffffff81292c39: reuse_ksm_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a28e0)
Location: mm/ksm.c:2659
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812a28e0-ffffffff812a29b9: reuse_ksm_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d7060)
Location: mm/ksm.c:2672
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812d7060-ffffffff812d7139: reuse_ksm_page (STB_GLOBAL)
```
</details>
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
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff800010342300)
Location: mm/ksm.c:2659
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffff800010342300-ffff800010342420: reuse_ksm_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c0548054)
Location: mm/ksm.c:2659
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c0548054-c0548140: reuse_ksm_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c00000000041fcb0)
Location: mm/ksm.c:2659
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c00000000041fcb0-c00000000041fe34: reuse_ksm_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffe000236546)
Location: mm/ksm.c:2659
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffe000236546-ffffffe00023662e: reuse_ksm_page (STB_GLOBAL)
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
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8129aec0)
Location: mm/ksm.c:2659
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8129aec0-ffffffff8129af99: reuse_ksm_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128ca80)
Location: mm/ksm.c:2659
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8128ca80-ffffffff8128cb59: reuse_ksm_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81298cd0)
Location: mm/ksm.c:2659
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81298cd0-ffffffff81298da9: reuse_ksm_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool reuse_ksm_page(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a8ab0)
Location: mm/ksm.c:2659
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812a8ab0-ffffffff812a8b89: reuse_ksm_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
