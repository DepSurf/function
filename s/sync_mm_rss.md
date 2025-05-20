# Function: <code>sync_mm_rss</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bc970)
Location: mm/memory.c:137
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff811bc970-ffffffff811bc9ce: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d7720)
Location: mm/memory.c:140
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff811d7720-ffffffff811d777e: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e7430)
Location: mm/memory.c:140
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff811e7430-ffffffff811e748e: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2540)
Location: mm/memory.c:144
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:copy_page_range
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff811f2540-ffffffff811f259e: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209500)
Location: mm/memory.c:145
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:copy_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81209500-ffffffff8120955e: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a3a0)
Location: mm/memory.c:144
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff8122a3a0-ffffffff8122a3fe: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123d9f0)
Location: mm/memory.c:144
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff8123d9f0-ffffffff8123da4e: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f6d0)
Location: mm/memory.c:146
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff8124f6d0-ffffffff8124f731: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125dc70)
Location: mm/memory.c:146
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff8125dc70-ffffffff8125dcd1: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128da00)
Location: mm/memory.c:164
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8128da00-ffffffff8128dae2: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812986a0)
Location: mm/memory.c:166
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff812986a0-ffffffff8129875b: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129ddc0)
Location: mm/memory.c:178
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8129ddc0-ffffffff8129de7b: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812def60)
Location: mm/memory.c:177
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff812def60-ffffffff812df094: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133f470)
Location: mm/memory.c:181
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8133f470-ffffffff8133f5ce: sync_mm_rss (STB_GLOBAL)
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
In kernel/exit.c (0)
Location: include/linux/mm.h:2292
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/mm.h:2292
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2292
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mm.h:2292
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mm.h:2292
Inline: True
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
In kernel/exit.c (0)
Location: include/linux/mm.h:2612
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/mm.h:2612
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2612
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mm.h:2612
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mm.h:2612
Inline: True
```
</details>
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
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f5330)
Location: mm/memory.c:146
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffff8000102f5330-ffff8000102f53b4: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0517394)
Location: mm/memory.c:146
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
c0517394-c0517424: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bc300)
Location: mm/memory.c:146
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
c0000000003bc300-c0000000003bc374: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000209bde)
Location: mm/memory.c:146
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffe000206962-ffffffe0002069b2: sync_mm_rss (STB_GLOBAL)
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
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812562c0)
Location: mm/memory.c:146
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812562c0-ffffffff81256321: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81248950)
Location: mm/memory.c:146
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81248950-ffffffff812489b1: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81254060)
Location: mm/memory.c:146
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81254060-ffffffff812540c1: sync_mm_rss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sync_mm_rss(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81263af0)
Location: mm/memory.c:146
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - mm/mmu_context.c:unuse_mm
  - mm/memory.c:handle_mm_fault
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81263af0-ffffffff81263b51: sync_mm_rss (STB_GLOBAL)
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
