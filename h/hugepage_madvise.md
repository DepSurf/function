# Function: <code>hugepage_madvise</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f7f70)
Location: mm/huge_memory.c:1995
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811f7f70-ffffffff811f7fe1: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8121cb40)
Location: mm/khugepaged.c:301
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff8121cb40-ffffffff8121cb9f: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8122f140)
Location: mm/khugepaged.c:303
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff8122f140-ffffffff8122f19f: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8123a990)
Location: mm/khugepaged.c:305
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff8123a990-ffffffff8123a9ef: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8125a220)
Location: mm/khugepaged.c:306
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff8125a220-ffffffff8125a27f: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8127df50)
Location: mm/khugepaged.c:306
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff8127df50-ffffffff8127dfaf: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81292630)
Location: mm/khugepaged.c:306
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81292630-ffffffff8129268f: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812ad010)
Location: mm/khugepaged.c:306
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812ad010-ffffffff812ad070: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812bdc10)
Location: mm/khugepaged.c:313
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812bdc10-ffffffff812bdc70: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f3410)
Location: mm/khugepaged.c:342
Inline: False
Direct callers:
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff812f3410-ffffffff812f3470: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812feba0)
Location: mm/khugepaged.c:347
Inline: False
Direct callers:
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff812feba0-ffffffff812fec00: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81305810)
Location: mm/khugepaged.c:347
Inline: False
Direct callers:
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff81305810-ffffffff81305870: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134f690)
Location: mm/khugepaged.c:347
Inline: False
Direct callers:
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff8134f690-ffffffff8134f6f0: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c7800)
Location: mm/khugepaged.c:347
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813c7800-ffffffff813c78b6: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8144b8a0)
Location: mm/khugepaged.c:352
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff8144b8a0-ffffffff8144b8fa: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81481120)
Location: mm/khugepaged.c:355
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81481120-ffffffff81481187: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814b0170)
Location: mm/khugepaged.c:349
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff814b0170-ffffffff814b01d7: hugepage_madvise (STB_GLOBAL)
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
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035f178)
Location: mm/khugepaged.c:313
Inline: False
Direct callers:
  - mm/madvise.c:__arm64_sys_madvise
```
**Symbols:**

```
ffff80001035f178-ffff80001035f218: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c05386dc)
Location: include/linux/huge_mm.h:344
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c000000000449d10)
Location: mm/khugepaged.c:313
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c000000000449d10-c000000000449db8: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffe0002215fc)
Location: include/linux/huge_mm.h:344
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
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
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b61f0)
Location: mm/khugepaged.c:313
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812b61f0-ffffffff812b6250: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a73e0)
Location: mm/khugepaged.c:313
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812a73e0-ffffffff812a7440: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b4000)
Location: mm/khugepaged.c:313
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812b4000-ffffffff812b4060: hugepage_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct *vma, long unsigned int *vm_flags, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c44a0)
Location: mm/khugepaged.c:313
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812c44a0-ffffffff812c4500: hugepage_madvise (STB_GLOBAL)
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
