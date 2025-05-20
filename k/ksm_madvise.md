# Function: <code>ksm_madvise</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff811e6ae0)
Location: mm/ksm.c:1757
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811e6ae0-ffffffff811e6b77: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81205b20)
Location: mm/ksm.c:1737
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff81205b20-ffffffff81205bb7: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81217b30)
Location: mm/ksm.c:1783
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff81217b30-ffffffff81217bc7: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81223720)
Location: mm/ksm.c:2349
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff81223720-ffffffff812237b7: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8123ed60)
Location: mm/ksm.c:2363
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff8123ed60-ffffffff8123edf7: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81262500)
Location: mm/ksm.c:2421
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81262500-ffffffff812625ac: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81276d80)
Location: mm/ksm.c:2424
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81276d80-ffffffff81276e2c: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812925f0)
Location: mm/ksm.c:2451
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812925f0-ffffffff8129269c: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a2370)
Location: mm/ksm.c:2433
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812a2370-ffffffff812a241c: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d6a80)
Location: mm/ksm.c:2441
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff812d6a80-ffffffff812d6b2c: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e25c0)
Location: mm/ksm.c:2442
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff812e25c0-ffffffff812e266c: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e9d50)
Location: mm/ksm.c:2438
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff812e9d50-ffffffff812e9df7: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81331c80)
Location: mm/ksm.c:2434
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:madvise_behavior
```
**Symbols:**

```
ffffffff81331c80-ffffffff81331d27: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff813a2e00)
Location: mm/ksm.c:2446
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813a2e00-ffffffff813a2eb9: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81422a70)
Location: mm/ksm.c:2473
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81422a70-ffffffff81422b23: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81457a70)
Location: mm/ksm.c:2656
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81457a70-ffffffff81457b35: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81492540)
Location: mm/ksm.c:2931
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81492540-ffffffff81492605: ksm_madvise (STB_GLOBAL)
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
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff800010341c40)
Location: mm/ksm.c:2433
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__arm64_sys_madvise
```
**Symbols:**

```
ffff800010341c40-ffff800010341d40: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c0547aa4)
Location: mm/ksm.c:2433
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c0547aa4-c0547b58: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c00000000041f380)
Location: mm/ksm.c:2433
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c00000000041f380-c00000000041f4bc: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffe000236016)
Location: mm/ksm.c:2433
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
ffffffe000236016-ffffffe0002360e2: ksm_madvise (STB_GLOBAL)
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
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8129a950)
Location: mm/ksm.c:2433
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8129a950-ffffffff8129a9fc: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128c510)
Location: mm/ksm.c:2433
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8128c510-ffffffff8128c5bc: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81298760)
Location: mm/ksm.c:2433
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81298760-ffffffff8129880c: ksm_madvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksm_madvise(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, int advice, long unsigned int *vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a84e0)
Location: mm/ksm.c:2433
Inline: False
Direct callers:
  - mm/mremap.c:move_vma
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812a84e0-ffffffff812a858c: ksm_madvise (STB_GLOBAL)
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
