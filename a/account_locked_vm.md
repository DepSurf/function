# Function: <code>account_locked_vm</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81237160)
Location: mm/util.c:362
Inline: True
```
**Symbols:**

```
ffffffff81237160-ffffffff812371d9: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812453d0)
Location: mm/util.c:467
Inline: True
```
**Symbols:**

```
ffffffff812453d0-ffffffff81245449: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272f20)
Location: mm/util.c:477
Inline: True
```
**Symbols:**

```
ffffffff81272f20-ffffffff81272f99: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/util.c (ffffffff8127d6e0)
Location: mm/util.c:490
Inline: True
```
**Symbols:**

```
ffffffff8127d6e0-ffffffff8127d78c: account_locked_vm.part.0 (STB_LOCAL)
ffffffff8127d790-ffffffff8127d7b0: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812828b0)
Location: mm/util.c:490
Inline: True
```
**Symbols:**

```
ffffffff812828b0-ffffffff8128297b: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c09d0)
Location: mm/util.c:490
Inline: True
```
**Symbols:**

```
ffffffff812c09d0-ffffffff812c0a84: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d660)
Location: mm/util.c:523
Inline: True
```
**Symbols:**

```
ffffffff8131d660-ffffffff8131d737: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81391330)
Location: mm/util.c:491
Inline: True
```
**Symbols:**

```
ffffffff81391330-ffffffff81391407: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3cf0)
Location: mm/util.c:514
Inline: True
```
**Symbols:**

```
ffffffff813c3cf0-ffffffff813c3de0: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ee8a0)
Location: mm/util.c:527
Inline: True
```
**Symbols:**

```
ffffffff813ee8a0-ffffffff813ee990: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d8310)
Location: mm/util.c:467
Inline: True
```
**Symbols:**

```
ffff8000102d8310-ffff8000102d83b0: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff738)
Location: mm/util.c:467
Inline: True
```
**Symbols:**

```
c04ff738-c04ff7c4: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (c0000000003980a0)
Location: mm/util.c:467
Inline: True
Direct callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_put
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_create_window
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_free_table
```
**Symbols:**

```
c0000000003980a0-c000000000398178: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2c08)
Location: mm/util.c:467
Inline: True
```
**Symbols:**

```
ffffffe0001f2c08-ffffffe0001f2c7e: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123da20)
Location: mm/util.c:467
Inline: True
```
**Symbols:**

```
ffffffff8123da20-ffffffff8123da99: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230a20)
Location: mm/util.c:467
Inline: True
```
**Symbols:**

```
ffffffff81230a20-ffffffff81230a99: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b7c0)
Location: mm/util.c:467
Inline: True
```
**Symbols:**

```
ffffffff8123b7c0-ffffffff8123b839: account_locked_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int account_locked_vm(struct mm_struct *mm, long unsigned int pages, bool inc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124aed0)
Location: mm/util.c:467
Inline: True
```
**Symbols:**

```
ffffffff8124aed0-ffffffff8124af49: account_locked_vm (STB_GLOBAL)
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
