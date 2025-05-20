# Function: <code>sort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff813f7ea0)
Location: lib/sort.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:sanitize_e820_map
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/mm/extable.c:sort_extable
  - arch/x86/mm/extable.c:sort_extable
  - kernel/range.c:clean_sort_range
  - kernel/range.c:sort_range
  - kernel/cgroup.c:pidlist_array_load
  - kernel/cgroup.c:pidlist_array_load
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff813f7ea0-ffffffff813f80cf: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff8143ed60)
Location: lib/sort.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:sanitize_e820_map
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - lib/extable.c:sort_extable
  - drivers/acpi/fan.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff8143ed60-ffffffff8143ef7e: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff8145bdb0)
Location: lib/sort.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:sanitize_e820_map
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - lib/extable.c:sort_extable
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8145bdb0-ffffffff8145bfce: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81461290)
Location: lib/sort.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:set_groups
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff81461290-ffffffff81461495: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff8148d170)
Location: lib/sort.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:SyS_setgroups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff8148d170-ffffffff8148d388: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff814c1ed0)
Location: lib/sort.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff814c1ed0-ffffffff814c20e7: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff814d65c0)
Location: lib/sort.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff814d65c0-ffffffff814d67d7: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81502460)
Location: lib/sort.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff81502460-ffffffff81502615: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff815205b0)
Location: lib/sort.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff815205b0-ffffffff815205c0: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81583770)
Location: lib/sort.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__do_sys_setgroups
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:sort_secondary
  - kernel/bpf/btf.c:btf_check_sec_info
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - lib/extable.c:sort_extable
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81583770-ffffffff81583780: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff815a05f0)
Location: lib/sort.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__do_sys_setgroups
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:sort_secondary
  - kernel/bpf/btf.c:btf_check_sec_info
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - lib/extable.c:sort_extable
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff815a05f0-ffffffff815a0600: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff815a73e0)
Location: lib/sort.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__do_sys_setgroups
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - lib/extable.c:sort_extable
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff815a73e0-ffffffff815a73f0: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81610320)
Location: lib/sort.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__do_sys_setgroups
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - lib/extable.c:sort_extable
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81610320-ffffffff81610330: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff816dc720)
Location: lib/sort.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__do_sys_setgroups
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/fprobe.c:get_ftrace_locations
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/static_call_inline.c:__static_call_init
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - lib/extable.c:sort_extable
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff816dc720-ffffffff816dc77a: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff817cc440)
Location: lib/sort.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__do_sys_setgroups
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/fprobe.c:register_fprobe_syms
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/static_call_inline.c:__static_call_init
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff817cc440-ffffffff817cc49a: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff8180a870)
Location: lib/sort.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__do_sys_setgroups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/fprobe.c:register_fprobe_syms
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/static_call_inline.c:__static_call_init
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - lib/group_cpus.c:alloc_nodes_groups
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff8180a870-ffffffff8180a8ca: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81851050)
Location: lib/sort.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/mm/numa.c:numa_fill_memblks
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__do_sys_setgroups
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/fprobe.c:get_ftrace_locations
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/static_call_inline.c:__static_call_init
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - lib/group_cpus.c:alloc_nodes_groups
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/gpu/drm/drm_blend.c:drm_atomic_helper_crtc_normalize_zpos
  - drivers/gpu/drm/drm_blend.c:drm_atomic_helper_crtc_normalize_zpos
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff81851050-ffffffff818510aa: sort (STB_GLOBAL)
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
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffff800011440f50)
Location: lib/sort.c:271
Inline: False
Direct callers:
  - arch/arm64/kernel/module-plts.c:module_frob_arch_sections
  - drivers/firmware/efi/libstub/arm-stub.c:efi_get_virtmap
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__arm64_sys_setgroups
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffff800010629a88-ffff800010629aa4: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (c07d0d48)
Location: lib/sort.c:271
Inline: False
Direct callers:
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__se_sys_setgroups
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/bpf/btf.c:btf_parse_hdr
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - lib/extable.c:sort_extable
```
**Symbols:**

```
c07d0d48-c07d0d74: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (c0000000007cb510)
Location: lib/sort.c:271
Inline: False
Direct callers:
  - arch/powerpc/kernel/module_64.c:module_frob_arch_sections
  - arch/powerpc/kernel/module_64.c:module_frob_arch_sections
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__se_sys_setgroups
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - lib/extable.c:sort_extable
```
**Symbols:**

```
c0000000007cb510-c0000000007cb524: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffe00045a676)
Location: lib/sort.c:271
Inline: False
Direct callers:
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__se_sys_setgroups
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/bpf/btf.c:btf_parse_hdr
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffe00045a676-ffffffe00045a692: sort (STB_GLOBAL)
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
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81518b90)
Location: lib/sort.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff81518b90-ffffffff81518ba0: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81508e90)
Location: lib/sort.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff81508e90-ffffffff81508ea0: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81514c20)
Location: lib/sort.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff81514c20-ffffffff81514c30: sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sort(void *base, size_t num, size_t size, int (*cmp_func)(const void *, const void *), void (*swap_func)(void *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff8152e390)
Location: lib/sort.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__update_table
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - kernel/range.c:sort_range
  - kernel/range.c:clean_sort_range
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/compat_ioctl.c:init_sys32_ioctl
  - fs/ext4/fsmap.c:ext4_getfsmap
  - security/apparmor/label.c:aa_vec_unique
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - lib/extable.c:sort_extable
```
**Symbols:**

```
ffffffff8152e390-ffffffff8152e3a0: sort (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>int (*cmp_func)(const void *, const void *)</code> ➡️ <code>cmp_func_t cmp_func</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*swap_func)(void *, void *, int)</code> ➡️ <code>swap_func_t swap_func</code>
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
