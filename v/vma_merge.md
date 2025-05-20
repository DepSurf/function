# Function: <code>vma_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c5610)
Location: mm/mmap.c:1040
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:copy_vma
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:SyS_madvise
  - mm/mempolicy.c:do_mbind
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff811c5610-ffffffff811c5939: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e1480)
Location: mm/mmap.c:942
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:SyS_madvise
  - mm/mempolicy.c:do_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff811e1480-ffffffff811e1794: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f1440)
Location: mm/mmap.c:1082
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:SyS_madvise
  - mm/mempolicy.c:SYSC_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff811f1440-ffffffff811f178b: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fc090)
Location: mm/mmap.c:1098
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:SyS_madvise
  - mm/mempolicy.c:SYSC_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff811fc090-ffffffff811fc44b: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812145d0)
Location: mm/mmap.c:1099
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:SyS_madvise
  - mm/mempolicy.c:SYSC_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff812145d0-ffffffff8121498b: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81235480)
Location: mm/mmap.c:1108
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff81235480-ffffffff812357cd: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81248c00)
Location: mm/mmap.c:1132
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff81248c00-ffffffff81248fc9: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125aea0)
Location: mm/mmap.c:1134
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff8125aea0-ffffffff8125b286: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812695a0)
Location: mm/mmap.c:1135
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff812695a0-ffffffff81269986: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81299e40)
Location: mm/mmap.c:1116
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_behavior
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff81299e40-ffffffff8129a1bc: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a5080)
Location: mm/mmap.c:1157
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_behavior
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff812a5080-ffffffff812a53cd: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812aa7e0)
Location: mm/mmap.c:1161
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_behavior
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff812aa7e0-ffffffff812aab61: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ebe00)
Location: mm/mmap.c:1158
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_behavior
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff812ebe00-ffffffff812ec181: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134ec50)
Location: mm/mmap.c:1169
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_update_vma
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff8134ec50-ffffffff8134f06e: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c8170)
Location: mm/mmap.c:999
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/madvise.c:madvise_update_vma
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff813c8170-ffffffff813c8551: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct vma_iterator *vmi, struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fbd80)
Location: mm/mmap.c:871
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/madvise.c:madvise_update_vma
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff813fbd80-ffffffff813fc739: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct vma_iterator *vmi, struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81428010)
Location: mm/mmap.c:864
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge_extend
  - mm/mmap.c:vma_modify
```
**Symbols:**

```
ffffffff81428010-ffffffff81428be3: vma_merge (STB_LOCAL)
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
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010300a68)
Location: mm/mmap.c:1135
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__arm64_sys_madvise
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffff800010300a68-ffff800010300df8: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c051f614)
Location: mm/mmap.c:1135
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__se_sys_madvise
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
c051f614-c051f978: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003ccb70)
Location: mm/mmap.c:1135
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__se_sys_madvise
  - mm/mempolicy.c:do_mbind
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
c0000000003ccb70-c0000000003cd098: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020e170)
Location: mm/mmap.c:1135
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__se_sys_madvise
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffe00020e170-ffffffe00020e3b2: vma_merge (STB_GLOBAL)
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
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81261bf0)
Location: mm/mmap.c:1135
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff81261bf0-ffffffff81261fd6: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81254010)
Location: mm/mmap.c:1135
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff81254010-ffffffff812543f6: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125f990)
Location: mm/mmap.c:1135
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff8125f990-ffffffff8125fd76: vma_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *vma_merge(struct mm_struct *mm, struct vm_area_struct *prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int pgoff, struct mempolicy *policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126f360)
Location: mm/mmap.c:1135
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:copy_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/mempolicy.c:kernel_mbind
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
**Symbols:**

```
ffffffff8126f360-ffffffff8126f746: vma_merge (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct anon_vma_name *anon_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vma_iterator *vmi</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, prev, addr, end, vm_flags, anon_vma, file, pgoff, policy, vm_userfaultfd_ctx, anon_name</code> ➡️ <code>vmi, mm, prev, addr, end, vm_flags, anon_vma, file, pgoff, policy, vm_userfaultfd_ctx, anon_name</code>
</li>
</ul>
</details>
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
