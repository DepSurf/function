# Function: <code>get_option</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff813e8f50)
Location: lib/cmdline.c:52
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/cpu/common.c:setup_show_msr
  - arch/x86/kernel/cpu/common.c:setup_disablecpuid
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:nrcpus
  - kernel/smp.c:maxcpus
  - mm/slub.c:setup_slub_min_order
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_objects
  - lib/cmdline.c:get_options
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/char/hpet.c:hpet_mmap_enable
```
**Symbols:**

```
ffffffff813e8f50-ffffffff813e8fbe: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8142f150)
Location: lib/cmdline.c:52
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/cpu/common.c:setup_disablecpuid
  - arch/x86/kernel/cpu/common.c:setup_show_msr
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - lib/cmdline.c:get_options
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
```
**Symbols:**

```
ffffffff8142f150-ffffffff8142f1be: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8144b2c0)
Location: lib/cmdline.c:52
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/cpu/common.c:setup_disablecpuid
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - lib/cmdline.c:get_options
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
```
**Symbols:**

```
ffffffff8144b2c0-ffffffff8144b32e: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff818eb800)
Location: lib/cmdline.c:53
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/cpu/common.c:setup_disablecpuid
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff818eb800-ffffffff818eb869: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff819717c0)
Location: lib/cmdline.c:53
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff819717c0-ffffffff81971829: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff819cdb90)
Location: lib/cmdline.c:53
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff819cdb90-ffffffff819cdbf9: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a07020)
Location: lib/cmdline.c:53
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff81a07020-ffffffff81a07089: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a76990)
Location: lib/cmdline.c:50
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff81a76990-ffffffff81a769f9: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81aadda0)
Location: lib/cmdline.c:50
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff81aadda0-ffffffff81aade09: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff815e7b9c)
Location: lib/cmdline.c:50
Inline: True
Inline callers:
  - lib/cmdline.c:get_options
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
```
**Symbols:**

```
ffffffff815e7a40-ffffffff815e7aa9: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8160cbb0)
Location: lib/cmdline.c:56
Inline: False
Direct callers:
  - init/main.c:loglevel
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - lib/cmdline.c:get_options
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
```
**Symbols:**

```
ffffffff8160cbb0-ffffffff8160cc39: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff815f0270)
Location: lib/cmdline.c:56
Inline: False
Direct callers:
  - init/main.c:loglevel
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - lib/cmdline.c:get_options
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
```
**Symbols:**

```
ffffffff815f0270-ffffffff815f02f9: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8165d350)
Location: lib/cmdline.c:56
Inline: False
Direct callers:
  - init/main.c:loglevel
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - lib/cmdline.c:get_options
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
```
**Symbols:**

```
ffffffff8165d350-ffffffff8165d3d9: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81776810)
Location: lib/cmdline.c:56
Inline: False
Direct callers:
  - init/main.c:loglevel
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - lib/cmdline.c:get_options
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
```
**Symbols:**

```
ffffffff81776810-ffffffff817768ad: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8201f280)
Location: lib/cmdline.c:56
Inline: False
Direct callers:
  - init/main.c:loglevel
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_pci
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff8201f280-ffffffff8201f31d: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8209f290)
Location: lib/cmdline.c:56
Inline: False
Direct callers:
  - init/main.c:loglevel
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_pci
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff8209f290-ffffffff8209f32d: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff82177290)
Location: lib/cmdline.c:56
Inline: False
Direct callers:
  - init/main.c:loglevel
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_pci
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - drivers/md/md-autodetect.c:md_setup
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff82177290-ffffffff8217732d: get_option (STB_GLOBAL)
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
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffff800010d83fe0)
Location: lib/cmdline.c:50
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffff800010d83fe0-ffff800010d8407c: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (c0e7f4c0)
Location: lib/cmdline.c:50
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/arm/plat-omap/dma.c:omap_dma_cmdline_reserve_ch
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - lib/cmdline.c:get_options
```
**Symbols:**

```
c0e7f4c0-c0e7f540: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (c000000000ec2f90)
Location: lib/cmdline.c:50
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/powerpc/kernel/rtasd.c:surveillance_setup
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - lib/cmdline.c:get_options
```
**Symbols:**

```
c000000000ec2f90-c000000000ec3098: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffe0008ae6b8)
Location: lib/cmdline.c:50
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffe0008ae6b8-ffffffe0008ae722: get_option (STB_GLOBAL)
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
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a4cbf0)
Location: lib/cmdline.c:50
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff81a4cbf0-ffffffff81a4cc59: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a09d20)
Location: lib/cmdline.c:50
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff81a09d20-ffffffff81a09d89: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81ab8fe0)
Location: lib/cmdline.c:50
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff81ab8fe0-ffffffff81ab9049: get_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_option(char **str, int *pint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81ac5430)
Location: lib/cmdline.c:50
Inline: False
Direct callers:
  - init/main.c:loglevel
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - init/do_mounts_md.c:md_setup
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
  - arch/x86/kernel/smpboot.c:_setup_possible_cpus
  - arch/x86/kernel/smpboot.c:cpu_init_udelay
  - arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid
  - arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand
  - arch/x86/kernel/apic/vector.c:setup_show_lapic
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:reserve_setup
  - kernel/signal.c:setup_print_fatal_signals
  - kernel/printk/printk.c:boot_delay_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/profile.c:profile_setup
  - kernel/time/tick-sched.c:skew_tick
  - kernel/smp.c:maxcpus
  - kernel/smp.c:nrcpus
  - kernel/watchdog.c:watchdog_thresh_setup
  - mm/slub.c:setup_slub_memcg_sysfs
  - mm/slub.c:setup_slub_min_objects
  - mm/slub.c:setup_slub_max_order
  - mm/slub.c:setup_slub_min_order
  - drivers/acpi/pci_link.c:acpi_irq_penalty_update
  - drivers/pnp/resource.c:pnp_setup_reserve_mem
  - drivers/pnp/resource.c:pnp_setup_reserve_io
  - drivers/pnp/resource.c:pnp_setup_reserve_dma
  - drivers/pnp/resource.c:pnp_setup_reserve_irq
  - drivers/char/hpet.c:hpet_mmap_enable
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff81ac5430-ffffffff81ac5499: get_option (STB_GLOBAL)
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
