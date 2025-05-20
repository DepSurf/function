# Function: <code>expand_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c6360)
Location: mm/mmap.c:2333
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/mmap.c:find_extend_vma
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff811c6360-ffffffff811c6393: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e2e30)
Location: mm/mmap.c:2230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/mmap.c:find_extend_vma
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff811e2e30-ffffffff811e2e62: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f2e10)
Location: mm/mmap.c:2383
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - mm/mmap.c:find_extend_vma
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff811f2e10-ffffffff811f2e42: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fddb3)
Location: mm/mmap.c:2426
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff811fdd70-ffffffff811fdd80: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81216363)
Location: mm/mmap.c:2442
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81216320-ffffffff81216330: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81237133)
Location: mm/mmap.c:2502
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812370f0-ffffffff81237100: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124a9e3)
Location: mm/mmap.c:2536
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff8124a9a0-ffffffff8124a9b0: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125cd62)
Location: mm/mmap.c:2538
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff8125cd10-ffffffff8125cd20: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126b532)
Location: mm/mmap.c:2543
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff8126b4e0-ffffffff8126b4f0: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129ac62)
Location: mm/mmap.c:2541
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff8129acb0-ffffffff8129acc0: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a5e24)
Location: mm/mmap.c:2607
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812a5e70-ffffffff812a5e80: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ac524)
Location: mm/mmap.c:2611
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812ac4e0-ffffffff812ac4f0: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812edc74)
Location: mm/mmap.c:2581
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812edc30-ffffffff812edc40: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81351053)
Location: mm/mmap.c:2602
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81351000-ffffffff81351018: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813cb4e5)
Location: mm/mmap.c:2118
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff813cb460-ffffffff813cb478: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_area_struct *expand_stack(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ffbd0)
Location: mm/mmap.c:2243
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__access_remote_vm
```
**Symbols:**

```
ffffffff813ffbd0-ffffffff813ffd19: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_area_struct *expand_stack(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142c200)
Location: mm/mmap.c:2246
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__access_remote_vm
```
**Symbols:**

```
ffffffff8142c200-ffffffff8142c349: expand_stack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010302ce8)
Location: mm/mmap.c:2543
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/arm64/mm/fault.c:do_page_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffff800010302c60-ffff800010302c94: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0521348)
Location: mm/mmap.c:2543
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/arm/mm/fault.c:do_page_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
c05212d8-c05212f4: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cf468)
Location: mm/mmap.c:2543
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/copro_fault.c:copro_handle_mm_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
c0000000003cf3e0-c0000000003cf3f4: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020fa4a)
Location: mm/mmap.c:2543
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/riscv/mm/fault.c:do_page_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffe00020f9d0-ffffffe00020fa02: expand_stack (STB_GLOBAL)
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
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81263b82)
Location: mm/mmap.c:2543
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81263b30-ffffffff81263b40: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81255fa2)
Location: mm/mmap.c:2543
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81255f50-ffffffff81255f60: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81261922)
Location: mm/mmap.c:2543
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812618d0-ffffffff812618e0: expand_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int expand_stack(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812712e2)
Location: mm/mmap.c:2543
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81271290-ffffffff812712a0: expand_stack (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct vm_area_struct *</code>
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
