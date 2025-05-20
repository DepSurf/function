# Function: <code>move_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811c9a10)
Location: mm/mremap.c:236
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811c9a10-ffffffff811c9ccf: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811e5ea0)
Location: mm/mremap.c:235
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811e5ea0-ffffffff811e617f: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811f6180)
Location: mm/mremap.c:251
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811f6180-ffffffff811f645f: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81200f60)
Location: mm/mremap.c:262
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff81200f60-ffffffff81201210: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81219910)
Location: mm/mremap.c:263
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff81219910-ffffffff81219bc3: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8123b1e0)
Location: mm/mremap.c:259
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff8123b1e0-ffffffff8123b48a: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8124f5a0)
Location: mm/mremap.c:317
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff8124f5a0-ffffffff8124f84a: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81261900)
Location: mm/mremap.c:318
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81261900-ffffffff81261baa: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812700d0)
Location: mm/mremap.c:318
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812700d0-ffffffff8127037a: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812a08b0)
Location: mm/mremap.c:337
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812a08b0-ffffffff812a0c0f: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812abfb0)
Location: mm/mremap.c:485
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812abfb0-ffffffff812ac3fb: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812b12b0)
Location: mm/mremap.c:484
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812b12b0-ffffffff812b1724: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:562
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812f2e70-ffffffff812f32f2: move_vma (STB_LOCAL)
ffffffff81cbcad4-ffffffff81cbcaf2: move_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:569
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81356bd0-ffffffff81357033: move_vma (STB_LOCAL)
ffffffff81e6e66d-ffffffff81e6e68b: move_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:571
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff813d1170-ffffffff813d15d4: move_vma (STB_LOCAL)
ffffffff8206457e-ffffffff8206459c: move_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:583
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81405b50-ffffffff814061d0: move_vma (STB_LOCAL)
ffffffff820e3c59-ffffffff820e3c7d: move_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:650
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81432250-ffffffff814328d3: move_vma (STB_LOCAL)
ffffffff821c0802-ffffffff821c0826: move_vma.cold (STB_LOCAL)
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
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffff8000103065f0)
Location: mm/mremap.c:318
Inline: False
Direct callers:
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:__arm64_sys_mremap
```
**Symbols:**

```
ffff8000103065f0-ffff800010306888: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c05241c8)
Location: mm/mremap.c:318
Inline: False
Direct callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c05241c8-c0524470: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c0000000003d4430)
Location: mm/mremap.c:318
Inline: False
Direct callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c0000000003d4430-c0000000003d47d4: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffe000211e38)
Location: mm/mremap.c:318
Inline: False
Direct callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
ffffffe000211e38-ffffffe00021202e: move_vma (STB_LOCAL)
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
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81268720)
Location: mm/mremap.c:318
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81268720-ffffffff812689ca: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8125aa10)
Location: mm/mremap.c:318
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff8125aa10-ffffffff8125acba: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812664c0)
Location: mm/mremap.c:318
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812664c0-ffffffff8126676a: move_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int move_vma(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int old_len, long unsigned int new_len, long unsigned int new_addr, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81275e60)
Location: mm/mremap.c:318
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81275e60-ffffffff8127610a: move_vma (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_userfaultfd_ctx *uf</code>
</li>
<li>
<b>Param added. </b>
<code>struct list_head *uf_unmap</code>
</li>
</ul>
</details>
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
<code>long unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, old_addr, old_len, new_len, new_addr, locked, uf, uf_unmap</code> ➡️ <code>vma, old_addr, old_len, new_len, new_addr, locked, flags, uf, uf_unmap</code>
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
