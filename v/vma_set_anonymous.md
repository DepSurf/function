# Function: <code>vma_set_anonymous</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812373d0)
Location: include/linux/mm.h:464
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812a2c84)
Location: include/linux/mm.h:464
Inline: True
```
```
In drivers/char/mem.c (ffffffff81643ffb)
Location: include/linux/mm.h:464
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124ac94)
Location: include/linux/mm.h:492
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812b7b56)
Location: include/linux/mm.h:492
Inline: True
```
```
In drivers/char/mem.c (ffffffff816622cb)
Location: include/linux/mm.h:492
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125d04b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812d40eb)
Location: include/linux/mm.h:539
Inline: True
```
```
In drivers/char/mem.c (ffffffff81697e7b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126b81b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812e5c7b)
Location: include/linux/mm.h:539
Inline: True
```
```
In drivers/char/mem.c (ffffffff816ba9fb)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129b651)
Location: include/linux/mm.h:612
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff8131b9af)
Location: include/linux/mm.h:612
Inline: True
Inline callers:
  - fs/exec.c:__bprm_mm_init
```
```
In drivers/char/mem.c (ffffffff8176edcb)
Location: include/linux/mm.h:612
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a6842)
Location: include/linux/mm.h:645
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff8132739b)
Location: include/linux/mm.h:645
Inline: True
Inline callers:
  - fs/exec.c:__bprm_mm_init
```
```
In drivers/char/mem.c (ffffffff817896ab)
Location: include/linux/mm.h:645
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ac7e7)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff8132d43b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - fs/exec.c:__bprm_mm_init
```
```
In drivers/char/mem.c (ffffffff8176cf8b)
Location: include/linux/mm.h:668
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812edf37)
Location: include/linux/mm.h:669
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff8137ac4b)
Location: include/linux/mm.h:669
Inline: True
Inline callers:
  - fs/exec.c:__bprm_mm_init
```
```
In drivers/char/mem.c (ffffffff817f275b)
Location: include/linux/mm.h:669
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81351384)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff813fafe8)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
```
```
In drivers/char/mem.c (ffffffff819331fb)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ca814)
Location: include/linux/mm.h:631
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff814848e8)
Location: include/linux/mm.h:631
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
```
```
In drivers/char/mem.c (ffffffff81a91f2b)
Location: include/linux/mm.h:631
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fee0b)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff814b94c8)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
```
```
In drivers/char/mem.c (ffffffff81add7bb)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142b28f)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff814ebfcf)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
```
```
In drivers/char/mem.c (ffffffff81b30beb)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010302fbc)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffff80001038e024)
Location: include/linux/mm.h:539
Inline: True
```
```
In drivers/char/mem.c (ffff8000108aad78)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0521630)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (c05759a8)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In drivers/char/mem.c (c09a70ec)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cf860)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (c0000000004862dc)
Location: include/linux/mm.h:539
Inline: True
```
```
In drivers/char/mem.c (c0000000009424bc)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020fc44)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffe00025eb52)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In drivers/char/mem.c (ffffffe00055fe10)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81263e6b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812de25b)
Location: include/linux/mm.h:539
Inline: True
```
```
In drivers/char/mem.c (ffffffff8168045b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125628b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812cf58b)
Location: include/linux/mm.h:539
Inline: True
```
```
In drivers/char/mem.c (ffffffff8165e12b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81261c0b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812dc06b)
Location: include/linux/mm.h:539
Inline: True
```
```
In drivers/char/mem.c (ffffffff816ae83b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812715cb)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812ecdf5)
Location: include/linux/mm.h:539
Inline: True
```
```
In drivers/char/mem.c (ffffffff816c8c8b)
Location: include/linux/mm.h:539
Inline: True
Inline callers:
  - drivers/char/mem.c:mmap_zero
```
</details>
</li>
</ul>

## Differences
