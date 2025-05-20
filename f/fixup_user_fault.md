# Function: <code>fixup_user_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811bb500)
Location: mm/gup.c:587
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff811bb500-ffffffff811bb5bc: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d5f10)
Location: mm/gup.c:678
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff811d5f10-ffffffff811d6013: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e46a0)
Location: mm/gup.c:689
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff811e46a0-ffffffff811e483b: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811eeb00)
Location: mm/gup.c:772
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff811eeb00-ffffffff811eec7b: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81204fe0)
Location: mm/gup.c:797
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff81204fe0-ffffffff8120515c: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81225f20)
Location: mm/gup.c:816
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff81225f20-ffffffff8122609d: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81239690)
Location: mm/gup.c:841
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff81239690-ffffffff8123980d: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124a720)
Location: mm/gup.c:957
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff8124a720-ffffffff8124a8a8: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81258bf0)
Location: mm/gup.c:958
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff81258bf0-ffffffff81258d78: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287700)
Location: mm/gup.c:1217
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff81287700-ffffffff81287888: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fixup_user_fault(struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81291550)
Location: mm/gup.c:1171
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
**Symbols:**

```
ffffffff81291550-ffffffff812916cc: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fixup_user_fault(struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81296a70)
Location: mm/gup.c:1256
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
**Symbols:**

```
ffffffff81296a70-ffffffff81296be9: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fixup_user_fault(struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d7470)
Location: mm/gup.c:1284
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
**Symbols:**

```
ffffffff812d7470-ffffffff812d75d8: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fixup_user_fault(struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81337100)
Location: mm/gup.c:1308
Inline: False
Direct callers:
  - kernel/futex/core.c:fault_in_user_writeable
  - mm/gup.c:fault_in_safe_writeable
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
**Symbols:**

```
ffffffff81337100-ffffffff8133728a: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fixup_user_fault(struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813aea90)
Location: mm/gup.c:1261
Inline: False
Direct callers:
  - kernel/futex/core.c:fault_in_user_writeable
  - mm/gup.c:fault_in_safe_writeable
```
**Symbols:**

```
ffffffff813aea90-ffffffff813aec52: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fixup_user_fault(struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e2b40)
Location: mm/gup.c:1366
Inline: False
Direct callers:
  - kernel/futex/core.c:fault_in_user_writeable
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
  - mm/gup.c:fault_in_safe_writeable
```
**Symbols:**

```
ffffffff813e2b40-ffffffff813e2d0b: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fixup_user_fault(struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140d380)
Location: mm/gup.c:1381
Inline: False
Direct callers:
  - kernel/futex/core.c:fault_in_user_writeable
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
  - mm/gup.c:fault_in_safe_writeable
```
**Symbols:**

```
ffffffff8140d380-ffffffff8140d54b: fixup_user_fault (STB_GLOBAL)
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
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f0b00)
Location: mm/gup.c:958
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffff8000102f0b00-ffff8000102f0c40: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0513f70)
Location: mm/gup.c:958
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
c0513f70-c0514094: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b5600)
Location: mm/gup.c:958
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
c0000000003b5600-c0000000003b57ac: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000204250)
Location: mm/gup.c:958
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffe000204250-ffffffe00020435a: fixup_user_fault (STB_GLOBAL)
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
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251240)
Location: mm/gup.c:958
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff81251240-ffffffff812513c8: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81244130)
Location: mm/gup.c:958
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff81244130-ffffffff812442b8: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124efe0)
Location: mm/gup.c:958
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff8124efe0-ffffffff8124f168: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fixup_user_fault(struct task_struct *tsk, struct mm_struct *mm, long unsigned int address, unsigned int fault_flags, bool *unlocked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125e950)
Location: mm/gup.c:958
Inline: False
Direct callers:
  - kernel/futex.c:fault_in_user_writeable
```
**Symbols:**

```
ffffffff8125e950-ffffffff8125ead8: fixup_user_fault (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *unlocked</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, address, fault_flags, unlocked</code> ➡️ <code>mm, address, fault_flags, unlocked</code>
</li>
</ul>
</details>
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
