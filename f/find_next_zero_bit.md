# Function: <code>find_next_zero_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff813fdff0)
Location: lib/find_bit.c:70
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/pid.c:alloc_pid
  - mm/percpu.c:pcpu_next_unpop
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_trim_fs
  - block/blk-tag.c:blk_queue_start_tag
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:ida_get_new_above
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff813fdff0-ffffffff813fe010: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81445650)
Location: lib/find_bit.c:70
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/pid.c:alloc_pid
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - block/blk-tag.c:blk_queue_start_tag
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_get_empty_slot
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_add_filter
```
**Symbols:**

```
ffffffff81445650-ffffffff81445670: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81463e40)
Location: lib/find_bit.c:70
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/pid.c:alloc_pid
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - block/blk-tag.c:blk_queue_start_tag
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_get_empty_slot
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:sbitmap_get
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_add_filter
```
**Symbols:**

```
ffffffff81463e40-ffffffff81463e60: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81468ed0)
Location: lib/find_bit.c:70
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/pid.c:alloc_pid
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - block/blk-tag.c:blk_queue_start_tag
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_add_filter
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
```
**Symbols:**

```
ffffffff81468ed0-ffffffff81468ee2: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814951a0)
Location: lib/find_bit.c:70
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - block/blk-tag.c:blk_queue_start_tag
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_add_filter
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
```
**Symbols:**

```
ffffffff814951a0-ffffffff814951b2: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814ca580)
Location: lib/find_bit.c:80
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - block/blk-tag.c:blk_queue_start_tag
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
```
**Symbols:**

```
ffffffff814ca580-ffffffff814ca5e8: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814df2a0)
Location: lib/find_bit.c:80
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff814df2a0-ffffffff814df308: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8150b100)
Location: lib/find_bit.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff8150b100-ffffffff8150b162: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81528f20)
Location: lib/find_bit.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff81528f20-ffffffff81528f82: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8158c7b0)
Location: lib/find_bit.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:choose_devnum
  - drivers/usb/core/hub.c:choose_devnum
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
**Symbols:**

```
ffffffff8158c7b0-ffffffff8158c7ca: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815a9220)
Location: lib/find_bit.c:86
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:choose_devnum
  - drivers/usb/core/hub.c:choose_devnum
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
**Symbols:**

```
ffffffff815a9220-ffffffff815a923a: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff831c57b6)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060378)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062f83)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In kernel/sysctl.c (ffffffff810af186)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In mm/percpu.c (ffffffff8128aeac)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
```
In fs/file.c (ffffffff8134acaa)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/ext4/balloc.c (ffffffff813f1083)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8140466f)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff81426474)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In lib/bitmap.c (ffffffff815a8d12)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/sbitmap.c (ffffffff815ecd9f)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In lib/idr.c (ffffffff815f1cd2)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (ffffffff8161b1b6)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165c572)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/nvdimm/label.c (ffffffff8180fafe)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/usb/core/hub.c (ffffffff818aa3b1)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
```
```
In net/netlink/genetlink.c (ffffffff81a6dd41)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba0014)
Location: include/asm-generic/bitops/find.h:81
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb85e8)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
**Symbols:**

```
ffffffff81bc5795-ffffffff81bc57b6: find_next_zero_bit.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff832a64f2)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106952d)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106ce02)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In kernel/sysctl.c (ffffffff810c191b)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In mm/percpu.c (ffffffff812ca05c)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
```
In fs/file.c (ffffffff81398a8a)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/ext4/balloc.c (ffffffff81443044)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81456e1f)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff8147a123)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In lib/bitmap.c (ffffffff81611fb2)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/sbitmap.c (ffffffff81659cbf)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In lib/idr.c (ffffffff8165ee39)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (ffffffff8168a6c4)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816cebb2)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/nvdimm/label.c (ffffffff8189a04e)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/usb/core/hub.c (ffffffff8193f2cf)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
```
```
In net/netlink/genetlink.c (ffffffff81b273c1)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
```
In net/ncsi/ncsi-manage.c (ffffffff81c6d994)
Location: include/asm-generic/bitops/find.h:81
Inline: True
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88398)
Location: include/asm-generic/bitops/find.h:81
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
**Symbols:**

