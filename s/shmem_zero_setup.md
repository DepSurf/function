# Function: <code>shmem_zero_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811abb80)
Location: mm/shmem.c:3434
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff811abb80-ffffffff811abbe0: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c4570)
Location: mm/shmem.c:4195
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff811c4570-ffffffff811c4635: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d4660)
Location: mm/shmem.c:4089
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff811d4660-ffffffff811d4725: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dd330)
Location: mm/shmem.c:4254
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff811dd330-ffffffff811dd432: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f2db0)
Location: mm/shmem.c:4314
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff811f2db0-ffffffff811f2eb8: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81213fc0)
Location: mm/shmem.c:4030
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff81213fc0-ffffffff812140ac: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81225a20)
Location: mm/shmem.c:3989
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff81225a20-ffffffff81225b0c: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81232be0)
Location: mm/shmem.c:4070
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff81232be0-ffffffff81232ccf: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81240e00)
Location: mm/shmem.c:4192
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff81240e00-ffffffff81240eef: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81271e10)
Location: mm/shmem.c:4155
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff81271e10-ffffffff81271ee8: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127ce60)
Location: mm/shmem.c:4262
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff8127ce60-ffffffff8127cf71: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81282120)
Location: mm/shmem.c:4206
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff81282120-ffffffff81282239: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bf7c0)
Location: mm/shmem.c:4142
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff812bf7c0-ffffffff812bf8ef: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131cce0)
Location: mm/shmem.c:4154
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff8131cce0-ffffffff8131cd57: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813907f0)
Location: mm/shmem.c:4283
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff813907f0-ffffffff8139085e: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813c30e0)
Location: mm/shmem.c:4492
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff813c30e0-ffffffff813c3154: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813edc00)
Location: mm/shmem.c:4867
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff813edc00-ffffffff813edc74: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffff8000102d29a0)
Location: mm/shmem.c:4192
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffff8000102d0528-ffff8000102d0594: shmem_zero_setup.part.0 (STB_LOCAL)
ffff8000102d29a0-ffff8000102d2a6c: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fa438)
Location: mm/shmem.c:4192
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
c04fa438-c04fa4c4: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000390390)
Location: mm/shmem.c:4192
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pci_mmap_legacy_page_range
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
c000000000390390-c000000000390548: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ef62c)
Location: mm/shmem.c:4192
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffe0001ef62c-ffffffe0001ef6ae: shmem_zero_setup (STB_GLOBAL)
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
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81239450)
Location: mm/shmem.c:4192
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff81239450-ffffffff8123953f: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122c490)
Location: mm/shmem.c:4192
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff8122c490-ffffffff8122c57f: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812371f0)
Location: mm/shmem.c:4192
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff812371f0-ffffffff812372df: shmem_zero_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int shmem_zero_setup(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244fa0)
Location: mm/shmem.c:4192
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - drivers/char/mem.c:mmap_zero
```
**Symbols:**

```
ffffffff81244fa0-ffffffff8124508f: shmem_zero_setup (STB_GLOBAL)
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
