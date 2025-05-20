# Function: <code>atomic_notifier_chain_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a1430)
Location: kernel/notifier.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - arch/x86/kernel/process.c:idle_notifier_register
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/update.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:trace_init
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/power_supply_core.c:power_supply_reg_notifier
  - net/core/netevent.c:register_netevent_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
```
**Symbols:**

```
ffffffff810a1430-ffffffff810a148c: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4b50)
Location: kernel/notifier.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - arch/x86/kernel/process.c:idle_notifier_register
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/update.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:trace_init
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
```
**Symbols:**

```
ffffffff810a4b50-ffffffff810a4bac: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aa7b0)
Location: kernel/notifier.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_register_decode_chain
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/update.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:trace_init
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/ipv4/fib_trie.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
```
**Symbols:**

```
ffffffff810aa7b0-ffffffff810aa80c: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7330)
Location: kernel/notifier.c:121
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/update.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:early_trace_init
  - security/security.c:register_lsm_notifier
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/ipv4/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810a7330-ffffffff810a738c: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810adab0)
Location: kernel/notifier.c:121
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/update.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:early_trace_init
  - security/security.c:register_lsm_notifier
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810adab0-ffffffff810adb0c: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4920)
Location: kernel/notifier.c:121
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/update.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:early_trace_init
  - security/security.c:register_lsm_notifier
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810b4920-ffffffff810b497c: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bda70)
Location: kernel/notifier.c:121
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/update.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:early_trace_init
  - security/security.c:register_lsm_notifier
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810bda70-ffffffff810bdacc: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3c70)
Location: kernel/notifier.c:123
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810c3c70-ffffffff810c3cb3: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccd80)
Location: kernel/notifier.c:123
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810ccd80-ffffffff810ccdc3: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6cd5)
Location: kernel/notifier.c:111
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810d6980-ffffffff810d69c3: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1770)
Location: kernel/notifier.c:139
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810d1480-ffffffff810d14c3: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3350)
Location: kernel/notifier.c:139
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810d3060-ffffffff810d30a3: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e6455)
Location: kernel/notifier.c:139
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810e63d0-ffffffff810e6445: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8110066f)
Location: kernel/notifier.c:143
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/reboot.c:register_sys_off_handler
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/hung_task.c:hung_task_init
  - mm/kfence/core.c:kfence_init_enable
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff81100530-ffffffff811005bb: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8112559f)
Location: kernel/notifier.c:143
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/reboot.c:register_sys_off_handler
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/hung_task.c:hung_task_init
  - mm/kfence/core.c:kfence_init_enable
  - drivers/acpi/apei/ghes.c:ghes_register_report_chain
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff81125440-ffffffff811254cb: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132edf)
Location: kernel/notifier.c:149
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/reboot.c:register_sys_off_handler
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/hung_task.c:hung_task_init
  - mm/kfence/core.c:kfence_init_enable
  - drivers/acpi/apei/ghes.c:ghes_register_report_chain
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_register_ppr_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - drivers/hv/hv_common.c:hv_common_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff811324f0-ffffffff8113253c: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113ddef)
Location: kernel/notifier.c:149
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/reboot.c:register_sys_off_handler
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/hung_task.c:hung_task_init
  - mm/kfence/core.c:kfence_init_enable
  - drivers/acpi/apei/ghes.c:ghes_register_report_chain
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_init
  - drivers/hv/hv_common.c:hv_common_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff8113d400-ffffffff8113d44c: atomic_notifier_chain_register (STB_GLOBAL)
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
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012c338)
Location: kernel/notifier.c:123
Inline: False
Direct callers:
  - arch/arm64/kernel/setup.c:register_kernel_offset_dumper
  - arch/arm64/kernel/cpufeature.c:register_cpu_hwcaps_dumper
  - arch/arm64/mm/init.c:register_mem_limit_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/cpu_pm.c:cpu_pm_register_notifier
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_register_notifier
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_register_notifier
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffff80001012c338-ffff80001012c3e0: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037c070)
Location: kernel/notifier.c:123
Inline: False
Direct callers:
  - arch/arm/vfp/vfpmodule.c:vfp_init
  - arch/arm/kernel/thumbee.c:thumbee_init
  - arch/arm/kernel/pj4-cp0.c:pj4_cp0_init
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/cpu_pm.c:cpu_pm_register_notifier
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_register_notifier
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_register_notifier
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
c037c070-c037c0bc: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c0000000001747c0)
Location: kernel/notifier.c:123
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:setup_panic
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
c0000000001747c0-c000000000174838: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e084e)
Location: kernel/notifier.c:123
Inline: False
Direct callers:
  - arch/riscv/mm/sifive_l2_cache.c:register_sifive_l2_error_notifier
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffe0000e084e-ffffffe0000e08a2: atomic_notifier_chain_register (STB_GLOBAL)
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
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c7100)
Location: kernel/notifier.c:123
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810c7100-ffffffff810c7143: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5920)
Location: kernel/notifier.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810b5920-ffffffff810b5963: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6650)
Location: kernel/notifier.c:123
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810c6650-ffffffff810c6693: atomic_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int atomic_notifier_chain_register(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cea00)
Location: kernel/notifier.c:123
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_panic_handler_init
  - arch/x86/kernel/setup.c:register_kernel_offset_dumper
  - kernel/notifier.c:register_die_notifier
  - kernel/reboot.c:register_restart_handler
  - kernel/rcu/tree.c:check_cpu_stall_init
  - kernel/profile.c:task_handoff_register
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - drivers/tty/vt/keyboard.c:register_keyboard_notifier
  - drivers/tty/vt/vt.c:register_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_register_ppr_notifier
  - drivers/base/memory.c:register_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/leds/trigger/ledtrig-panic.c:ledtrig_panic_init
  - net/core/netevent.c:register_netevent_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_notifier
  - net/dcb/dcbevent.c:register_dcbevent_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810cea00-ffffffff810cea43: atomic_notifier_chain_register (STB_GLOBAL)
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