```
ffffffff81c9835a-ffffffff81c9837b: find_next_zero_bit.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff834556ec)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810766fa)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107a2fd)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In kernel/sysctl.c (ffffffff810d90f2)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In mm/percpu.c (ffffffff8132713b)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
```
In fs/file.c (ffffffff8141b2c9)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/ext4/balloc.c (ffffffff814bee82)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814d48ff)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff814fc3f1)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In security/landlock/fs.c (ffffffff8163a26c)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
```
```
In io_uring/io_uring.c (ffffffff816d3f6a)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fixed_fd_install
```
```
In lib/bitmap.c (ffffffff816de313)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/sbitmap.c (ffffffff81772415)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In lib/idr.c (ffffffff8177871b)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/vsprintf.c (ffffffff81785869)
Location: include/linux/find.h:89
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff817a78bf)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f7761)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_next_free_bar
```
```
In drivers/xen/grant-table.c (ffffffff818c7483)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/nvdimm/label.c (ffffffff819e2b92)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/usb/core/hub.c (ffffffff81a97657)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
```
```
In net/netlink/genetlink.c (ffffffff81cb033e)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f4d4)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35388)
Location: include/linux/find.h:89
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
**Symbols:**

```
ffffffff81e4784e-ffffffff81e47881: find_next_zero_bit.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83e73610)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810862c5)
Location: include/linux/find.h:138
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108b40b)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In kernel/sysctl.c (ffffffff810f7f5a)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In mm/percpu.c (ffffffff8139cbca)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
```
```
In fs/file.c (ffffffff814a7366)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/ext4/balloc.c (ffffffff81556d63)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8156d5bf)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff81596b4e)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In security/landlock/fs.c (ffffffff816f17fa)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
```
```
In io_uring/filetable.c (ffffffff8179420d)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - io_uring/filetable.c:__io_fixed_fd_install
```
```
In lib/bitmap.c (ffffffff817ce4cb)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/sbitmap.c (ffffffff818a2ca5)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff818bfe7f)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81923361)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_next_free_bar
```
```
In drivers/xen/grant-table.c (ffffffff81a17fc3)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/nvdimm/label.c (ffffffff81b5e776)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/usb/core/hub.c (ffffffff81c1a2ff)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
```
```
In net/netlink/genetlink.c (ffffffff81e6e0ea)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
```
In net/mptcp/pm_netlink.c (ffffffff82007bec)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff8200e01c)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In lib/idr.c (ffffffff820214cb)
Location: include/linux/find.h:138
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/vsprintf.c (ffffffff82042936)
Location: include/linux/find.h:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff836950d0)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088ef5)
Location: include/linux/find.h:173
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108e35e)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In kernel/sysctl.c (ffffffff8110431e)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In mm/percpu.c (ffffffff813cfca7)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
```
```
In mm/vmalloc.c (ffffffff81412dae)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_ram_vread_iter
```
```
In fs/file.c (ffffffff814dc346)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/ext4/balloc.c (ffffffff8158ef34)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815a54af)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff815cd56e)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In security/landlock/fs.c (ffffffff8172bc17)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - security/landlock/fs.c:is_access_to_paths_allowed
  - security/landlock/fs.c:is_access_to_paths_allowed
