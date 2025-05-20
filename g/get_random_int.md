# Function: <code>get_random_int</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int get_random_int();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81512bd0)
Location: drivers/char/random.c:1802
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:node_random
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - drivers/char/random.c:randomize_range
```
**Symbols:**

```
ffffffff81512bd0-ffffffff81512c38: get_random_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int get_random_int();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81565550)
Location: drivers/char/random.c:2062
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - mm/slub.c:new_slab
  - lib/nodemask.c:node_random
  - drivers/char/random.c:randomize_range
```
**Symbols:**

```
ffffffff81565550-ffffffff815655c1: get_random_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int get_random_int();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81591cb0)
Location: drivers/char/random.c:2062
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/kernel/process.c:arch_align_stack
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/module.c:module_alloc
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - mm/slub.c:new_slab
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81591cb0-ffffffff81591d21: get_random_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810040ad)
Location: include/linux/random.h:48
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff81036315)
Location: include/linux/random.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104036e)
Location: include/linux/random.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff81062849)
Location: include/linux/random.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff8118f6f1)
Location: include/linux/random.h:48
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In mm/slub.c (ffffffff81225e22)
Location: include/linux/random.h:48
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In net/ipv4/route.c (ffffffff8180f2c1)
Location: include/linux/random.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffffffff818eff4a)
Location: include/linux/random.h:48
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8100430d)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff810386a6)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104425b)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff8106698c)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff8119db78)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In mm/slub.c (ffffffff812430b8)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In net/ipv4/route.c (ffffffff8188e921)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffffffff8197639a)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004aae)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff81039b56)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81045a10)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff81069545)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811b23ab)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In mm/slub.c (ffffffff81264909)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In net/ipv4/route.c (ffffffff818e25aa)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffffffff819d2b5a)
Location: include/linux/random.h:49
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/entry/vdso/vma.c (ffffffff81004a0e)
Location: include/linux/random.h:50
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff8103b0b6)
Location: include/linux/random.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047460)
Location: include/linux/random.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff8106f295)
Location: include/linux/random.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811c0e11)
Location: include/linux/random.h:50
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/hashtab.c (ffffffff811d4cbe)
Location: include/linux/random.h:50
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff8127904e)
Location: include/linux/random.h:50
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
```
In net/ipv4/route.c (ffffffff8190f44a)
Location: include/linux/random.h:50
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffffffff81a0c1da)
Location: include/linux/random.h:50
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c7e)
Location: include/linux/random.h:51
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff8103d695)
Location: include/linux/random.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a0c2)
Location: include/linux/random.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff81073378)
Location: include/linux/random.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811ce715)
Location: include/linux/random.h:51
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff811e5095)
Location: include/linux/random.h:51
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/hashtab.c (ffffffff811e7a68)
Location: include/linux/random.h:51
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff81294286)
Location: include/linux/random.h:51
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In net/ipv4/route.c (ffffffff8197163a)
Location: include/linux/random.h:51
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffffffff81a7bb3a)
Location: include/linux/random.h:51
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/entry/vdso/vma.c (ffffffff81004cfe)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff8103de55)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104aa52)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff81074338)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811dad35)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff811f18f4)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/hashtab.c (ffffffff811f41c8)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff812a3f74)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In net/ipv4/route.c (ffffffff819a8047)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffffffff81ab2e9a)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/entry/vdso/vma.c (ffffffff8100595d)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_addr
```
```
In arch/x86/kernel/process.c (ffffffff81040f15)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f804)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff8107b658)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811f78d5)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff8120a500)
Location: include/linux/random.h:54
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81217950)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff812d9a94)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In lib/nodemask.c (ffffffff815ed74a)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In net/ipv4/route.c (ffffffff81a90d57)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
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
In arch/x86/entry/vdso/vma.c (ffffffff8100478d)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_addr
```
```
In arch/x86/kernel/process.c (ffffffff81040e75)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ea81)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff8107b5b8)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811f68cc)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff8120c6ac)
Location: include/linux/random.h:54
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81219a20)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff812e4dfe)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In lib/nodemask.c (ffffffff81611e7a)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In net/ipv4/route.c (ffffffff81a9abb7)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
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
In arch/x86/entry/vdso/vma.c (ffffffff81004919)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff81042875)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81050224)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff8107c7d8)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811f771c)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff812106f9)
Location: include/linux/random.h:54
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8121d40e)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff812ec9e5)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In lib/nodemask.c (ffffffff815f556a)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In net/ipv4/route.c (ffffffff81a85f47)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
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
In arch/x86/entry/vdso/vma.c (ffffffff81004f49)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff81048be5)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058514)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff8108a8f8)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff81228cec)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff81244ffe)
Location: include/linux/random.h:54
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff812543b0)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff81334bb5)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In lib/nodemask.c (ffffffff816629ca)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In net/ipv4/route.c (ffffffff81b40747)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
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
In arch/x86/entry/vdso/vma.c (ffffffff810044a1)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
```
In arch/x86/kernel/process.c (ffffffff81051edb)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81064ccf)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff8109aeac)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff81269d38)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff8128ab08)
Location: include/linux/random.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8129c93f)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/bloom_filter.c (ffffffff812a4a04)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In mm/slub.c (ffffffff813a63f7)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff813b61c2)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - mm/migrate.c:next_demotion_node
```
```
In lib/nodemask.c (ffffffff8177c86a)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In net/ipv4/route.c (ffffffff81ccc9ce)
Location: include/linux/random.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/arm64/kernel/process.c (ffff8000100896e8)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:arch_align_stack
```
```
In kernel/bpf/core.c (ffff80001025b8b8)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffff800010275028)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/hashtab.c (ffff800010277af4)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffff800010345d14)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In net/ipv4/route.c (ffff800010c577e0)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffff800010d8d10c)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/arm/kernel/process.c (c030b694)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/arm/kernel/process.c:arch_setup_additional_pages
```
```
In arch/arm/kernel/signal.c (c030ecbc)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:get_signal_page
```
```
In kernel/bpf/core.c (c048ea90)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (c04a771c)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/hashtab.c (c04aab4c)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (c0549a94)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In net/ipv4/route.c (c0d67504)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
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
In arch/powerpc/kernel/process.c (c000000000022e80)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:arch_align_stack
```
```
In kernel/bpf/core.c (c0000000002ff28c)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (c00000000031ce88)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/hashtab.c (c000000000320d90)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (c0000000004223fc)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In net/ipv4/route.c (c000000000d58f60)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (c000000000ecf354)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In kernel/bpf/core.c (ffffffe00019a5a8)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffe0001ad850)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/hashtab.c (ffffffe0001b0640)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffe00023848e)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In net/ipv4/route.c (ffffffe0007c1a8c)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
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
In arch/x86/entry/vdso/vma.c (ffffffff81004cfe)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff8103dfd5)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104abc2)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff81073338)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811d3355)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff811e9f14)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/hashtab.c (ffffffff811ec7e8)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff8129c554)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In net/ipv4/route.c (ffffffff81947eb7)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffffffff81a51cea)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/entry/vdso/vma.c (ffffffff810033de)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff8102d7e5)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81039f62)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff810633b8)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811c6115)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff811dccd4)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/hashtab.c (ffffffff811df578)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff8128e101)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In net/ipv4/route.c (ffffffff819019a7)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffffffff81a0edea)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/entry/vdso/vma.c (ffffffff81004cbe)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff8103de15)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104aa02)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff810732e8)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811d1125)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff811e7ce4)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/hashtab.c (ffffffff811ea5b8)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff8129a364)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In net/ipv4/route.c (ffffffff819b2687)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffffffff81abe0da)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/entry/vdso/vma.c (ffffffff81004dfe)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/kernel/process.c (ffffffff8103ef75)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_align_stack
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104be12)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/module.c (ffffffff81075348)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In kernel/bpf/core.c (ffffffff811df415)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_insn
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff811f6094)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/hashtab.c (ffffffff811f8993)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/slub.c (ffffffff812aa244)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In net/ipv4/route.c (ffffffff819bbd47)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
```
```
In lib/nodemask.c (ffffffff81aca57a)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
</ul>
