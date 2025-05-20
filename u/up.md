# Function: <code>up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810c9d80)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:suspend_console
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810c9d80-ffffffff810c9dc8: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810ce700)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:suspend_console
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810ce700-ffffffff810ce74c: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810d5340)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:suspend_console
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810d5340-ffffffff810d538c: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810d4310)
Location: kernel/locking/semaphore.c:179
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810d4310-ffffffff810d435c: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810dc270)
Location: kernel/locking/semaphore.c:179
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810dc270-ffffffff810dc2bc: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810e48b0)
Location: kernel/locking/semaphore.c:179
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810e48b0-ffffffff810e48fc: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810efea0)
Location: kernel/locking/semaphore.c:179
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810efea0-ffffffff810efeec: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810f7900)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810f7900-ffffffff810f7961: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff81103730)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call_irqsave
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81103730-ffffffff81103791: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8110e290)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
  - kernel/printk/printk.c:console_unlock
  - kernel/seccomp.c:seccomp_notify_recv
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking
  - drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking
  - drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff8110e290-ffffffff8110e2ed: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8110b4f0)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
  - kernel/printk/printk.c:console_unlock
  - kernel/seccomp.c:seccomp_notify_recv
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:clone_endio
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking
  - drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking
  - drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff8110b4f0-ffffffff8110b54d: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8110d310)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/seccomp.c:seccomp_notify_recv
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:clone_endio
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff8110d310-ffffffff8110d36d: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8112cb40)
Location: kernel/locking/semaphore.c:182
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
  - kernel/printk/printk.c:console_unlock
  - kernel/seccomp.c:seccomp_notify_recv
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:clone_endio
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff8112cb40-ffffffff8112cb9d: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8114dda0)
Location: kernel/locking/semaphore.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
  - kernel/seccomp.c:seccomp_notify_recv
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:clone_endio
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff8114dda0-ffffffff8114de0f: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff820d02c0)
Location: kernel/locking/semaphore.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
  - kernel/seccomp.c:seccomp_notify_recv
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:clone_endio
  - drivers/firmware/efi/vars.c:efivar_trylock
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivars_register
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff820d02c0-ffffffff820d032f: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff82154650)
Location: kernel/locking/semaphore.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
  - kernel/module/kmod.c:__request_module
  - kernel/seccomp.c:seccomp_notify_recv
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:clone_endio
  - drivers/firmware/efi/vars.c:efivar_trylock
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivars_register
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff82154650-ffffffff821546bf: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff82237490)
Location: kernel/locking/semaphore.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
  - kernel/module/kmod.c:__request_module
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:clone_endio
  - drivers/firmware/efi/vars.c:efivar_trylock
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivars_register
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_acpi_prm_handler
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff82237490-ffffffff822374ff: up (STB_GLOBAL)
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
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffff800010168948)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffff800010168948-ffff800010168a10: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (c03b507c)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - arch/arm/mach-vexpress/spc.c:spc_set_rate
  - arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
c03b507c-c03b50ec: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (c0000000001c0800)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_release_token
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_get_token_interruptible
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
c0000000001c0800-c0000000001c08a0: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffe00010a656)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffe00010a656-ffffffe00010a6c2: up (STB_GLOBAL)
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
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810fca40)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810fca40-ffffffff810fcaa1: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810ecc50)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/hv/vmbus_drv.c:vmbus_free_mmio
  - drivers/hv/vmbus_drv.c:vmbus_allocate_mmio
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810ecc50-ffffffff810eccb1: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810f9c00)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810f9c00-ffffffff810f9c61: up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void up(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff81104d70)
Location: kernel/locking/semaphore.c:178
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call_irqsave
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/acpi/osl.c:acpi_os_signal_semaphore
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - net/core/netpoll.c:netpoll_poll_enable
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81104d70-ffffffff81104dd1: up (STB_GLOBAL)
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
