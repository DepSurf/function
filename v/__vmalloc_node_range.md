# Function: <code>__vmalloc_node_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cf050)
Location: mm/vmalloc.c:1653
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - mm/vmalloc.c:__vmalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_exec
```
**Symbols:**

```
ffffffff811cf050-ffffffff811cf2d7: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ec1e0)
Location: mm/vmalloc.c:1674
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff811ec1e0-ffffffff811ec45f: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd480)
Location: mm/vmalloc.c:1688
Inline: False
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc
  - mm/vmalloc.c:__vmalloc_node_range
```
**Symbols:**

```
ffffffff811fd480-ffffffff811fd6fb: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81208150)
Location: mm/vmalloc.c:1749
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff81208150-ffffffff812083e2: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81221230)
Location: mm/vmalloc.c:1741
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff81221230-ffffffff81221491: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812430e0)
Location: mm/vmalloc.c:1728
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff812430e0-ffffffff81243352: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812577f0)
Location: mm/vmalloc.c:1734
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff812577f0-ffffffff81257a3a: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126a540)
Location: mm/vmalloc.c:2472
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:copy_process
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff8126a540-ffffffff8126a7ac: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81279450)
Location: mm/vmalloc.c:2480
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:copy_process
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff81279450-ffffffff812796bf: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac530)
Location: mm/vmalloc.c:2527
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/module.c:module_alloc
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:__vmalloc_node
```
**Symbols:**

```
ffffffff812ac530-ffffffff812ac5dc: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7a60)
Location: mm/vmalloc.c:2560
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/module.c:module_alloc
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:__vmalloc_node
```
**Symbols:**

```
ffffffff812b7a60-ffffffff812b7b0c: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bd470)
Location: mm/vmalloc.c:2866
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/module.c:module_alloc
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_no_huge
  - mm/vmalloc.c:__vmalloc_node
```
**Symbols:**

```
ffffffff812bd470-ffffffff812bd54d: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ffc30)
Location: mm/vmalloc.c:2970
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/module.c:module_alloc
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_no_huge
  - mm/vmalloc.c:__vmalloc_node
```
**Symbols:**

```
ffffffff812ffc30-ffffffff812ffd0d: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3081
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/module/main.c:module_alloc
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_huge
  - mm/vmalloc.c:__vmalloc_node
```
**Symbols:**

```
ffffffff81e6ede8-ffffffff81e6edfd: __vmalloc_node_range.cold (STB_LOCAL)
ffffffff81366e40-ffffffff8136705e: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3143
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/module/main.c:module_alloc
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_huge
  - mm/vmalloc.c:__vmalloc_node
```
**Symbols:**

```
ffffffff82064d0d-ffffffff82064d22: __vmalloc_node_range.cold (STB_LOCAL)
ffffffff813e2ce0-ffffffff813e2efe: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3236
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/module/main.c:module_alloc
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_huge
  - mm/vmalloc.c:__vmalloc_node
```
**Symbols:**

```
ffffffff820e44a2-ffffffff820e44b7: __vmalloc_node_range.cold (STB_LOCAL)
ffffffff81417940-ffffffff81417b5b: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3236
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/module/main.c:module_alloc
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - mm/util.c:kvmalloc_node
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_huge
  - mm/vmalloc.c:__vmalloc_node
```
**Symbols:**

```
ffffffff821c10d6-ffffffff821c10eb: __vmalloc_node_range.cold (STB_LOCAL)
ffffffff81444490-ffffffff814446ab: __vmalloc_node_range (STB_GLOBAL)
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
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030feb8)
Location: mm/vmalloc.c:2480
Inline: True
Direct callers:
  - arch/arm64/kernel/irq.c:init_IRQ
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/sdei.c:_init_sdei_stack
  - arch/arm64/net/bpf_jit_comp.c:bpf_jit_alloc_exec
  - kernel/fork.c:dup_task_struct
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffff80001030feb8-ffff800010310238: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052c364)
Location: mm/vmalloc.c:2480
Inline: True
Direct callers:
  - arch/arm/kernel/module.c:module_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
c052c364-c052c610: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e1180)
Location: mm/vmalloc.c:2480
Inline: True
Direct callers:
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
c0000000003e1180-c0000000003e1508: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe0002183c4)
Location: mm/vmalloc.c:2480
Inline: True
Direct callers:
  - arch/riscv/kernel/module.c:module_alloc
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffe0002183c4-ffffffe0002185e8: __vmalloc_node_range (STB_GLOBAL)
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
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81271aa0)
Location: mm/vmalloc.c:2480
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:copy_process
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff81271aa0-ffffffff81271d0f: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263a10)
Location: mm/vmalloc.c:2480
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:copy_process
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff81263a10-ffffffff81263c7f: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126f840)
Location: mm/vmalloc.c:2480
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:copy_process
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff8126f840-ffffffff8126faaf: __vmalloc_node_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *__vmalloc_node_range(long unsigned int size, long unsigned int align, long unsigned int start, long unsigned int end, gfp_t gfp_mask, pgprot_t prot, long unsigned int vm_flags, int node, const void *caller);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f250)
Location: mm/vmalloc.c:2480
Inline: True
Direct callers:
  - arch/x86/kernel/module.c:module_alloc
  - kernel/fork.c:copy_process
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc
```
**Symbols:**

```
ffffffff8127f250-ffffffff8127f493: __vmalloc_node_range (STB_GLOBAL)
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
