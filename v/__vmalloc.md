# Function: <code>__vmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cf2e0)
Location: mm/vmalloc.c:1719
Inline: False
Direct callers:
  - kernel/module.c:SYSC_init_module
  - kernel/bpf/core.c:bpf_prog_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvmalloc
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff811cf2e0-ffffffff811cf32c: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ec460)
Location: mm/vmalloc.c:1740
Inline: False
Direct callers:
  - kernel/module.c:SYSC_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/file.c:alloc_fdmem
  - fs/ext4/super.c:ext4_kvmalloc
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff811ec460-ffffffff811ec4ac: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd700)
Location: mm/vmalloc.c:1753
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:SYSC_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/file.c:alloc_fdmem
  - fs/ext4/super.c:ext4_kvmalloc
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff811fd700-ffffffff811fd74c: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812083f0)
Location: mm/vmalloc.c:1816
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:SYSC_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffff812083f0-ffffffff81208426: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812214a0)
Location: mm/vmalloc.c:1808
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:SYSC_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffff812214a0-ffffffff812214d6: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81243360)
Location: mm/vmalloc.c:1795
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffff81243360-ffffffff81243396: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81257a40)
Location: mm/vmalloc.c:1801
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffff81257a40-ffffffff81257a76: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126a7b0)
Location: mm/vmalloc.c:2549
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffff8126a7b0-ffffffff8126a7e6: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812796c0)
Location: mm/vmalloc.c:2557
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffff812796c0-ffffffff812796f6: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac6c0)
Location: mm/vmalloc.c:2600
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff812ac6c0-ffffffff812ac6e0: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7bf0)
Location: mm/vmalloc.c:2633
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff812b7bf0-ffffffff812b7c10: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bd150)
Location: mm/vmalloc.c:2980
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_res_table_info_init
```
**Symbols:**

```
ffffffff812bd150-ffffffff812bd170: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff8c0)
Location: mm/vmalloc.c:3086
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff812ff8c0-ffffffff812ff8e0: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813671e0)
Location: mm/vmalloc.c:3243
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - kernel/module/main.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/util.c:vcalloc
  - mm/util.c:__vcalloc
  - mm/util.c:vmalloc_array
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff813671e0-ffffffff8136720f: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e30c0)
Location: mm/vmalloc.c:3305
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - kernel/module/main.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/util.c:vcalloc
  - mm/util.c:__vcalloc
  - mm/util.c:vmalloc_array
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff813e30c0-ffffffff813e30ef: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81417d20)
Location: mm/vmalloc.c:3398
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - kernel/module/main.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/util.c:vcalloc
  - mm/util.c:__vcalloc
  - mm/util.c:vmalloc_array
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff81417d20-ffffffff81417d4f: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81444870)
Location: mm/vmalloc.c:3398
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - kernel/module/main.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/util.c:vcalloc
  - mm/util.c:__vcalloc
  - mm/util.c:vmalloc_array
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
**Symbols:**

```
ffffffff81444870-ffffffff8144489f: __vmalloc (STB_GLOBAL)
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
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff800010310238)
Location: mm/vmalloc.c:2557
Inline: False
Direct callers:
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffff800010310238-ffff8000103102ac: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052c610)
Location: mm/vmalloc.c:2557
Inline: False
Direct callers:
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__se_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
  - sound/core/pcm_memory.c:_snd_pcm_lib_alloc_vmalloc_buffer
```
**Symbols:**

```
c052c610-c052c66c: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e1510)
Location: mm/vmalloc.c:2557
Inline: False
Direct callers:
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
c0000000003e1510-c0000000003e1570: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe0002185e8)
Location: mm/vmalloc.c:2557
Inline: False
Direct callers:
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffe0002185e8-ffffffe00021863a: __vmalloc (STB_GLOBAL)
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
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81271d10)
Location: mm/vmalloc.c:2557
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffff81271d10-ffffffff81271d46: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263c80)
Location: mm/vmalloc.c:2557
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffff81263c80-ffffffff81263cb6: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126fab0)
Location: mm/vmalloc.c:2557
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffff8126fab0-ffffffff8126fae6: __vmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f4a0)
Location: mm/vmalloc.c:2557
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - kernel/groups.c:groups_alloc
  - kernel/module.c:__do_sys_init_module
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - mm/page_alloc.c:alloc_large_system_hash
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
```
**Symbols:**

```
ffffffff8127f4a0-ffffffff8127f4d6: __vmalloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pgprot_t prot</code>
</li>
</ul>
</details>
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