```
```
In io_uring/filetable.c (ffffffff817d4f00)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - io_uring/filetable.c:__io_fixed_fd_install
```
```
In lib/bitmap.c (ffffffff8180c97b)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/sbitmap.c (ffffffff818e5c8e)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_find_bit
```
```
In drivers/gpio/gpiolib.c (ffffffff81902e5f)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81967102)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/xen/grant-table.c (ffffffff81a61053)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/nvdimm/label.c (ffffffff81bb1d26)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/usb/core/hub.c (ffffffff81c81326)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
```
```
In drivers/firmware/efi/unaccepted_memory.c (ffffffff81dd46ca)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
```
```
In net/netlink/genetlink.c (ffffffff81eca20a)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
```
In net/mptcp/pm_netlink.c (ffffffff82083f6c)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff8208a908)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In lib/idr.c (ffffffff820a14fb)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/vsprintf.c (ffffffff820c0e9c)
Location: include/linux/find.h:173
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff838c5010)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108fd75)
Location: include/linux/find.h:173
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810956ee)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
```
```
In kernel/sysctl.c (ffffffff8110dc6e)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In mm/percpu.c (ffffffff813fa896)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
```
```
In mm/vmalloc.c (ffffffff8143f81e)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_ram_vread_iter
```
```
In fs/file.c (ffffffff8150e666)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/ext4/balloc.c (ffffffff815c7c44)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815de31f)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff81605dee)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In security/landlock/fs.c (ffffffff8176ccda)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - security/landlock/fs.c:scope_to_request
```
```
In io_uring/filetable.c (ffffffff81818d50)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - io_uring/filetable.c:__io_fixed_fd_install
```
```
In lib/bitmap.c (ffffffff81852bab)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_find_next_zero_area_off
```
```
In lib/sbitmap.c (ffffffff8192cc8e)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_find_bit
```
```
In drivers/gpio/gpiolib.c (ffffffff8194aa2f)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819b0832)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/xen/grant-table.c (ffffffff81ab3883)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_seq
```
```
In drivers/nvdimm/label.c (ffffffff81c06216)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/usb/core/hub.c (ffffffff81d35ada)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
```
```
In drivers/firmware/efi/unaccepted_memory.c (ffffffff81e8c791)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
```
```
In net/netlink/genetlink.c (ffffffff81f8e0ca)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
```
In net/mptcp/pm_netlink.c (ffffffff821595b9)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff821604cd)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In lib/idr.c (ffffffff821794eb)
Location: include/linux/find.h:173
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/vsprintf.c (ffffffff8219b7cc)
Location: include/linux/find.h:173
Inline: True
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
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffff800010633840)
Location: lib/find_bit.c:76
Inline: False
Direct callers:
  - arch/arm64/mm/context.c:check_and_switch_context
  - arch/arm64/mm/context.c:check_and_switch_context
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - lib/sbitmap.c:__sbitmap_get_word
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_domain_alloc
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_alloc
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_irq_msi_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_bitmap_alloc
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/scsi/sr.c:sr_probe
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/firmware/ti_sci.c:ti_sci_get_free_resource
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_alloc_bit
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_get_event_idx
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_add
  - drivers/perf/xgene_pmu.c:xgene_perf_add
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffff800010633840-ffff8000106338a8: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (c0000000007d8bf0)
Location: lib/find_bit.c:76
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_get_ipi
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/events/uprobes.c:handle_swbp
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_map_addr
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/scsi/sr.c:sr_probe
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
c0000000007d8bf0-c0000000007d8c74: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffe000461880)
Location: lib/find_bit.c:76
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_map_addr
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/scsi/sr.c:sr_probe
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffe000461880-ffffffe000461918: find_next_zero_bit (STB_GLOBAL)
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
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81521500)
Location: lib/find_bit.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff81521500-ffffffff81521562: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815117f0)
Location: lib/find_bit.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff815117f0-ffffffff81511852: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8151d590)
Location: lib/find_bit.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff8151d590-ffffffff8151d5f2: find_next_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int find_next_zero_bit(const long unsigned int *addr, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81536e00)
Location: lib/find_bit.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_unpop
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/sbitmap.c:__sbitmap_get_word
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff81536e00-ffffffff81536e62: find_next_zero_bit (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
