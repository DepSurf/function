# Function: <code>__printk_ratelimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d6ba0)
Location: kernel/printk/printk.c:2776
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sysctl_binary.c:do_sysctl
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/audit.c:audit_printk_skb
  - kernel/audit.c:audit_log_start
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff810d6ba0-ffffffff810d6bba: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810db8e0)
Location: kernel/printk/printk.c:2918
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sysctl_binary.c:do_sysctl
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_printk_skb
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff810db8e0-ffffffff810db8fa: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e23b0)
Location: kernel/printk/printk.c:2750
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sysctl_binary.c:do_sysctl
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff810e23b0-ffffffff810e23ca: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e1650)
Location: kernel/printk/printk.c:2757
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/ss/services.c:context_struct_compute_av
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff810e1650-ffffffff810e166a: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e9790)
Location: kernel/printk/printk.c:2751
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/ss/services.c:context_struct_compute_av
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff810e9790-ffffffff810e97aa: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f1a60)
Location: kernel/printk/printk.c:2928
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_alloc
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff810f1a60-ffffffff810f1a7a: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fd110)
Location: kernel/printk/printk.c:2940
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff810fd110-ffffffff810fd12a: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81105820)
Location: kernel/printk/printk.c:3005
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/vmalloc.c:alloc_vmap_area
  - mm/cma.c:cma_alloc
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81105820-ffffffff8110583a: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81111ba0)
Location: kernel/printk/printk.c:3015
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/vmalloc.c:alloc_vmap_area
  - mm/cma.c:cma_alloc
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81111ba0-ffffffff81111bba: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111d270)
Location: kernel/printk/printk.c:3083
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/audit.c:audit_log_lost
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff8111d270-ffffffff8111d28a: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81117d40)
Location: kernel/printk/printk.c:3162
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/audit.c:audit_log_lost
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81117d40-ffffffff81117d5a: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118410)
Location: kernel/printk/printk.c:3226
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/audit.c:audit_log_lost
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81118410-ffffffff8111842a: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811387b0)
Location: kernel/printk/printk.c:3290
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:audit_log_lost
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff811387b0-ffffffff811387ca: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115b190)
Location: kernel/printk/printk.c:3546
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:gp_user_force_sig_segv
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:audit_log_lost
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff8115b190-ffffffff8115b1b2: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118d570)
Location: kernel/printk/printk.c:3809
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:audit_log_lost
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff8118d570-ffffffff8118d592: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119ed10)
Location: kernel/printk/printk.c:3850
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:audit_log_lost
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
**Symbols:**

```
ffffffff8119ed10-ffffffff8119ed32: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811aded0)
Location: kernel/printk/printk.c:3968
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:audit_log_lost
  - mm/vmalloc.c:alloc_vmap_area
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
**Symbols:**

```
ffffffff811aded0-ffffffff811adef2: __printk_ratelimit (STB_GLOBAL)
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
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010171ed0)
Location: kernel/printk/printk.c:3015
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/vmalloc.c:alloc_vmap_area
  - mm/cma.c:cma_alloc
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffff800010171ed0-ffff800010171f08: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c4c88)
Location: kernel/printk/printk.c:3015
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - mm/cma.c:cma_alloc
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - sound/core/pcm_lib.c:snd_pcm_update_hw_ptr0
```
**Symbols:**

```
c03c4c88-c03c4cb0: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001caea0)
Location: kernel/printk/printk.c:3015
Inline: False
Direct callers:
  - arch/powerpc/kernel/iommu.c:iommu_map_page
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
  - arch/powerpc/kernel/iommu.c:__iommu_free
  - arch/powerpc/kernel/iommu.c:iommu_range_alloc
  - arch/powerpc/platforms/pseries/iommu.c:tce_get_pSeriesLP
  - arch/powerpc/platforms/pseries/iommu.c:tce_free_pSeriesLP
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/vmalloc.c:alloc_vmap_area
  - mm/cma.c:cma_alloc
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
c0000000001caea0-c0000000001caee0: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010e2f4)
Location: kernel/printk/printk.c:3015
Inline: False
Direct callers:
  - arch/riscv/kernel/traps.c:do_trap
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/cma.c:cma_alloc
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffe00010e2f4-ffffffe00010e326: __printk_ratelimit (STB_GLOBAL)
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
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110a180)
Location: kernel/printk/printk.c:3015
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/vmalloc.c:alloc_vmap_area
  - mm/cma.c:cma_alloc
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff8110a180-ffffffff8110a19a: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fb060)
Location: kernel/printk/printk.c:3015
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/vmalloc.c:alloc_vmap_area
  - mm/cma.c:cma_alloc
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff810fb060-ffffffff810fb07a: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108070)
Location: kernel/printk/printk.c:3015
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/vmalloc.c:alloc_vmap_area
  - mm/cma.c:cma_alloc
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81108070-ffffffff8110808a: __printk_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __printk_ratelimit(const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81113410)
Location: kernel/printk/printk.c:3015
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - mm/vmalloc.c:alloc_vmap_area
  - mm/cma.c:cma_alloc
  - fs/quota/dquot.c:__quota_error
  - security/selinux/ss/services.c:context_struct_compute_av
  - drivers/acpi/apei/erst.c:pr_unimpl_nvram
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81113410-ffffffff8111342a: __printk_ratelimit (STB_GLOBAL)
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
