# Function: <code>get_mem_cgroup_from_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fadf0)
Location: mm/memcontrol.c:831
Inline: False
Direct callers:
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:__memcg_kmem_get_cache
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
**Symbols:**

```
ffffffff811fadf0-ffffffff811faea2: get_mem_cgroup_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8121e460)
Location: mm/memcontrol.c:724
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:task_in_mem_cgroup
```
**Symbols:**

```
ffffffff8121e460-ffffffff8121e4f7: get_mem_cgroup_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81230a50)
Location: mm/memcontrol.c:726
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:task_in_mem_cgroup
```
**Symbols:**

```
ffffffff81230a50-ffffffff81230ae4: get_mem_cgroup_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123c3b0)
Location: mm/memcontrol.c:696
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:task_in_mem_cgroup
```
**Symbols:**

```
ffffffff8123c3b0-ffffffff8123c43f: get_mem_cgroup_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125ba40)
Location: mm/memcontrol.c:710
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:task_in_mem_cgroup
```
**Symbols:**

```
ffffffff8125ba40-ffffffff8125bb11: get_mem_cgroup_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8127f630)
Location: mm/memcontrol.c:681
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:task_in_mem_cgroup
```
**Symbols:**

```
ffffffff8127f630-ffffffff8127f6f6: get_mem_cgroup_from_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81294b10)
Location: mm/memcontrol.c:827
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:task_in_mem_cgroup
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff81294b10-ffffffff81294ba9: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b04d0)
Location: mm/memcontrol.c:944
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff812b04d0-ffffffff812b0555: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c1b00)
Location: mm/memcontrol.c:955
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff812c1b00-ffffffff812c1b7e: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f7480)
Location: mm/memcontrol.c:916
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
**Symbols:**

```
ffffffff812f7480-ffffffff812f74fe: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81302980)
Location: mm/memcontrol.c:1019
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - mm/mmap_lock.c:get_mm_memcg_path
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
**Symbols:**

```
ffffffff81302980-ffffffff81302a36: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81308f90)
Location: mm/memcontrol.c:897
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - mm/mmap_lock.c:get_mm_memcg_path
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
**Symbols:**

```
ffffffff81308f90-ffffffff81309046: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81352da0)
Location: mm/memcontrol.c:948
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - mm/mmap_lock.c:get_mm_memcg_path
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
**Symbols:**

```
ffffffff81352da0-ffffffff81352ed2: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cdb00)
Location: mm/memcontrol.c:930
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - kernel/bpf/syscall.c:map_create
  - mm/mmap_lock.c:get_mm_memcg_path
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
**Symbols:**

```
ffffffff813cdb00-ffffffff813cdc36: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814521b0)
Location: mm/memcontrol.c:1010
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - mm/vmscan.c:lru_gen_add_mm
  - mm/mmap_lock.c:get_mm_memcg_path
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
**Symbols:**

```
ffffffff814521b0-ffffffff814522e6: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81487b00)
Location: mm/memcontrol.c:1035
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - mm/vmscan.c:lru_gen_add_mm
  - mm/mmap_lock.c:get_mm_memcg_path
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
**Symbols:**

```
ffffffff81487b00-ffffffff81487c36: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b7a10)
Location: mm/memcontrol.c:1078
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - mm/vmscan.c:lru_gen_add_mm
  - mm/mmap_lock.c:get_mm_memcg_path
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
**Symbols:**

```
ffffffff814b7a10-ffffffff814b7b46: get_mem_cgroup_from_mm (STB_GLOBAL)
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
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010366828)
Location: mm/memcontrol.c:955
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
```
**Symbols:**

```
ffff800010366828-ffff800010366930: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (c055c1c4)
Location: mm/memcontrol.c:955
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
**Symbols:**

```
c05566ec-c05567bc: get_mem_cgroup_from_mm.part.0 (STB_LOCAL)
c05567bc-c05567f4: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000450be0)
Location: mm/memcontrol.c:955
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
**Symbols:**

```
c000000000450be0-c000000000450cf0: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffe00024836c)
Location: mm/memcontrol.c:955
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
**Symbols:**

```
ffffffe00024316e-ffffffe000243214: get_mem_cgroup_from_mm.part.0 (STB_LOCAL)
ffffffe000243214-ffffffe000243256: get_mem_cgroup_from_mm (STB_GLOBAL)
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
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ba0e0)
Location: mm/memcontrol.c:955
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff812ba0e0-ffffffff812ba15e: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ab370)
Location: mm/memcontrol.c:955
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff812ab370-ffffffff812ab3ee: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b7ef0)
Location: mm/memcontrol.c:955
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff812b7ef0-ffffffff812b7f6e: get_mem_cgroup_from_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c87e0)
Location: mm/memcontrol.c:955
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff812c87e0-ffffffff812c8897: get_mem_cgroup_from_mm (STB_GLOBAL)
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
