# Function: <code>atomic_notifier_chain_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a15f0)
Location: kernel/notifier.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:idle_notifier_unregister
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
```
**Symbols:**

```
ffffffff810a15f0-ffffffff810a1668: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4d10)
Location: kernel/notifier.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:idle_notifier_unregister
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
```
**Symbols:**

```
ffffffff810a4d10-ffffffff810a4d88: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aa970)
Location: kernel/notifier.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/ipv4/fib_trie.c:unregister_fib_notifier
  - net/ipv4/fib_trie.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
```
**Symbols:**

```
ffffffff810aa970-ffffffff810aa9e8: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a74f0)
Location: kernel/notifier.c:143
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - security/security.c:unregister_lsm_notifier
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/ipv4/fib_notifier.c:unregister_fib_notifier
  - net/ipv4/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810a74f0-ffffffff810a7568: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810adc70)
Location: kernel/notifier.c:143
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - security/security.c:unregister_lsm_notifier
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810adc70-ffffffff810adce8: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4ae0)
Location: kernel/notifier.c:143
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - security/security.c:unregister_lsm_notifier
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810b4ae0-ffffffff810b4b58: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bdc30)
Location: kernel/notifier.c:143
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - security/security.c:unregister_lsm_notifier
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810bdc30-ffffffff810bdca8: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3cd0)
Location: kernel/notifier.c:145
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810c3cd0-ffffffff810c3d42: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccde0)
Location: kernel/notifier.c:145
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810ccde0-ffffffff810cce52: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6d25)
Location: kernel/notifier.c:133
Inline: True
Inline callers:
  - kernel/notifier.c:unregister_die_notifier
Direct callers:
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/gpio/gpiolib.c:gpio_chrdev_release
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/remoteproc/remoteproc_core.c:rproc_exit_panic
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810d6810-ffffffff810d6882: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d17bf)
Location: kernel/notifier.c:161
Inline: True
Inline callers:
  - kernel/notifier.c:unregister_die_notifier
Direct callers:
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/remoteproc/remoteproc_core.c:rproc_exit_panic
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810d13b0-ffffffff810d1422: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d339f)
Location: kernel/notifier.c:161
Inline: True
Inline callers:
  - kernel/notifier.c:unregister_die_notifier
Direct callers:
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/remoteproc/remoteproc_core.c:rproc_exit_panic
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810d2f90-ffffffff810d3002: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e630f)
Location: kernel/notifier.c:161
Inline: True
Inline callers:
  - kernel/notifier.c:unregister_die_notifier
Direct callers:
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/remoteproc/remoteproc_core.c:rproc_exit_panic
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810e60d0-ffffffff810e6142: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8110033d)
Location: kernel/notifier.c:188
Inline: True
Inline callers:
  - kernel/notifier.c:unregister_die_notifier
Direct callers:
  - kernel/reboot.c:unregister_sys_off_handler
  - kernel/reboot.c:unregister_restart_handler
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/remoteproc/remoteproc_core.c:rproc_exit_panic
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810fff60-ffffffff810fffd7: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8112520d)
Location: kernel/notifier.c:188
Inline: True
Inline callers:
  - kernel/notifier.c:unregister_die_notifier
Direct callers:
  - kernel/reboot.c:unregister_sys_off_handler
  - kernel/reboot.c:unregister_restart_handler
  - drivers/acpi/apei/ghes.c:ghes_unregister_report_chain
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff81124dc0-ffffffff81124e37: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132f4f)
Location: kernel/notifier.c:194
Inline: True
Inline callers:
  - kernel/notifier.c:unregister_die_notifier
Direct callers:
  - kernel/reboot.c:unregister_sys_off_handler
  - kernel/reboot.c:unregister_restart_handler
  - drivers/acpi/apei/ghes.c:ghes_unregister_report_chain
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd/iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
  - drivers/hv/hv_common.c:hv_common_free
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff81132c30-ffffffff81132c7d: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113de5f)
Location: kernel/notifier.c:194
Inline: True
Inline callers:
  - kernel/notifier.c:unregister_die_notifier
Direct callers:
  - kernel/reboot.c:unregister_sys_off_handler
  - kernel/reboot.c:unregister_restart_handler
  - drivers/acpi/apei/ghes.c:ghes_unregister_report_chain
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
  - drivers/hv/hv_common.c:hv_common_free
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff8113db40-ffffffff8113db8d: atomic_notifier_chain_unregister (STB_GLOBAL)
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012c188)
Location: kernel/notifier.c:145
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - kernel/cpu_pm.c:cpu_pm_unregister_notifier
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_unregister_notifier
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_unregister_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffff80001012c188-ffff80001012c274: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037c0d8)
Location: kernel/notifier.c:145
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - kernel/cpu_pm.c:cpu_pm_unregister_notifier
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_unregister_notifier
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_unregister_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
c037c0d8-c037c164: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174860)
Location: kernel/notifier.c:145
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal.c:opal_message_notifier_unregister
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
c000000000174860-c00000000017494c: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e08d4)
Location: kernel/notifier.c:145
Inline: False
Direct callers:
  - arch/riscv/mm/sifive_l2_cache.c:unregister_sifive_l2_error_notifier
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffe0000e08d4-ffffffe0000e0946: atomic_notifier_chain_unregister (STB_GLOBAL)
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
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c7160)
Location: kernel/notifier.c:145
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810c7160-ffffffff810c71d2: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5980)
Location: kernel/notifier.c:145
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/hv/vmbus_drv.c:vmbus_exit
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810b5980-ffffffff810b59f2: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c66b0)
Location: kernel/notifier.c:145
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810c66b0-ffffffff810c6722: atomic_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int atomic_notifier_chain_unregister(struct atomic_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cea60)
Location: kernel/notifier.c:145
Inline: False
Direct callers:
  - kernel/notifier.c:unregister_die_notifier
  - kernel/reboot.c:unregister_restart_handler
  - kernel/profile.c:task_handoff_unregister
  - drivers/tty/vt/keyboard.c:unregister_keyboard_notifier
  - drivers/tty/vt/vt.c:unregister_vt_notifier
  - drivers/iommu/amd_iommu.c:amd_iommu_unregister_ppr_notifier
  - drivers/base/memory.c:unregister_memory_isolate_notifier
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - net/core/netevent.c:unregister_netevent_notifier
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_notifier
  - net/dcb/dcbevent.c:unregister_dcbevent_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810cea60-ffffffff810cead2: atomic_notifier_chain_unregister (STB_GLOBAL)
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
