# Function: <code>atomic_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a14b0)
Location: kernel/notifier.c:190
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - arch/x86/kernel/process.c:exit_idle
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/kernel/process.c:arch_cpu_idle_exit
  - arch/x86/kernel/cpu/mcheck/mce.c:print_mce
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
  - drivers/power/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
```
**Symbols:**

```
ffffffff810a14b0-ffffffff810a14cc: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4cbc)
Location: kernel/notifier.c:190
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - arch/x86/kernel/process.c:arch_cpu_idle_exit
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/kernel/process.c:exit_idle
  - arch/x86/kernel/cpu/mcheck/mce.c:print_mce
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/power/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
```
**Symbols:**

```
ffffffff810a4bd0-ffffffff810a4bec: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aa91c)
Location: kernel/notifier.c:190
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
```
**Symbols:**

```
ffffffff810aa830-ffffffff810aa84c: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a749c)
Location: kernel/notifier.c:190
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - security/security.c:call_lsm_notifier
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/ipv4/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810a73b0-ffffffff810a73cc: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810adc1c)
Location: kernel/notifier.c:190
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - security/security.c:call_lsm_notifier
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810adb30-ffffffff810adb4c: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4ac0)
Location: kernel/notifier.c:190
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - security/security.c:call_lsm_notifier
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810b49a0-ffffffff810b49bc: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bdc10)
Location: kernel/notifier.c:190
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - security/security.c:call_lsm_notifier
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810bdaf0-ffffffff810bdb0c: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3bbb)
Location: kernel/notifier.c:192
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810c3af0-ffffffff810c3b0c: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccccb)
Location: kernel/notifier.c:192
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810ccc00-ffffffff810ccc1c: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6e90)
Location: kernel/notifier.c:180
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv4/nexthop.c:__remove_nexthop_fib
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810d6e00-ffffffff810d6e5c: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1930)
Location: kernel/notifier.c:211
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810d1890-ffffffff810d18ff: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3510)
Location: kernel/notifier.c:211
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810d3470-ffffffff810d34df: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e66a0)
Location: kernel/notifier.c:192
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810e6600-ffffffff810e666f: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100733)
Location: kernel/notifier.c:219
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:do_kernel_restart
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff811004a0-ffffffff81100521: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125673)
Location: kernel/notifier.c:219
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:do_kernel_restart
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff811253a0-ffffffff81125421: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132ade)
Location: kernel/notifier.c:225
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:do_kernel_restart
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd/iommu.c:iommu_poll_ppr_log
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff81132930-ffffffff81132982: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113d9ee)
Location: kernel/notifier.c:225
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:do_kernel_restart
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff8113d840-ffffffff8113d892: atomic_notifier_call_chain (STB_GLOBAL)
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
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012bb3c)
Location: kernel/notifier.c:192
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_work_handler
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffff80001012b998-ffff80001012b9e4: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037bf7c)
Location: kernel/notifier.c:192
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - arch/arm/kernel/process.c:copy_thread_tls
  - arch/arm/kernel/process.c:flush_thread
  - arch/arm/kernel/process.c:exit_thread
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_work_handler
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
c037be40-c037be74: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174684)
Location: kernel/notifier.c:192
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - arch/powerpc/platforms/powernv/opal.c:opal_message_notify
  - arch/powerpc/platforms/pseries/io_event_irq.c:ioei_interrupt
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
c000000000174570-c0000000001745ac: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e0e6e)
Location: kernel/notifier.c:192
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffe0000e06a6-ffffffe0000e06e6: atomic_notifier_call_chain (STB_GLOBAL)
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
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c704b)
Location: kernel/notifier.c:192
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810c6f80-ffffffff810c6f9c: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b586b)
Location: kernel/notifier.c:192
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810b57a0-ffffffff810b57bc: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c659b)
Location: kernel/notifier.c:192
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
Direct callers:
  - kernel/panic.c:panic
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810c64d0-ffffffff810c64ec: atomic_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int atomic_notifier_call_chain(struct atomic_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ceb60)
Location: kernel/notifier.c:192
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/notifier.c:notify_die
  - kernel/reboot.c:do_kernel_restart
  - kernel/profile.c:profile_handoff_task
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/vt.c:vcs_scr_updated
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:lf
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/memory.c:memory_isolate_notify
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - net/core/netevent.c:call_netevent_notifiers
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_notifier_call_chain
  - net/dcb/dcbevent.c:call_dcbevent_notifiers
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810ceb60-ffffffff810ceba5: atomic_notifier_call_chain (STB_GLOBAL)
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
