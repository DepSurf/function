# Function: <code>down_interruptible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810c9e30)
Location: kernel/locking/semaphore.c:75
Inline: False
```
**Symbols:**

```
ffffffff810c9e30-ffffffff810c9e84: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810ce7b0)
Location: kernel/locking/semaphore.c:75
Inline: False
```
**Symbols:**

```
ffffffff810ce7b0-ffffffff810ce804: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810d53f0)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff810d53f0-ffffffff810d5444: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810d43c0)
Location: kernel/locking/semaphore.c:76
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff810d43c0-ffffffff810d4414: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810dc380)
Location: kernel/locking/semaphore.c:76
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff810dc380-ffffffff810dc3d4: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810e4960)
Location: kernel/locking/semaphore.c:76
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
**Symbols:**

```
ffffffff810e4960-ffffffff810e49b4: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810eff50)
Location: kernel/locking/semaphore.c:76
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
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
```
**Symbols:**

```
ffffffff810eff50-ffffffff810effa4: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810f7a30)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
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
```
**Symbols:**

```
ffffffff810f7a30-ffffffff810f7a8a: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff81103860)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call_irqsave
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
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
```
**Symbols:**

```
ffffffff81103860-ffffffff811038ba: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8110e3b0)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
  - kernel/seccomp.c:seccomp_notify_recv
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
**Symbols:**

```
ffffffff8110e3b0-ffffffff8110e40a: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8110b670)
Location: kernel/locking/semaphore.c:75
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
  - kernel/seccomp.c:seccomp_notify_recv
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
**Symbols:**

```
ffffffff8110b670-ffffffff8110b6ca: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8110d3d0)
Location: kernel/locking/semaphore.c:75
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
  - kernel/seccomp.c:seccomp_notify_recv
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
**Symbols:**

```
ffffffff8110d3d0-ffffffff8110d42a: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8112cc00)
Location: kernel/locking/semaphore.c:76
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
  - kernel/seccomp.c:seccomp_notify_recv
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
**Symbols:**

```
ffffffff8112cc00-ffffffff8112cc62: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8114de90)
Location: kernel/locking/semaphore.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
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
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_delete
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
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
```
**Symbols:**

```
ffffffff8114de90-ffffffff8114def6: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff820d06a0)
Location: kernel/locking/semaphore.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
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
```
**Symbols:**

```
ffffffff820d06a0-ffffffff820d0706: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff82154a30)
Location: kernel/locking/semaphore.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
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
```
**Symbols:**

```
ffffffff82154a30-ffffffff82154a96: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff82237870)
Location: kernel/locking/semaphore.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
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
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivars_register
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_acpi_prm_handler
```
**Symbols:**

```
ffffffff82237870-ffffffff822378d6: down_interruptible (STB_GLOBAL)
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
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffff800010168c30)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
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
```
**Symbols:**

```
ffff800010168c30-ffff800010168ce8: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (c03b5150)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
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
```
**Symbols:**

```
c03b5150-c03b51b8: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (c0000000001c0970)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_get_token_interruptible
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
c0000000001c0970-c0000000001c0a2c: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffe00010a720)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffe00010a720-ffffffe00010a77c: down_interruptible (STB_GLOBAL)
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
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810fcb70)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
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
```
**Symbols:**

```
ffffffff810fcb70-ffffffff810fcbca: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810ecd20)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
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
```
**Symbols:**

```
ffffffff810ecd20-ffffffff810ecd7a: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810f9d30)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
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
```
**Symbols:**

```
ffffffff810f9d30-ffffffff810f9d8a: down_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int down_interruptible(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff81104e40)
Location: kernel/locking/semaphore.c:75
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call_irqsave
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call
  - kernel/seccomp.c:seccomp_notify_ioctl
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivars_unregister
  - drivers/firmware/efi/vars.c:efivar_entry_set_get_size
  - drivers/firmware/efi/vars.c:efivar_entry_get
  - drivers/firmware/efi/vars.c:efivar_entry_size
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/vars.c:efivar_entry_remove
  - drivers/firmware/efi/vars.c:efivar_entry_add
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
  - drivers/firmware/efi/vars.c:efivar_init
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
```
**Symbols:**

```
ffffffff81104e40-ffffffff81104e9a: down_interruptible (STB_GLOBAL)
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
