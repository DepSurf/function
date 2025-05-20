# Function: <code>get_random_long</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int get_random_long();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81566440)
Location: drivers/char/random.c:2084
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - mm/slab_common.c:cache_random_seq_create
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81566440-ffffffff815664b3: get_random_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int get_random_long();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81592ba0)
Location: drivers/char/random.c:2084
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - mm/slab_common.c:cache_random_seq_create
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - drivers/char/random.c:randomize_page
```
**Symbols:**

```
ffffffff81592ba0-ffffffff81592c13: get_random_long (STB_GLOBAL)
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
In arch/x86/mm/mmap.c (ffffffff8107279d)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff81081ce0)
Location: include/linux/random.h:52
Inline: True
```
```
In mm/slab_common.c (ffffffff811e7aa7)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In fs/binfmt_elf.c (ffffffff812b4ef4)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812b800d)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In drivers/char/random.c (ffffffff815a8a8a)
Location: include/linux/random.h:52
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff8107801d)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff810885a5)
Location: include/linux/random.h:53
Inline: True
```
```
In mm/slab_common.c (ffffffff811fdce7)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/slub.c (ffffffff81246d0a)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
```
```
In fs/binfmt_elf.c (ffffffff812d879f)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812db931)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In drivers/char/random.c (ffffffff8160f38a)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff8107aa15)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff8108c309)
Location: include/linux/random.h:53
Inline: True
```
```
In mm/slab_common.c (ffffffff8121f01d)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/slub.c (ffffffff812680a9)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/binfmt_elf.c (ffffffff81304bed)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813084df)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In drivers/char/random.c (ffffffff81649157)
Location: include/linux/random.h:53
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff81081355)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff81093d21)
Location: include/linux/random.h:54
Inline: True
```
```
In mm/slab_common.c (ffffffff8123200d)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/slub.c (ffffffff8127dbc0)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/binfmt_elf.c (ffffffff8131a355)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8131dcef)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In drivers/char/random.c (ffffffff81667457)
Location: include/linux/random.h:54
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff81084fb3)
Location: include/linux/random.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff81098453)
Location: include/linux/random.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/slab_common.c (ffffffff812424dd)
Location: include/linux/random.h:55
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81a9594b)
Location: include/linux/random.h:55
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff812999f8)
Location: include/linux/random.h:55
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In fs/binfmt_elf.c (ffffffff81341876)
Location: include/linux/random.h:55
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813451ca)
Location: include/linux/random.h:55
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In drivers/char/random.c (ffffffff8169cee7)
Location: include/linux/random.h:55
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff81085ca3)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff8109ea2d)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/util.c (ffffffff812456b7)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff812509fd)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81acd22e)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff812a98b8)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In drivers/char/random.c (ffffffff816bfc57)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff810893f5)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff810a5adb)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/util.c (ffffffff812733e7)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff8127f076)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81bc5c26)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff812de8f6)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In drivers/char/random.c (ffffffff81773b37)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff810895d5)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff810a13d2)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/util.c (ffffffff8127db47)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff81288e0a)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81c3eb8d)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff812ea702)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In lib/random32.c (ffffffff815a1046)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - lib/random32.c:prandom_reseed
  - lib/random32.c:prandom_reseed
```
```
In drivers/char/random.c (ffffffff8178eae7)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff8108a2e5)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff810a2141)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/util.c (ffffffff81282d17)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff8128e4ca)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81c30c5c)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff812f1ea0)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In lib/random32.c (ffffffff815a7ef6)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - lib/random32.c:prandom_reseed
  - lib/random32.c:prandom_reseed
```
```
In drivers/char/random.c (ffffffff817718ac)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff81099825)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff810b2f31)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/util.c (ffffffff812c0e07)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff812ce40a)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81d4f588)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff8133ae56)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In lib/random32.c (ffffffff81610e7a)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - lib/random32.c:prandom_reseed
  - lib/random32.c:prandom_reseed
