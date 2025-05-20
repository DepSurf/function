# Function: <code>__mmu_notifier_change_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff811e4090)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff811e4090-ffffffff811e4107: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81202b20)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81202b20-ffffffff81202b97: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81214960)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81214960-ffffffff812149d7: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8121fde0)
Location: mm/mmu_notifier.c:163
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8121fde0-ffffffff8121fe57: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8123b000)
Location: mm/mmu_notifier.c:163
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8123b000-ffffffff8123b07a: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8125e540)
Location: mm/mmu_notifier.c:163
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8125e540-ffffffff8125e5ba: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81272dc0)
Location: mm/mmu_notifier.c:156
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81272dc0-ffffffff81272e3a: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8128e5b0)
Location: mm/mmu_notifier.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff8128e5b0-ffffffff8128e637: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8129e190)
Location: mm/mmu_notifier.c:148
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff8129e190-ffffffff8129e217: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d27b0)
Location: mm/mmu_notifier.c:427
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
**Symbols:**

```
ffffffff812d27b0-ffffffff812d2837: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812de1e0)
Location: mm/mmu_notifier.c:427
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
**Symbols:**

```
ffffffff812de1e0-ffffffff812de267: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e5930)
Location: mm/mmu_notifier.c:427
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
**Symbols:**

```
ffffffff812e5930-ffffffff812e59b7: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8132d760)
Location: mm/mmu_notifier.c:427
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
**Symbols:**

```
ffffffff8132d760-ffffffff8132d7e7: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8139d950)
Location: mm/mmu_notifier.c:427
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
**Symbols:**

```
ffffffff8139d950-ffffffff8139d9e2: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8141ce50)
Location: mm/mmu_notifier.c:427
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
**Symbols:**

```
ffffffff8141ce50-ffffffff8141cee2: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81450410)
Location: mm/mmu_notifier.c:427
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
**Symbols:**

```
ffffffff81450410-ffffffff814504a2: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8148a140)
Location: mm/mmu_notifier.c:427
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate_device.c:migrate_vma_insert_page
```
**Symbols:**

```
ffffffff8148a140-ffffffff8148a1d2: __mmu_notifier_change_pte (STB_GLOBAL)
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
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffff80001033d610)
Location: mm/mmu_notifier.c:148
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffff80001033d610-ffff80001033d6cc: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c0543c44)
Location: mm/mmu_notifier.c:148
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
**Symbols:**

```
c0543c44-c0543d04: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c000000000418cd0)
Location: mm/mmu_notifier.c:148
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
```
**Symbols:**

```
c000000000418cd0-c000000000418dfc: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffe000232d38)
Location: mm/mmu_notifier.c:148
Inline: False
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffe000232d38-ffffffe000232db8: __mmu_notifier_change_pte (STB_GLOBAL)
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
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81296770)
Location: mm/mmu_notifier.c:148
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff81296770-ffffffff812967f7: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81288380)
Location: mm/mmu_notifier.c:148
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff81288380-ffffffff81288407: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81294580)
Location: mm/mmu_notifier.c:148
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff81294580-ffffffff81294607: __mmu_notifier_change_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __mmu_notifier_change_pte(struct mm_struct *mm, long unsigned int address, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812a43f0)
Location: mm/mmu_notifier.c:148
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff812a43f0-ffffffff812a4477: __mmu_notifier_change_pte (STB_GLOBAL)
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
