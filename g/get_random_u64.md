# Function: <code>get_random_u64</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a8870)
Location: drivers/char/random.c:2094
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - mm/slab_common.c:cache_random_seq_create
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff815a8870-ffffffff815a894b: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160f170)
Location: drivers/char/random.c:2093
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - mm/slab_common.c:cache_random_seq_create
  - mm/slub.c:__kmem_cache_create
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff8160f170-ffffffff8160f249: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81648850)
Location: drivers/char/random.c:2201
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - mm/slab_common.c:cache_random_seq_create
  - mm/slub.c:kmem_cache_open
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff81648850-ffffffff81648929: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816672f0)
Location: drivers/char/random.c:2226
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - mm/slab_common.c:cache_random_seq_create
  - mm/slub.c:kmem_cache_open
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff816672f0-ffffffff816673c9: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169c840)
Location: drivers/char/random.c:2310
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:add_to_free_area_random
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff8169c840-ffffffff8169c8e1: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bf5b0)
Location: drivers/char/random.c:2371
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:add_to_free_area_random
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff816bf5b0-ffffffff816bf651: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81772600)
Location: drivers/char/random.c:2191
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:dup_task_struct
  - kernel/seccomp.c:init_listener
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:shuffle_pick_tail
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff81772600-ffffffff817726ac: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178d670)
Location: drivers/char/random.c:2190
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:dup_task_struct
  - kernel/seccomp.c:init_listener
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:shuffle_pick_tail
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - lib/random32.c:prandom_reseed
  - lib/random32.c:prandom_reseed
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff8178d670-ffffffff8178d71c: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81770620)
Location: drivers/char/random.c:2166
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:dup_task_struct
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:shuffle_pick_tail
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - lib/random32.c:prandom_reseed
  - lib/random32.c:prandom_reseed
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff81770620-ffffffff817706cd: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f5f30)
Location: drivers/char/random.c:2191
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:dup_task_struct
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:shuffle_pick_tail
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - lib/random32.c:prandom_reseed
  - lib/random32.c:prandom_reseed
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff817f5f30-ffffffff817f5ff6: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff819351d0)
Location: drivers/char/random.c:509
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:dup_task_struct
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_page
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:shuffle_pick_tail
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff819351d0-ffffffff81935303: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a93bd0)
Location: drivers/char/random.c:533
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:dup_task_struct
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_page
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:shuffle_pick_tail
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff81a93bd0-ffffffff81a93d05: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81adf6c0)
Location: drivers/char/random.c:533
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:dup_task_struct
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_page
  - mm/util.c:randomize_stack_top
  - mm/shuffle.c:shuffle_pick_tail
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff81adf6c0-ffffffff81adf7f5: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b32ae0)
Location: drivers/char/random.c:533
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:dup_task_struct
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_page
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:create_kmalloc_caches
  - mm/shuffle.c:shuffle_pick_tail
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff81b32ae0-ffffffff81b32c15: get_random_u64 (STB_GLOBAL)
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
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108b0168)
Location: drivers/char/random.c:2371
Inline: False
Direct callers:
  - arch/arm64/kvm/va_layout.c:compute_layout
  - kernel/fork.c:dup_task_struct
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:arch_mmap_rnd
  - mm/util.c:arch_mmap_rnd
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:add_to_free_area_random
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffff8000108b0168-ffff8000108b0270: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09aa7c4)
Location: drivers/char/random.c:2371
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/shuffle.c:add_to_free_area_random
```
**Symbols:**

```
c09aa7c4-c09aa858: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000948160)
Location: drivers/char/random.c:2371
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/powerpc/kernel/process.c:arch_randomize_brk
  - arch/powerpc/kernel/process.c:arch_randomize_brk
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:add_to_free_area_random
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
c000000000948160-c00000000094825c: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe00056249a)
Location: drivers/char/random.c:2371
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:arch_pick_mmap_layout
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:add_to_free_area_random
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffe00056249a-ffffffe000562540: get_random_u64 (STB_GLOBAL)
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
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81685000)
Location: drivers/char/random.c:2371
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:add_to_free_area_random
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff81685000-ffffffff816850a1: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81662ca0)
Location: drivers/char/random.c:2371
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:add_to_free_area_random
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff81662ca0-ffffffff81662d41: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b33f0)
Location: drivers/char/random.c:2371
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:add_to_free_area_random
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff816b33f0-ffffffff816b3491: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 get_random_u64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cd970)
Location: drivers/char/random.c:2371
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - kernel/fork.c:copy_process
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/util.c:randomize_stack_top
  - mm/slab_common.c:cache_random_seq_create
  - mm/shuffle.c:add_to_free_area_random
  - mm/shuffle.c:__shuffle_zone
  - mm/slub.c:kmem_cache_open
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff816cd970-ffffffff816cda11: get_random_u64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