```
```
In drivers/char/random.c (ffffffff817f749c)
Location: include/linux/random.h:58
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff810ac725)
Location: include/linux/random.h:47
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff810c91fb)
Location: include/linux/random.h:47
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/util.c (ffffffff8131dc4c)
Location: include/linux/random.h:47
Inline: True
Inline callers:
  - mm/util.c:randomize_page
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff8132c4ce)
Location: include/linux/random.h:47
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81f1f4e9)
Location: include/linux/random.h:47
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff813ad728)
Location: include/linux/random.h:47
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In init/main.c (ffffffff83e61371)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83e75688)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/mmap.c (ffffffff810c6795)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff810e66eb)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/util.c (ffffffff8139173c)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - mm/util.c:randomize_page
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff813a286e)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff820c8736)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff8142d998)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In init/main.c (ffffffff836817e0)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83697158)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/mmap.c (ffffffff810c9f25)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff810f205b)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/util.c (ffffffff813c410c)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - mm/util.c:randomize_page
  - mm/util.c:randomize_stack_top
```
```
In mm/shuffle.c (ffffffff8214c9b6)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff81463018)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In init/main.c (ffffffff838b0805)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/espfix_64.c (ffffffff838c6eae)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/mmap.c (ffffffff810d2385)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff810fbc9e)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/util.c (ffffffff813eecbc)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - mm/util.c:randomize_page
  - mm/util.c:randomize_stack_top
```
```
In mm/shuffle.c (ffffffff8222f4c6)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff8145f268)
Location: include/linux/random.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In arch/arm64/kvm/va_layout.c (ffff8000100cf8d0)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - arch/arm64/kvm/va_layout.c:compute_layout
```
```
In kernel/fork.c (ffff8000100f312c)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/util.c (ffff8000102d8a98)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/util.c:arch_mmap_rnd
  - mm/util.c:arch_mmap_rnd
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffff8000102e7b30)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffff800010da032c)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffff80001034b3c4)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In drivers/char/random.c (ffff8000108b19b4)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In kernel/fork.c (c0351dd8)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/util.c (c04ffe2c)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/util.c:arch_pick_mmap_layout
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (c050bc38)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (c15be2a8)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (c054f3ac)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In drivers/char/random.c (c09ac910)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In init/main.c (c00000000134419c)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/powerpc/kernel/process.c (c000000000022f10)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:arch_randomize_brk
  - arch/powerpc/kernel/process.c:arch_randomize_brk
```
```
In arch/powerpc/kernel/smp.c (c00000000005642c)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:start_secondary
```
```
In arch/powerpc/mm/mmap.c (c0000000000887b8)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - arch/powerpc/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (c000000000139404)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/util.c (c0000000003986c0)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (c0000000003a99b0)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (c000000000eed000)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (c00000000042a988)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In drivers/char/random.c (c00000000094a760)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In mm/util.c (ffffffe0001f30d8)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/util.c:arch_pick_mmap_layout
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffe0001fd63e)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffe000047686)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffe00023ca14)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In drivers/char/random.c (ffffffe00056419a)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff81084ca3)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff8109834d)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/util.c (ffffffff8123dd07)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff8124904d)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81a6c09e)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff812a1e98)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In drivers/char/random.c (ffffffff816856a7)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff81073973)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff81086d93)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/util.c (ffffffff81230d07)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff8123bffd)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81a285e5)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff81293978)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In drivers/char/random.c (ffffffff81663347)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff81084c53)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff810982fd)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/util.c (ffffffff8123baa7)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff81246ded)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81ad84ae)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff8129fca8)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In drivers/char/random.c (ffffffff816b3a97)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
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
In arch/x86/mm/mmap.c (ffffffff81086da3)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In kernel/fork.c (ffffffff8109fef4)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/util.c (ffffffff8124b1b7)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In mm/slab_common.c (ffffffff8125661d)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
```
In mm/shuffle.c (ffffffff81ae4969)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/slub.c (ffffffff812afde8)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In drivers/char/random.c (ffffffff816cdff7)
Location: include/linux/random.h:56
Inline: True
Inline callers:
  - drivers/char/random.c:randomize_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
