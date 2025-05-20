# Function: <code>pte_none_mostly</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pte_none_mostly(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff813494a9)
Location: include/linux/swapops.h:365
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/memcontrol.c (ffffffff813ce8ec)
Location: include/linux/swapops.h:365
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff813e42c1)
Location: include/linux/swapops.h:365
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e83db)
Location: include/linux/swapops.h:365
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8145d9f0)
Location: include/linux/swapops.h:365
Inline: True
```
**Symbols:**

```
ffffffff813e3ec0-ffffffff813e3f4d: pte_none_mostly (STB_LOCAL)
ffffffff8145dab0-ffffffff8145db3d: pte_none_mostly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pte_none_mostly(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff813c1898)
Location: include/linux/swapops.h:457
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/memcontrol.c (ffffffff81453369)
Location: include/linux/swapops.h:457
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8146bd59)
Location: include/linux/swapops.h:457
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff81470304)
Location: include/linux/swapops.h:457
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ed420)
Location: include/linux/swapops.h:457
Inline: True
```
**Symbols:**

```
ffffffff8146b920-ffffffff8146b9ad: pte_none_mostly (STB_LOCAL)
ffffffff814ed4f0-ffffffff814ed57d: pte_none_mostly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pte_none_mostly(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff813f6731)
Location: include/linux/swapops.h:448
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/memcontrol.c (ffffffff81488f74)
Location: include/linux/swapops.h:448
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814a0b26)
Location: include/linux/swapops.h:448
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a4ad5)
Location: include/linux/swapops.h:448
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff8152412e)
Location: include/linux/swapops.h:448
Inline: True
```
**Symbols:**

```
ffffffff814a0790-ffffffff814a081d: pte_none_mostly (STB_LOCAL)
ffffffff81524210-ffffffff8152429d: pte_none_mostly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pte_none_mostly(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff814223e1)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/memcontrol.c (ffffffff814b8ee2)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814d2375)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d5b31)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81558690)
Location: include/linux/swapops.h:453
Inline: True
```
**Symbols:**

```
ffffffff81558690-ffffffff8155871d: pte_none_mostly (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
